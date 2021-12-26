## Clustering of Bank Customers using LSTM-based encoder-decoder and Dynamic Time Warping
[arxiv link](https://arxiv.org/abs/2110.11769)
#### Ehsan Barkhordar, Mohammad Hassan Shirali-Shahreza, Hamidreza Sadeghi

* [Ehsan Barkhordar](https://ehsanbarkhordar.github.io/) - [Mohammad Hassan Shirali-Shahreza](https://shahreza.shirali.ir/) - [Hamidreza Sadeghi](https://www.linkedin.com/in/hamidrezasadeghi/)



### *Abstract:*
Clustering is an unsupervised data mining technique that can be employed to segment customers. The efficient clustering of customers enables banks to design and make offers based on the features of the target customers. The present study uses a real-world financial dataset (Berka, 2000) to cluster bank customers by an encoder-decoder network and the dynamic time warping (DTW) method. The customer features required for clustering are obtained in four ways: Dynamic Time Warping (DTW), Recency Frequency and Monetary (RFM), LSTM encoder-decoder network, and our proposed hybrid method. Once the LSTM model was trained by customer transaction data, a feature vector of each customer was automatically extracted by the encoder.Moreover, the distance between pairs of sequences of transaction amounts was obtained using DTW. Another vector feature was calculated for customers by RFM scoring. In the hybrid method, the feature vectors are combined from the encoder-decoder output, the DTW distance, and the demographic data (e.g., age and gender). Finally, feature vectors were introduced as input to the k-means clustering algorithm, and we compared clustering results with Silhouette and Davies-Bouldin index. As a result, the clusters obtained from the hybrid approach are more accurate and meaningful than those derived from individual clustering techniques. In addition, the type of neural network layers had a substantial effect on the clusters, and high network error does not necessarily worsen clustering performance. 

* Keywords: Clusterin, Bank customer clustering, Encoder-Decoder LSTM, Dynamic time warping, RFM analysis, Time series clustering
