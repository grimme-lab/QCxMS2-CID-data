This archive contains input coordinate files and spectral data
for the test set used in the publication "Evaluation of the QCxMS2 method for the calculation of collision-induced-dissociation spectra via automated reaction network exploration"

# QCxMS2-CID-data
This archive contains the data of spectra calculations with QCxMS2 for the respective [publication]( DUMMY).
Each directory contains the input coordinates coord.xyz for each protomer of the compound, the "protomers" file with relative free energies in gas-phase and water,
the experimental data exp_hcdXXeV.csv and exp_cidXXeV.csv, QCxMS2 computed spectra at different levels of theory, simulated at different -esiatom energies without isotope pattern and only with masses
over 50 m/z. 
-GFN2-xTB energies on geometries: qcxms2_gfn2_gfn2_${esiat}eV_mthr50.dat
-wB97X-3c energies on GFN2-xTB geometries: qcxms2_wb97x3c_gfn2_${esiat}eV_mthr50.dat 
-g-xTB energies on GFN2-xTB geometries: qcxms2_gxtb_gfn2_${esiat}eV_mthr50.dat

-wB97X-3c energies on wB97X-3c geometries (only for hydroxyproline, aspartic acid, and histamine): qcxms2_wb97x3c_wb97x3c_${esiat}eV_mthr50.dat
and QCxMS computed spectra with GFN2-xTB with the settings "temprun esi2", "temprun esi6", and "collauto elab 70": 
gfn2_qcxms_temprunesi2.csv, gfn2_qcxms_temprunesi6.csv, gfn2_qcxms_collauto6elab70.csv
