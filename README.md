# Network_Intrusion_Detection_DataMining
 This GitHub repository is dedicated to a data mining course project focusing on network intrusion detection using machine learning techniques. It provides resources and datasets for building and evaluating ML models to enhance network security. Ideal for students and researchers in the field of cybersecurity and data mining.


# Dataset link
[https://www.kaggle.com/datasets/aryashah2k/nfuqnidsv2-network-intrusion-detection-dataset](https://www.kaggle.com/datasets/agungpambudi/network-malware-detection-connection-analysis/data?select=CTU-IoT-Malware-Capture-1-1conn.log.labeled.csv)

# Dataset Description
A comprehensive dataset, merging all the aforementioned datasets mentioned in https://staff.itee.uq.edu.au/marius/NIDS_datasets/#RA5

The newly published dataset represents the benefits of shared dataset feature sets, where the merging of multiple smaller ones is possible. This will eventually lead to a bigger and more universal NIDS dataset containing flows from multiple network setups and different attack settings.

An additional label feature identifies the original dataset of each flow. This can be used to compare the same attack scenarios conducted over two or more different test-bed networks. The attack categories have been modified to combine all parent categories.

Attacks named DoS attacks-Hulk, DoS attacks-SlowHTTPTest, DoS attacks-GoldenEye and DoS attacks-Slowloris have been renamed to the parent DoS category. Attacks named DDOS attack-LOIC-UDP, DDOS attack-HOIC and DDoS attacks-LOIC-HTTP have been renamed to DDoS. Attacks named FTP-BruteForce, SSH-Bruteforce, Brute Force -Web and Brute Force -XSS have been combined as a brute-force category. Finally, SQL Injection attacks have been included in the injection attacks category.

The NF-UQ-NIDS dataset has a total of 11,994,893 records, out of which 9,208,048 (76.77%) are benign flows and 2,786,845 (23.23%) are attacks. The table below lists the distribution of the final attack categories.
