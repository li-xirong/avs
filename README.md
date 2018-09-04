# Ad-hoc Video Search


We provide frame-level CNN features for the [IACC.3](https://www-nlpir.nist.gov/projects/tv2016/tv2016.html#IACC.3) dataset, which has been the test set for the TRECVID Ad-hoc Video Search (AVS) task since 2016. The dataset contains 4,593 Internet Archive videos (144 GB, 600 hours) with Creative Commons licenses in MPEG-4/H.264 format with duration ranging from 6.5 min to 9.5 min and a mean duration of almost 7.8 min. Automated shot boundary detection has been performed, resulting in 335,944 shots in total. From each shot we sampled frames uniformaly, obtaining 3,845,221 frames in total.

| CNN feature | Dimensionality |
|:----- | -----:| 
| ResNext-101 | 2,048 |

## Citations

If you find the feature data useful, please consider citing 

* Xirong Li, Jianfeng Dong, Chaoxi Xu, Jing Cao, Renmin University of China and  Zhejiang Gongshang University at TRECVID 2018: Deep Cross-Modal Embeddings for Video-Text Retrieval,  TRECVID Workshop, 2018

## Acknowledgments

* We thank the [TRECVID](https://trecvid.nist.gov/) team for providing the IACC.3 dataset.
* We thank the [MediaMill](https://ivi.fnwi.uva.nl/isis/mediamill/) team at the University of Amsterdam for generously providing their trained ResNext-101 model. 
