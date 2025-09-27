# 🛠️ Tunnel Lining Multi-Category Defect Segmentation Detection

<h3>📌 Introduction</h3>

This repository is the open-source implementation of the research paper  
**"The hybrid segmentation method and application of KNet-UperNet-SwinL in multi-category defect segmentation detection of tunnel lining"**, including:

- 📂 **Large-scale tunnel lining defect image dataset** (multi-class annotations for cracks, leakage, etc.)
- 🤖 **Deep learning segmentation models** (8 representative semantic segmentation models + improved KNet model)
- 💻 **Desktop application for tunnel defect detection** (PyQt GUI, batch detection, visualization, and result export)

<p align="center"> <img src="image/1.png" height="250px"/>
 <img src="image/2.png" height="200px"/>
 <img src="image/3.png" height="170px"/>
 <img src="image/4.png" height="170px"/>
</p>

## 📑 Features

✅ **Multi-category defect annotations** – cracks, leakage, no-defect, suitable for real engineering scenarios  
✅ **Multiple model benchmarks** – trained weights for DeeplabV3+, PSPNet, SegFormer, UNet, Fast-SCNN, Mask2Former, etc.  
✅ **ONNX model conversion supported** – portable and hardware-accelerated inference  
✅ **User-friendly desktop program** – no deep learning knowledge required, easy-to-use GUI for field engineers

---

## 📂 File Directory Description

```bash
filetree
├── algorithm_model
│   ├── deeplabv3
│   ├── deeplabv3plus
│   ├── fast-scnn
│   ├── knet
│   ├── pspnet
│   ├── segformer
│   ├── unet
│   ├── mask2former
├── dataset
│   ├── crack
│   ├── leakage
│   ├── defects
│   ├── no_defects
├── Tunnel defects detect
│   ├── config
│   ├── model
│   ├── UI
│   ├── work
│   ├── work
├── README.md
```

## 👤 Author

**Jingqi Cui**
