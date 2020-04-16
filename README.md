# NAS-PaperReading
Notes for daily reading papers


### One-shot NAS
| Abb.| title | pdf | code | Brief| 
| :-: |:-: | :-: | :-: | :-:|
|SPOS|Single path one-shot neural architecture search with uniform sampling | [CVPR](https://arxiv.org/abs/1904.00420)|[Pytorch](https://github.com/ShunLu91/Single-Path-One-Shot-NAS) | [megvii technology]()| 
||Improving One-shot NAS by Suppressing the Posterior Fading|[ICLR2020](https://arxiv.org/pdf/1910.02543.pdf)|None|[SenseTime_Junjie Yan](http://valser.org/webinar/slide/slides/20191009/20191009-valse_automl_v3.pdf)|

### ICLR2020
[Open reviwer Link](https://openreview.net/group?id=ICLR.cc/2020/Conference)

| Abb.| title | pdf | code | Brief| 
| :-: |:-: | :-: | :-: | :-:|
|AtomNAS| AtomNAS: Fine-Grained End-to-End Neural Architecture Search| [ICLR2020](https://arxiv.org/pdf/1912.09640.pdf)|[pytorch](https://github.com/meijieru/AtomNAS)| |
|CRNAS| Computation Reallocation for Object Detection|[ICLR2020](https://openreview.net/forum?id=SkxLFaNKwB)|None|[SenseTime](https://mp.weixin.qq.com/s/Fjd6pGuJxCKcV8cPiLVw5g)|
||Evaluating The Search Phase of Neural Architecture Search|[ICLR2020](https://openreview.net/forum?id=H1loF2NFwr)|[pytorch](https://github.com/automl/RobustDARTS)|[EPFL]()|



### Have Read

| No. | Abb. | title | pdf | code | Brief| 
| :-: | :-: |:-: | :-: | :-: | :-:|
|1. |DARTS |DARTS: DIFFERENTIABLE ARCHITECTURE SEARCH|[ICLR 2019](https://arxiv.org/pdf/1806.09055.pdf) | [Pytorch1](https://github.com/quark0/darts); [Pytorch2](https://github.com/khanrc/pt.darts)  [Pytorch3](https://github.com/dragen1860/DARTS-PyTorch)| Architecture Search |
|2. | |Customizable Architecture Search for Semantic Segmentation|[CVPR 2019](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Customizable_Architecture_Search_for_Semantic_Segmentation_CVPR_2019_paper.pdf) | [NO] | Architecture Search; Classification |
|3. | |NAS-Unet: Neural Architecture Search for Medical Image Segmentation |[IEEE Access](https://www.researchgate.net/publication/332216927_NAS-Unet_Neural_Architecture_Search_for_Medical_Image_Segmentation) | [Pytorch](https://github.com/tianbaochou/NasUnet) | Architecture Search;  Medical Image Segmentation |
|4. |C2FNAS |C2FNAS: Coarse-to-Fine Neural Architecture Search for 3D Medical Image Segmentation |[arxiv](https://arxiv.org/pdf/1912.09628.pdf) | [NO] | Architecture Search;  Medical Image Segmentation |
|5. | HiNAS |Memory-Efficient Hierarchical Neural Architecture Search for Image Denoising |[CVPR2020](https://arxiv.org/pdf/1909.08228.pdf) | [NO] | Architecture Search; image denoising and de-raining|
|5.5|NAS-FCOS|NAS-FCOS: Fast Neural Architecture Search for Object Detection|[CVPR2020](https://arxiv.org/pdf/1906.04423.pdf) |[Pytorch](https://github.com/Lausannen/NAS-FCOS)|Object Detection; based on maskrcnn-benchmark|
|6. |Auto-deeplab (hnasnet)|Auto-deeplab: Hierarchical neural architecture search for semantic image segmentation|[CVPR 2019 oral](https://arxiv.org/abs/1901.02985) | [Tensorflow](https://github.com/tensorflow/models/tree/master/research/deeplab); [Pytorch1](https://github.com/MenghaoGuo/AutoDeeplab); [Pytorch2](https://github.com/NoamRosenberg/AutoML) | Architecture Search |
|7. |UnNAS| Are Labels Necessary for Neural Architecture Search? |[arxiv](https://arxiv.org/pdf/2003.12056.pdf)|None|[Note1](https://blog.csdn.net/saturdaysunset/article/details/105352342) [Note2](https://www.zhihu.com/question/358468168)|

####NAS#####

| No. | Abb.| title | pdf | code | Brief| 
| :-: | :-: |:-: | :-: | :-: | :-:|
|1. |NAS-FPN |NAS-FPN: Learning Scalable Feature Pyramid Architecture for Object Detection|[CVPR](https://arxiv.org/pdf/1904.07392.pdf) | [tensorflow](https://github.com/DetectionTeamUCAS/NAS_FPN_Tensorflow)| Architecture Search
|2. |SpineNet |SpineNet: Learning Scale-Permuted Backbone for Recognition and Localization|[CVPR](https://arxiv.org/pdf/1912.05027v1.pdf) | -- | Architecture Search
|3. | XNAS| XNAS: Neural Architecture Searchwith Expert Advice |[NeurIPS 2019](https://arxiv.org/pdf/1906.08031.pdf)| [Pytorch](https://github.com/NivNayman/XNAS) |[Poster](https://postersession.ai/poster/xnas-neural-architecture-search-with-exp/)|

| No. | Abb.| title | pdf | code | Brief| 
| :-: | :-: |:-: | :-: | :-: | :-:|
|1. |ENAS |Efficient Neural Architecture Search via Parameter Sharing|[ICML 2018](https://arxiv.org/pdf/1806.09055.pdf) | [tensorflow](https://github.com/melodyguan/enas); [Pytorch](https://github.com/carpedm20/ENAS-pytorch) | Architecture Search |
|2. |SMASH |SMASH: One-Shot Model Architecture Search through HyperNetworks|[ICLR 2018](https://arxiv.org/abs/1708.05344) | [Pytorch](https://github.com/ajbrock/SMASH) | Architecture Search |
|3. |ProxylessNAS |ProxylessNAS: Direct Neural Architecture Search on Target Task and Hardware|[ICLR 2019](https://arxiv.org/pdf/1812.00332.pdf) | [Pytorch&Tensorflow](https://github.com/mit-han-lab/ProxylessNAS) | Architecture Search |
|4. | |OPTIMIZATION AS A MODEL FOR FEW-SHOT LEARNING|[ICLR 2017](https://openreview.net/pdf?id=rJY0-Kcll) | [Pytorch](https://github.com/markdtw/meta-learning-lstm-pytorch);[Lua Torch](https://github.com/twitter/meta-learning-lstm)| Meta-learning; LSTM |
|5. | DPC |Searching for Efficient Multi-Scale Architectures for Dense Image Prediction|[NIPS 2018](https://arxiv.org/pdf/1809.04184.pdf) | [Link](https://zhuanlan.zhihu.com/p/46350372)| NAS; AutoML |
|6. | Matching Nets (MN) |Matching Networks for One Shot Learning|[NIPS 2016](https://arxiv.org/pdf/1606.04080.pdf) | [Tensorflow](https://github.com/AntreasAntoniou/MatchingNetworks); [Pytorch](https://github.com/BoyuanJiang/matching-networks-pytorch)| One-Shot Learning; AutoML |
