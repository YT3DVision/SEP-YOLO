# Abstract
Transparent object instance segmentation presents significant challenges in computer vision, due to the inherent properties of transparent objects, including boundary blur, low
contrast, and high dependence on background context. Exist
ing methods often fail as they depend on strong appearance
cues and clear boundaries. To address these limitations, we
propose SEP-YOLO, a novel framework that integrates a dual
domain collaborative mechanism for transparent object instance
segmentation. Our method incorporates a Frequency Domain
Detail Enhancement Module, which separates and enhances weak
high-frequency boundary components via learnable multi-scale
filtering. We further design a multi-scale spatial refinement
stream, which consists of a Content-Aware Alignment Neck and
a Multi-scale Gated Refinement Block, to ensure precise feature
alignment and boundary localization in deep semantic features.
We also provide high-quality instance-level annotations for the
Trans10K dataset, filling the critical data gap in transparent
object instance segmentation. Extensive experiments on the
Trans10K and GVD datasets show that SEP-YOLO achieves
state-of-the-art (SOTA) performance.

## Proceeding

Fengming Zhang, Tao Yan and Jianchao Huang, "SEP-YOLO: Fourier-Domain Feature Representation for Transparent Object Instance Segmentation," 2026 IEEE International Symposium on Circuits and Systems (ISCAS), Shanghai, China, 2026, pp. 140-144, doi: 10.1109/ISCAS66217.2026.11562174.

The paper link is https://ieeexplore.ieee.org/document/11562174.
## Network Architecture
![architecture](image/SEP-YOLO.jpg)


## Quantitative Comparisons
![QuantitativeComparisons](image/1.png)

## APs Comparisons

![APsComparisons](images/APsComparisons.png)
