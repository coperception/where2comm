# Where2comm
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

[**Where2comm: Communication-Efficient Collaborative Perception via Spatial Confidence Maps</a>**](https://arxiv.org/abs/2209.12836)
<br>
<a href="https://scholar.google.com/citations?user=XBbwb78AAAAJ&hl=zh-CN"> Yue Hu, <a href="https://github.com/dongfeng12"> Shaoheng Fang, <a href="https://chezacar.github.io/">Zixing Lei, <a href="https://github.com/Kay1794"> Yiqi Zhong, <a href="https://siheng-chen.github.io/">Siheng Chen</a> 
<br>
Presented at [Neurips 2022 Spotlight](https://nips.cc/)

![Where2comm](./static/images/dair_3d_18.gif)
<div align='center' ><font size='2'>Single agent detection v.s. collaborative perception</font></div>

See our code at https://github.com/MediaBrain-SJTU/Where2comm.

## Main idea
**Abstract:** Multi-agent collaborative perception could significantly upgrade the perception performance by enabling agents to share complementary information with each other through communication. It inevitably results in a fundamental trade-off between perception performance and communication bandwidth. To tackle this bottleneck issue, we propose a spatial confidence map, which reflects the spatial heterogeneity of perceptual information. It empowers agents to only share spatially sparse, yet perceptually critical information, contributing to where to communicate. 

![Where2comm](./static/images/Intro.png)

## Features

- Dataset Support
  - [x] DAIR-V2X
  - [ ] OPV2V
  - [ ] V2X-Sim 2.0

- SOTA collaborative perception method support
    - [x] [Where2comm [Neurips2022]](https://arxiv.org/abs/2209.12836)
    - [x] [V2VNet [ECCV2020]](https://arxiv.org/abs/2008.07519)
    - [x] [DiscoNet [NeurIPS2021]](https://arxiv.org/abs/2111.00643)
    - [x] [V2X-ViT [ECCV2022]](https://arxiv.org/abs/2203.10638)
    - [x] [When2com [CVPR2020]](https://arxiv.org/abs/2006.00176)
    - [x] Late Fusion
    - [x] Early Fusion

- Visualization
  - [x] BEV visualization
  - [x] 3D visualization

## Citation

If you find this code useful in your research then please cite

```
@inproceedings{Where2comm:22,
  author    = {Yue Hu, Shaoheng Fang, Zixing Lei, Yiqi Zhong, Siheng Chen},
  title     = {Where2comm: Communication-Efficient Collaborative Perception via Spatial Confidence Maps},
  booktitle = {Thirty-sixth Conference on Neural Information Processing Systems (Neurips)},
  month     = {November},  
  year      = {2022}
}
```

## Acknowledgements
Thank for the excellent cooperative perception codebases [OpenCOOD](https://github.com/DerrickXuNu/OpenCOOD) and [CoPerception](https://github.com/coperception/coperception).

Thank for the excellent cooperative perception datasets [DAIR-V2X](https://thudair.baai.ac.cn/index), [OPV2V](https://mobility-lab.seas.ucla.edu/opv2v/) and [V2X-SIM](https://ai4ce.github.io/V2X-Sim/).

Thank for the dataset and code support by [YiFan Lu](https://github.com/yifanlu0227).

## Relevant Projects

Thanks for the insightful previous works in cooperative perception field.


**V2vnet: Vehicle-to-vehicle communication for joint perception and prediction** 
*ECCV20* [[Paper]](https://arxiv.org/abs/2008.07519) 

**When2com: Multi-agent perception via communication graph grouping** 
*CVPR20* [[Paper]](https://arxiv.org/abs/2006.00176) [[Code]](https://arxiv.org/abs/2006.00176)

**Who2com: Collaborative Perception via Learnable Handshake Communication** 
*ICRA20* [[Paper]](https://arxiv.org/abs/2003.09575?context=cs.RO)

**Learning Distilled Collaboration Graph for Multi-Agent Perception** 
*Neurips21* [[Paper]](https://arxiv.org/abs/2111.00643) [[Code]](https://github.com/DerrickXuNu/OpenCOOD)

**V2X-Sim: A Virtual Collaborative Perception Dataset and Benchmark for Autonomous Driving** 
*RAL21* [[Paper]](https://arxiv.org/abs/2111.00643) [[Website]](https://ai4ce.github.io/V2X-Sim/)[[Code]](https://github.com/ai4ce/V2X-Sim)

**OPV2V: An Open Benchmark Dataset and Fusion Pipeline for Perception with Vehicle-to-Vehicle Communication** 
*ICRA2022* [[Paper]](https://arxiv.org/abs/2109.07644) [[Website]](https://mobility-lab.seas.ucla.edu/opv2v/) [[Code]](https://github.com/DerrickXuNu/OpenCOOD)

**V2X-ViT: Vehicle-to-Everything Cooperative Perception with Vision Transformer** *ECCV2022* [[Paper]](https://arxiv.org/abs/2203.10638) [[Code]](https://github.com/DerrickXuNu/v2x-vit) [[Talk]](https://course.zhidx.com/c/MmQ1YWUyMzM1M2I3YzVlZjE1NzM=)

**Self-Supervised Collaborative Scene Completion: Towards Task-Agnostic Multi-Robot Perception** 
*CoRL2022* [[Paper]](https://openreview.net/forum?id=hW0tcXOJas2)

**CoBEVT: Cooperative Bird's Eye View Semantic Segmentation with Sparse Transformers** *CoRL2022* [[Paper]](https://arxiv.org/abs/2207.02202) [[Code]](https://github.com/DerrickXuNu/CoBEVT)

**DAIR-V2X: A Large-Scale Dataset for Vehicle-Infrastructure Cooperative 3D Object Detection** *CVPR2022* [[Paper]](https://arxiv.org/abs/2204.05575) [[Website]](https://thudair.baai.ac.cn/index) [[Code]](https://github.com/AIR-THU/DAIR-V2X)


## Contact

If you have any problem with this code, please feel free to contact **18671129361@sjtu.edu.cn**.
