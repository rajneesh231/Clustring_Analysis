# Cluster analysis using Pycaret
### Details
- Dataset - "seeds" dataset from pycaret.datasets

- Clustering algorithms :- K-means, Hierarchical, Birch


### Result
- Best Clustering Algo: K-Means - No Preprocessing
- Best Silhouette Score:  0.4714  
- Best Number of Cluster: 3
  
| Preprocessing           | Clusters | Silhouette | Calinski-Harabasz | Davies-Bouldin |
|--------------------------|----------|------------|-------------------|----------------|
| K-Means - No Preprocessing | c=3      | 0.4714     | 370.1834          | 0.7563         |
| K-Means - No Preprocessing | c=4      | 0.4140     | 323.7788          | 0.8202         |
| K-Means - No Preprocessing | c=5      | 0.3698     | 305.5448          | 0.8789         |
| Hierarchical - No Preprocessing | c=3  | 0.4517     | 340.9872          | 0.7838         |
| Hierarchical - No Preprocessing | c=4  | 0.3717     | 288.0574          | 0.8914         |
| Hierarchical - No Preprocessing | c=5  | 0.3394     | 268.1505          | 0.8636         |
| Birch - No Preprocessing | c=3          | 0.4003     | 282.0376          | 0.8620         |
| Birch - No Preprocessing | c=4          | 0.3627     | 298.1573          | 0.9198         |
| Birch - No Preprocessing | c=5          | 0.3571     | 281.8176          | 0.8779         |
| K-Means - Normalize      | c=3          | 0.4419     | 330.9761          | 0.7789         |
| K-Means - Normalize      | c=4          | 0.3357     | 270.4963          | 1.0641         |
| K-Means - Normalize      | c=5          | 0.2926     | 237.9721          | 1.1069         |
| Hierarchical - Normalize | c=3          | 0.4256     | 297.9830          | 0.8462         |
| Hierarchical - Normalize | c=4          | 0.3525     | 218.4550          | 1.5536         |
| Hierarchical - Normalize | c=5          | 0.3075     | 214.4040          | 1.4734         |
| Birch - Normalize        | c=3          | 0.3478     | 255.2645          | 0.9641         |
| Birch - Normalize        | c=4          | 0.2872     | 191.9383          | 1.0507         |
| Birch - Normalize        | c=5          | 0.2669     | 180.3051          | 1.1950         |
| K-Means - Transform      | c=3          | 0.4419     | 330.9761          | 0.7789         |
| K-Means - Transform      | c=4          | 0.3357     | 270.4963          | 1.0641         |
| K-Means - Transform      | c=5          | 0.2872     | 237.9721          | 1.1069         |
| Hierarchical - Transform | c=3          | 0.4256     | 297.9830          | 0.8462         |
| Hierarchical - Transform | c=4          | 0.3525     | 218.4550          | 1.5536         |
| Hierarchical - Transform | c=5          | 0.3075     | 214.4040          | 1.4734         |
| Birch - Transform        | c=3          | 0.3478     | 255.2645          | 0.9641         |
| Birch - Transform        | c=4          | 0.2872     | 191.9383          | 1.0507         |
| Birch - Transform        | c=5          | 0.2669     | 180.3051          | 1.1950         |
| K-Means - PCA            | c=3          | 0.4419     | 330.9761          | 0.7789         |
| K-Means - PCA            | c=4          | 0.3357     | 270.4963          | 1.0641         |
| K-Means - PCA            | c=5          | 0.2872     | 237.9721          | 1.1069         |
| Hierarchical - PCA       | c=3          | 0.4256     | 297.9830          | 0.8462         |
| Hierarchical - PCA       | c=4          | 0.3525     | 218.4550          | 1.5536         |
| Hierarchical - PCA       | c=5          | 0.3075     | 214.4040          | 1.4734         |
| Birch - PCA              | c=3          | 0.3478     | 255.2645          | 0.9641         |
| Birch - PCA              | c=4          | 0.2872     | 191.9383          | 1.0507         |
| Birch - PCA              | c=5          | 0.2669     | 180.3051          | 1.1950         |
| K-Means - T+N            | c=3          | 0.4419     | 330.9761          | 0.7789         |
| K-Means - T+N            | c=4          | 0.3357     | 270.4963          | 1.0641         |
| K-Means - T+N            | c=5          | 0.2973     | 237.9721          | 1.1288         |
| Hierarchical - T+N       | c=3          | 0.4256     | 297.9830          | 0.8462         |
| Hierarchical - T+N       | c=4          | 0.3525     | 218.4550          | 1.5536         |
| Hierarchical - T+N       | c=5          | 0.3075     | 214.4040          | 1.4734         |
| Birch - T+N              | c=3          | 0.4419     | 330.9761          | 0.7789         |
| Birch - T+N              | c=4          | 0.3357     | 270.4963          | 1.0641         |
| Birch - T+N              | c=5          | 0.2989     | 237.9721          | 1.1631         |
| K-Means - T+N+PCA        | c=3          | 0.4419     | 330.9761          | 0.7789         |
| K-Means - T+N+PCA        | c=4          | 0.3357     | 270.4963          | 1.0641         |
| K-Means - T+N+PCA        | c=5          | 0.2973     | 237.9721          | 1.1288         |
| Hierarchical - T+N+PCA   | c=3          | 0.4256     | 297.9830          | 0.8462         |
| Hierarchical - T+N+PCA   | c=4          | 0.3525     | 218.4550          | 1.5536         |
| Hierarchical - T+N+PCA   | c=5          | 0.3075     | 214.4040          | 1.4734         |
| Birch - T+N+PCA          | c=3          | 0.4419     | 330.9761          | 0.7789         |
| Birch - T+N+PCA          | c=4          | 0.3357     | 270.4963          | 1.0641         |
| Birch - T+N+PCA          | c=5          | 0.2989     | 237.9721          | 1.1631         |
