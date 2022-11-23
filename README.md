# A clustering/anomaly detection machine learning algorithm for near-shore ADCP data processing
Alexander Knysh, [Google Colab notebook](https://github.com/alexanderknysh/adcpml/blob/main/adcpml.ipynb).

[![colab](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/alexanderknysh/adcpml/blob/main/adcpml.ipynb)

## Description 
The present algorithm aims to select several typical and extreme environmental data samples from near-shore Acoustic Doppler Current Profiler (ADCP) measurements for further marine engineering analysis. Performance of the metod as well as the hyperparameter tuning are demonstrated on the example of ADCP datasets obtained by the Wood Island research site, Maine, USA. Two ADCPs were used to monitor environmental conditions around a kelp farm installation and wer placed *42 m* away from each other. The devices measured water depth, significant wave height, significant wave period, and current velocity profiles over *15 min* intervals from May 16 to May 28, 2019.

![](https://user-images.githubusercontent.com/46943028/203622001-0b92fbfe-6029-4542-bce7-f0d0f55905bf.JPG)

Two ADCPs measured water depth, significant wave height and period, as well as north and east projections of current velocity profiles during a half of a month period. The detailed description of the machine learning algorithm and the corresponding interactive cloud code can be found in [this Google Colab notebook](https://github.com/alexanderknysh/adcpml/blob/main/adcpml.ipynb).

The following machine learning study aims to select several typical and several anomalous loadcases (about 20-30 loadcases in total) from a detailed ADCP datasets obtained at the Wood Island research site, Maine, USA. Two ADCPs measured water depth, significant wave height and period, as well as north and east projections of current velocity profiles (15 minute averages) during a half of a month period. More details on the research can be found in Section 3.2 of this paper.


More details on the research can be found in [Section 3.2 of the paper below](https://github.com/alexanderknysh/thinplaterbf/blob/main/Methodology%20for%20multidimensional%20approximation%20of%20current%20velocity%20fields%20around%20offshore%20aquaculture%20installations.pdf).

[![paper](https://user-images.githubusercontent.com/46943028/202962633-1310e67e-1372-40e5-afa2-7a5e91813450.PNG)](https://github.com/alexanderknysh/thinplaterbf/blob/main/Methodology%20for%20multidimensional%20approximation%20of%20current%20velocity%20fields%20around%20offshore%20aquaculture%20installations.pdf)
