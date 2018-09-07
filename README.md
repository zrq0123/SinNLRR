# SinNLRR
SinNLRR: a robust subspace clustering meth-od for cell type detection by nonnegative and low rank representation

## Demo
% > Matlab R2016b <br />
% SinNLRR(path_data,path_label) <br />
% path_data is the path for data matrix, each column denotes a gene and each row denotes a cell <br />
% path_label is the the path for cells' labels <br />

[NMI,ARI,grps] = SinNLRR('single_data/Test_12_Goolam.txt','single_data/Test_12_Goolam_label.txt');


## Acknowlege

SubKit (https://github.com/sjtrny/SubKit))
