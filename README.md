# Fraud Detection in Elliptical Bitcoin Dataset Using GNN
Elliptical Bitcoin dataset is considered, where it’s combination of the 3 csv files, Edgelist, classes, and features. This dataset is collected from bitcoin blockchain. Nodes in this dataset are transaction information. An edge represents relation between one transaction and another. Each node has 166 features and is labelled as either scam, licit or unknown. 
The motivation behind selecting this dataset is to combat the threat of hackers attempting to infiltrate the blockchain and steal funds, making it challenging to trace the original IP address of the device used. Identifying illicit transactions is crucial for maintaining the integrity of the network and ensuring user trust.
The preprocessing of the dataset involves assigning edges, classes, and features. The dataset is divided into three parts based on the transaction ID, and the class labels are encoded to distinguish between illicit, licit, and unknown transactions. Due to the dataset's density, batch normalization is employed to alleviate computational power constraints. This technique calculates the average of each batch and divides it by each element, thereby optimizing processing efficiency


##### This model code was taken from baseline models from GitHub.
Source :  https://medium.com/@adjcs224w/illicit-transaction-detection-in-graph-networks-c0d381d85999

### References: 
•	Weber, M., Domeniconi, G., Chen, J., Weidele, D. K., Bellei, C., Robinson, T., & Leiserson, C. E. (2019). Anti-Money Laundering in Bitcoin: Experimenting with Graph Convolutional Networks for Financial Forensics. ArXiv. /abs/1908.02591
•	AmolDominicJosh. (2023, December 15). Illicit Transaction Detection in Graph Networks.
•	GAT fraud detection. illicit-f1=0.89. (n.d.). Kaggle.com
•	Veličković, P., Cucurull, G., Casanova, A., Romero, A., Liò, P., & Bengio, Y. (2017). Graph Attention Networks. ArXiv. /abs/1710.10903
•	Hamilton, W. L., Ying, R., & Leskovec, J. (2017). Inductive Representation Learning on Large Graphs. ArXiv. /abs/1706.02216
