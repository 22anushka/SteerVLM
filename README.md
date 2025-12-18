# SteerVLM
Official Page for SteerVLM [EMNLP2025].

**SteerVLM: Robust Model Control through Lightweight Activation Steering for Vision-Language Models**
*Anushka Sivakumar, Andrew Zhang, Zaber Hakim, Chris Thomas*
[Virginia Tech]

Visit our project website for more details: [SteerVLM Website](https://22anushka.github.io/emnlp-2025/)  

[📄**arxiv**](https://arxiv.org/pdf/2510.26769) | [**🎥 Video:**](https://drive.google.com/file/d/1_T4voPg_Xdye6rvJk8PZK3iX6I3cZYt_/view)  | [**📊 Poster:**](https://drive.google.com/file/d/1qOkktvyQ6kGOfI3wmRBtH12kDpv7I7Qt/view) | 

## 🧰 Repository Structure
```
SteerVLM/
├── external/           # pointer to LLaVA fork containing SteerVLM Code
  ├── LLaVA/
    ├── llava
      ├── serve
        ├── Steerer2_0 # SteerVLM code files!!
├── VNIA/              # Novel VNIA Multimodal Steering Dataset for training, validation, and evaluation
└── README.md
```

*Note*: The current structure is due to SteerVLM's integration with LLaVA. However, you can find the code in the [Steerer2_0](https://github.com/22anushka/LLaVA/tree/1bd636e0af4577a7c130ca9fbadbc50464987e56/llava/serve/Steerer2_0) folder and adapt it to any Vision Language Model since the core steering logic is orthogonal to existing architectures.

## 🔧 Installation

```bash
git clone https://github.com/yourusername/SteerVLM.git
cd SteerVLM
pip install -r requirements.txt
```

## 📚 Citation

If you use SteerVLM in your research, please cite our work:
```bibtex
@inproceedings{anushka2025steervlm,
  title={SteerVLM: Steering Vision-Language Models for Controlled Reasoning},
  author={Anushka et al.},
  booktitle={EMNLP},
  year={2025}
}
```
