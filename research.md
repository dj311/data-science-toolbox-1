# Research

Following topics:

  - What are the broad types of data?
  - What are the main types of resource?
  - What type of problems can the resources solve?
  - Are there any generic data science resources that might be applicable? In what sense are they applicable?
  - How might the approach be compared to other approaches, and/or applied across different datasets?

## Resources

Stochastic Identification of Malware with Dynamic Traces (https://arxiv.org/pdf/1404.2462.pdf):

Using program runtime traces as a data source and applying Markov chains to classify them as malware:
  - Can we find good data for this?
  - www.secrepo.com linked to http://panda.gtisc.gatech.edu/malrec/ which has links to “RR log” files (execution traces of malware)
  - Would need to find “nice” execution traces as well.
  - RR files can be read and recorded by https://github.com/moyix/panda-malrec

A Markov Chain Model of Temporal Behavior for Anomaly Detection (http://projects.laas.fr/METROSEC/DOC/WA1_1.pdf):

> Gets a bunch of records associating users with events (e.g. resource accesses) including process id’s etc. Then tries to learn a transition probability matrix for normal and bad behaviour over time.

https://www.r-bloggers.com/data-mining-for-network-security-and-intrusion-detection/  using data mining for network security and intrusion detection

https://medium.com/cyberdefenders/python-for-cybersecurity-lesson-3-data-analysis-with-pandas-501441e14fe0  python codes

Survey Paper: https://ieeexplore.ieee.org/abstract/document/7307098/

  - Quote:
    > There are three main types of cyber analytics in support of IDSs [intrusion detection systems]: misuse-based (sometimes also called signature-based), anomaly-based, and hybrid.
    >
    > Misuse-based techniques are designed to detect known attacks by using signatures of those attacks. They are effective for detecting known type of attacks without generating an overwhelming number of false alarms. They require frequent manual updates of the database with rules and signatures. Misuse-based techniques cannot detect novel (zero-day) attacks.
    >
    > Anomaly-based techniques model the normal network and system behaviour, and identify anomalies as deviations from normal behaviour. They are appealing because of their ability to detect zero-day attacks. Another advantage is that the profiles of normal activity are customized for every system, application, or network, thereby making it difficult for attackers to know which activities they can carry out undetected. Additionally, the data on which anomaly-based techniques alert (novel attacks) can be used to define the signatures for misuse detectors. The main disadvantage of anomaly-based techniques is the potential for high false alarm rates (FARs) because previously unseen (yet legitimate) system behaviors may be categorized as anomalies.
    >
    > Hybrid techniques combine misuse and anomaly detection.

Another survey paper: https://www.sciencedirect.com/science/article/pii/S108480451200183X

Zeus malware analysis (http://www.secrepo.com/Datasets%20Description/PE_malware/Zeus.html) with paper (https://alrawi.github.io/static/papers/unzeus_www13.pdf):

  - Uses multiple techniques (k-NN, decision/classification trees, support vector machine, and Logistic Regression), then compares them
  - Uses of the shelf algorithms from mlpy (http://mlpy.sourceforge.net/)
  - Data source generated using [automal](https://dl.acm.org/citation.cfm?id=2906041.2906045)
  - Can we apply this technique to malicious URLS? Can use [this work](https://github.com/surajr/URL-Classification/blob/master/URL%20Classification.ipynb) as a basis (TODO: Check licensing).

Look at "weird" network data (http://www.secrepo.com/Datasets%20Description/Network/weird.html). Description of workflow and analysis is at https://www.sans.org/reading-room/whitepapers/detection/intrusion-detection-relationship-analysis-37352.

https://github.com/sooshie/Security-Data-Analysis  (security data anaylsis) 

## Techniques

Try to find resources which use all three of these techniques.

### Classical Statistics

To do

### Machine Learning

Techniques within machine learning:

  - Clustering (e.g. k-means https://ieeexplore.ieee.org/document/5231545, https://pdfs.semanticscholar.org/634e/2f1a20755e7ab18e8e8094f48e140a32dacd.pdf, https://perso.telecom-paristech.fr/qleroy/aml/lab5.html)

### Neural Networks

To do

## Data

Try to find resources which use all these types of data.

### Network Analysis

To do

### Log Files

To do

### Program Execution Traces
To do
