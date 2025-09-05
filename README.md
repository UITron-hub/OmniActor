<div align="center">
  <h1>OmniActor: A Generalist GUI and Embodied Agent for 2D&3D Worlds</h1>
</div>

<div align="center">
<!-- <a href='https://arxiv.org/abs/2507.15509'><img src='https://img.shields.io/badge/Arxiv-2507.15509-b31b1b.svg?logo=arXiv'></a>&ensp;<a href='https://huggingface.co/collections/DocTron/chart-r1-68834834a239e09e9abcb5f4'><img src='https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face%20-models-blue'></a>&ensp;<a href=https://github.com/tatsu-lab/stanford_alpaca/blob/main/LICENSE><img src='https://img.shields.io/badge/License-Apache_2.0-green.svg'></a> -->
<img src='https://img.shields.io/badge/License-Apache_2.0-green.svg'></a>


Longrong Yang, Zhixiong Zeng*, Yufeng Zhong, Jing Huang, Liming Zheng, 
Lei Chen, Haibo Qiu, Zequn Qin, Lin Ma†, Xi Li†
</div>
<div align="center">
<strong>Meituan Group</strong>
</div>
<div align="center">
* Project leader. † Corresponding authors. 
</div>


---
**OmniActor** is an open-source high-performance generalist agent for GUI tasks in the 2D virtual world and embodied tasks in the 3D real world. OmniActor proposes Layer-heterogeneity MoE to eliminate the conflict between GUI and embodied data by separating deep-layer parameters, while leverage their synergy by sharing shallow-layer parameters, resembling the cerebrum-cerebellum mechanism in the human brain. By successfully leveraging the synergy and eliminating the conflict, OmniActor outperforms agents only trained by GUI or embodied data in GUI or embodied tasks. Furthermore, OmniActor unifies the action spaces of GUI and embodied tasks, and collect large-scale GUI and embodied data from various sources for training. This significantly improves OmniActor under different environments.
<div align="center">
<img src="./fig/pipeline.png"  width="80%">
</div>

## 📢 News and Updates
* ```2025.09.05``` Code and model are coming soon.
* ```2025.09.05``` 🔥🔥🔥 We release the technical report of **OmniActor**.


## 🤗 Models
| Model                | Base MLLM    | Download Link |
| --------------------- | ------------ | ------------- |
| OmniActor-GUI         | Qwen2-VL 7B  | -             |
| OmniActor-EA          | Qwen2-VL 7B  | -             |
| OmniActor-EA&GUI      | Qwen2-VL 7B  | -             |
| OmniActor hard        | Qwen2-VL 7B  | -             |
| OmniActor             | Qwen2-VL 7B  | -             |

## 📊 Performance
### ScreenSpot
<div align="center">
<img src="./fig/result.png"  width="80%">
</div>

## 📌 Acknowledgement
We sincerely appreciate [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) and [UItron](https://github.com/UITron-hub/UItron) for providing reference training frameworks.

