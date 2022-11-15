# ML evalulation tool
The jupyter notebook contains a python script that was used to evaluate ceftraxone resistance in *Neisseria gonorrhoeae*
The code includes training and testing seven different machine learning models and evaluates the performance using the ROC curve.
It also has a code for shapley value which accounts for contribution of each mutations.

For the ceftriaxone resistance in *N. gonorrhoeae*, we used 97 known mutations. All the genomes were obtained from PathogenWatch database and SNPs were extracted using https://github.com/smha118/mutation_detector.



# Dependencies
The following versions of python and libraries were used. 
So anything higher than these should work, unless there are some major changes.

python: 3.8.13
panda: 1.4.2
sklern: 1.1.1
numpy: 1.20.3
matplotlib: 3.4.3



# Citation
The paper is currently under review but if you find this code useful you can cite the preprint below.

Sung Min Ha, Eric Lin, Jeffrey Klaunser et al. Machine learning to predict ceftriaxone resistance using single nucleotide polymorphisms within a global database of Neisseria gonorrhoeae genomes, 02 September 2022, PREPRINT (Version 1) available at Research Square [https://doi.org/10.21203/rs.3.rs-1999855/v1]

