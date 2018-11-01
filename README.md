# Ad-hoc Video Search


We provide frame-level CNN features for the following datasets that have been used by our winning entry for the TRECVID 2018 Ad-hoc Video Search (AVS) task.

1. The [IACC.3](https://www-nlpir.nist.gov/projects/tv2016/tv2016.html#IACC.3) dataset, which has been the test set for the TRECVID Ad-hoc Video Search (AVS) task since 2016. The dataset contains 4,593 Internet Archive videos (144 GB, 600 hours) with Creative Commons licenses in MPEG-4/H.264 format with duration ranging from 6.5 min to 9.5 min and a mean duration of almost 7.8 min. Automated shot boundary detection has been performed, resulting in 335,944 shots in total. From each shot we sampled frames uniformaly, obtaining 3,845,221 frames in total.
2. The [MSR-VTT](https://www.microsoft.com/en-us/research/publication/msr-vtt-a-large-video-description-dataset-for-bridging-video-and-language/) dataset, providing 10K web video clips and 200k natural sentences describing the visual content of the clips. The average number of sentences per clip is 20. From each clip we sampled frames uniformly, obtaining 305,462 frames in total. 
3. The [TGIF](http://raingo.github.io/TGIF-Release/) dataset, containing 100K animated GIFs and 120K sentences describing visual content of the animated GIFs. From each gif we sampled frames uniformly, obtaining 1,045,268 frames in total. 

## Downloads

## Video features

| CNN feature | Dimensionality | Downloads |
|:----- | -----:|:----- |
| ResNext-101 | 2,048 | [IACC.3 (27GB)](http://39.104.114.128/avs/iacc.3_ResNext-101.tar.gz), [MSR-VTT (2GB)](http://39.104.114.128/avs/msrvtt10k_ResNext-101.tar.gz), [TGIF (7GB)](http://39.104.114.128/avs/tgif_ResNext-101.tar.gz) |
| ResNet-152 | 2,048 | [IACC.3 (26GB)](http://39.104.114.128/avs/iacc.3_ResNet-152.tar.gz), [MSR-VTT (2GB)](http://39.104.114.128/avs/msrvtt10k_ResNet-152.tar.gz), [TGIF (7GB)](http://39.104.114.128/avs/tgif_ResNet-152.tar.gz) |

## Sentences 
* [MSR-VTT (3MB)](http://39.104.114.128/avs/msrvtt10k_textdata.tar.gz)
* [TGIF (2MB)](http://39.104.114.128/avs/tgif_textdata.tar.gz) 

## Citations

If you find the feature data useful, please consider citing 

* Xirong Li, Jianfeng Dong, Chaoxi Xu, Jing Cao, Xun Wang, Gang Yang, [Renmin University of China and  Zhejiang Gongshang University at TRECVID 2018: Deep Cross-Modal Embeddings for Video-Text Retrieval](http://lixirong.net/pub/trecvid2018-rucmm.pdf),  TRECVID Workshop, 2018

## Acknowledgments

* We thank the [TRECVID](https://trecvid.nist.gov/) team, the [MSR-VTT](https://www.microsoft.com/en-us/research/publication/msr-vtt-a-large-video-description-dataset-for-bridging-video-and-language/) team, and the [TGIF](http://raingo.github.io/TGIF-Release/) team for the datasets, the [UvA MediaMill](https://ivi.fnwi.uva.nl/isis/mediamill/) team for sharing their ResNext-101 model, and the MXNet team for sharing their [ResNet-152](http://data.mxnet.io/models/imagenet-11k/resnet-152/) model. 
