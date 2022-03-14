# DeFiTraps
This repository provides the dataset and the tool for the paper "DeFiDefender: Investigating and Detecting Decentralized Financial Traps in Ethereum Smart Contracts". We will make the tool avaliable when the paper is published. 

1. Due to the file size limitation of Github, we upload our dataset to the Google dirve, while could be found at: https://drive.google.com/drive/folders/164yvbsJYmV9lpoew45aFAT2r7rvK3o4w. The file "dataset.zip" contains all the 20,679 verified (open-sourced) DeFi related smart contracts collected from Etherscan

2. result_total-fse.txt contains the results of 20,679 Ethereum DeFi related smart contracts. 

3. labeled.txt is the result based on manually effort, which contains sixe lines for each examples. 

The first line contains the contract address and its main contract name. The first line endwith Y or N. If the it ends with Y, which means all the prediction is correct; Otherwise, there must be at least one error case. 

The second to sixth lines contains the prediction result. If the result ends with  "==> error", which refers to an error case. 

The source code can be found at Etherscan by using address https://etherscan.io/address/...#code  You need to replace ... with the address, e.g, https://etherscan.io/address/0a25400e0b185077bd0d52a1cac7e46e38aa585e#code
