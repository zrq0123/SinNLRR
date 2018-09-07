# SinNLRR
SinNLRR: a robust subspace clustering meth-od for cell type detection by nonnegative and low rank representation

## Demo

% SinNLRR(path_data,path_label)
% path_data is the the data matrix, each column denotes a gene and each row denotes a cell 

[NMI,ARI,grps] = SinNLRR('../single_MPSSC/Test_12_Goolam.txt','../single_MPSSC/Test_12_Goolam_label.txt');


## Acknowlege

SubKit (https://github.com/sjtrny/SubKit))
