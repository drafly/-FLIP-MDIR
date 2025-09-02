# <p align=center> `FLIP-MDIR:A Benchmark for Multi-Degraded Medical Image Restoration from fiber-bundle endomicroscopy`</p>

(The datasets are hosted on Baidu Netdisk)
| Download Link | Description | 
|:-----: |:-----: |
| [Baidu Netdisk](https://pan.baidu.com/s/1YkCvpEBmSlK01CWr6u8VPw) (18o8) | A total of 51872 pairs for training, 6448 pairs for validation and 6368 pairs for testing. |

### Data acquisition platform 
![Example](figure/platform.pdf)
Our data acquisition platform with beam splitter equipment, which enables us to collect real-world degraded-clean image pairs simultaneously. (a) Schematic diagram of our beam splitter equipment.
(b) Physical Diagram of our beam splitter equipment. (c) Pathological sections used in dataset collection.

### Dataset Property
![Example](figure/properties.pdf)
There are 48 different diseases in our dataset, and the number of diseases varies because of the different sizes of tissue sections.

Visualization of clustering based on low-level features of our dataset. 
![Example](figure/gmm_out1.pdf)
![Example](figure/GIST results.pdf)
Top: Visualizing GIST features of our dataset using t-sne and Gaussian Mixture Models (GMM). Bottom: Cluster-center example of each cluster.

### Comparison with Previous Datasets
![Example](figure/Comparison.pdf)
Comparison on the existing synthesized datasets and the FLIP-MDIR dataset.

### Image Complexity Analysis
![Example](figure/PSNR.pdf)
Our dataset contains a significantly higher proportion of challenging examples characterized by low PSNR and SSIM scores.
