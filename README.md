# Predicting-Transparent-Conductors
High-quality data are provided for 3,000 materials that show promise as transparent conductors. The following information has been included:

Spacegroup alabelidentifyingthesymmetryofthematerial
Total number of Al, Ga, In and O atoms in the unit cell (Ntotal)
Relative compositions of Al, Ga, and In (x, y, z)
Lattice vectors and angles: lv1, lv2, lv3 whicharelengthsgiveninunitsofangstroms(\(10−10\)meters and α, β, γ whichareanglesindegreesbetween0°and360°

The task for this competition is to predict two target properties:

Formation energy an importan indicator of the stability of a material
Bandgap energy an important property for opto electronic applications

# Data description

Note: For each line of the CSV file, the corresponding spatial positions of all of the atoms in the unit cell expressedinCartesiancoordinates are provided as a separate file.

train.csv - contains a set of materials for which the bandgap and formation energies are provided

test.csv - contains the set of materials for which you must predict the bandgap and formation energies

/{train|test}/{id}/geometry.xyz - files with spatial information about the material. The file name corresponds to the id in the respective csv files.

# Datasets
you can find all csv data on 
https://www.kaggle.com/c/nomad2018-predict-transparent-conductors/data
