<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1f2e,100:00b4d8&height=200&section=header&text=Santhosh%20Kumar%20R%20R&fontSize=50&fontColor=ffffff&fontAlignY=38&desc=AI%20%7C%20Computer%20Vision%20%7C%20Deep%20Learning&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00B4D8&center=true&vCenter=true&width=600&lines=B.Tech+CSE+%40+SASTRA+University;Computer+Vision+Researcher;IEEE+%26+Springer+Publications;Building+AI+for+the+Real+World+🌍)](https://git.io/typing-svg)

<p>
  <a href="https://www.linkedin.com/in/santhosh-kumar-64a203335">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:santhosh23200605@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.kaggle.com/santhoshkumarrr">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/Santhosh_Kumar_R_R">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
</p>

<img src="https://komarev.com/ghpvc/?username=santhoshkumarrr&label=Profile%20Views&color=00b4d8&style=flat-square" />

</div>

---

## 🧠 About Me

```python
class SanthoshKumar:
    def __init__(self):
        self.name        = "Santhosh Kumar R R"
        self.degree      = "B.Tech CSE (3rd Year) @ SASTRA Deemed University"
        self.research    = ["Computer Vision", "Deep Learning", "Agentic AI"]
        self.stack       = ["PyTorch", "YOLOv8", "Faster R-CNN", "SegFormer",
                            "FAISS", "FastAPI", "Streamlit", "Phi-3"]
        self.publications = 2   # IEEE ISED 2025 + ICRAI 2025 (Springer)
        self.goal        = "AI/ML Engineer — CV + Intelligent Systems"

    def current_focus(self):
        return ["LLMs", "RAG Pipelines", "MLOps", "Agentic AI"]
```

---

## 📄 Publications

<table>
  <tr>
    <th>#</th>
    <th>Title</th>
    <th>Venue</th>
    <th>Method</th>
    <th>Key Result</th>
    <th>Status</th>
  </tr>
  <tr>
    <td>1</td>
    <td><b>Enhanced Wild Animal Intrusion Detection using Faster R-CNN with Debiasing Technique</b></td>
    <td>IEEE ISED 2025 — NIT Raipur</td>
    <td>Faster R-CNN + ResNet-50 + FPN</td>
    <td>mAP 0.797 · IoU 98.12% · F1 0.824</td>
    <td>✅ Published</td>
  </tr>
  <tr>
    <td>2</td>
    <td><b>Computer Vision-based Recognition of Queen Bees in Colonies Using Faster R-CNN</b></td>
    <td>ICRAI 2025 — Springer</td>
    <td>Faster R-CNN + ResNet-50</td>
    <td>Precision 89% · Recall 81% · F1 0.87</td>
    <td>✅ Accepted</td>
  </tr>
</table>

---

## 🚀 Featured Projects

<details>
<summary><b>🐟 MarineRAG-LLM — Underwater Fish Detection + RAG System</b></summary>
<br>

> End-to-end pipeline combining real-time YOLOv8 fish detection with an LLM-powered Q&A system for marine biodiversity intelligence.

| Component | Details |
|---|---|
| **Detection** | YOLOv8 — 362 fish families, FishNet dataset, mAP@0.50 ≈ 0.802 |
| **Embeddings** | SentenceTransformer + FAISS IndexFlatIP |
| **LLM** | Phi-3 via Ollama |
| **Serving** | FastAPI + Streamlit |
| **Training** | Multi-session Kaggle T4, checkpoint resumption, AMP-off for FP16 stability |

</details>

<details>
<summary><b>🐝 Computer Vision-based Recognition of Queen Bees in Colonies — ICRAI 2025 (Springer)</b></summary>
<br>

> Automated queen bee detection in natural hive imagery using Faster R-CNN, addressing the challenge of locating a single queen among dense worker bee clusters.

| Component | Details |
|---|---|
| **Model** | Faster R-CNN + ResNet-50 backbone + FPN |
| **Dataset** | Real-time hive images/video frames; annotated via Roboflow (label: `Qbee`) |
| **Augmentation** | Horizontal flip, saturation shift (±25%), 90° rotation |
| **Training** | 25 epochs, SGD optimizer, decaying LR schedule, GPU-accelerated |
| **Precision** | 89% · Recall 81% · F1 0.87 · Avg IoU 0.89 |
| **vs. YOLO** | Outperformed YOLOv5 (F1 0.80), YOLOv8 (F1 0.77), YOLOv11 (F1 0.84) |
| **Deployment** | Android Progressive Web App via Gradio + `fasterrcnn_epoch8.pth` |

</details>

<details>
<summary><b>🐘 Enhanced Wild Animal Intrusion Detection using Faster R-CNN — IEEE ISED 2025</b></summary>
<br>

> Day-night adaptive animal trespass detection system for agricultural and residential perimeter security, using a debiased dataset and two-stage Faster R-CNN architecture.

| Component | Details |
|---|---|
| **Model** | Faster R-CNN + ResNet-50 + FPN (two-stage detector) |
| **Dataset** | 13-class custom day + night dataset; debiased via Albumentations |
| **Debiasing** | Horizontal flip, random brightness/contrast, rotation, Gaussian noise |
| **Hardware** | Intel Core i5-10300H · 16GB RAM · NVIDIA GTX 1650 |
| **mAP** | 0.797 · Avg IoU 98.12% · Precision 79.7% · Recall 86.2% · F1 0.824 |
| **vs. YOLO** | Surpassed YOLOv5 (mAP 0.641), YOLOv7, YOLOv8 (mAP 0.640) on same dataset |
| **Key Feature** | Dual day-night training enables adaptation to varying illumination without retraining |

</details>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**ML / CV Frameworks**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Infrastructure & Tools**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-00B4D8?style=for-the-badge&logo=meta&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=santhosh-kumar2305&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=santhosh-kumar2305&layout=compact&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=santhosh-kumar2305&theme=tokyonight&hide_border=true" />
</div>

---

## 📈 Activity Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=santhosh-kumar2305&theme=tokyo-night&hide_border=true&area=true" width="95%"/>
</div>

---

## 🎯 Currently Learning

```
📦 LLMs & Prompt Engineering    ████████████░░░░   75%
🔍 RAG & Vector Databases       ██████████░░░░░░   63%
⚙️  MLOps & Model Deployment    ████████░░░░░░░░   50%
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,100:0d1117&height=120&section=footer&text=Let's%20Build%20Something%20Meaningful&fontSize=20&fontColor=ffffff&fontAlignY=65&animation=fadeIn" width="100%"/>

</div>
