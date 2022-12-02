# MSGDN
An algorithm for VVC post-processing, which achieves the best PSNR in the CLIC2020 competition

Multi-scale Grouped Dense Network for VVC Intra Coding
>[**MSGDN**](https://arxiv.org/abs/2005.07896) Xin Li, Simeng Sun, Zhizheng Zhang, Zhibo Chen

> Accepted by CVPR2020 Workshop 

![image](https://github.com/lixinustc/MSGDN/blob/main/figs/MSGDN.png)


## Abstract
Versatile Video Coding (H.266/VVC) standard achieves
better image quality when keeping the same bits than any
other conventional image codec, such as BPG, JPEG, and
etc. However, it is still attractive and challenging to improve the image quality with high compression ratio on the
basis of traditional coding techniques. In this paper, we
design the multi-scale grouped dense network (MSGDN) to
further reduce the compression artifacts by combining the
multi-scale and grouped dense block, which are integrated
as the post-process network of VVC intra coding. Besides,
to improve the subjective quality of compressed image, we
also present a generative adversarial network (MSGDNGAN) by utilizing our MSGDN as generator. Across the extensive experiments on validation set, our MSGDN trained
by MSE losses yields the PSNR of 32.622 on average with
teams ”IMC” and ”haha” at the bit-rate of 0.15 in Lowrate track. Moreover, our MSGDN-GAN could achieve the
better subjective performance.


## Usages
The code will be released soon

## Cite US

Please cite us if this work is helpful to you.

```
@inproceedings{li2020multi,
  title={Multi-scale grouped dense network for VVC intra coding},
  author={Li, Xin and Sun, Simeng and Zhang, Zhizheng and Chen, Zhibo},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops},
  pages={158--159},
  year={2020}
}
```



