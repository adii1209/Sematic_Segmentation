# Semantic Segmentation using Deep Learning

Implementation and comparison of MobileNet, U-Net, and DeepLabV3 architectures for image semantic segmentation using PyTorch.

---

## Installation

Follow the steps below to get a copy of the project running on your local machine.

### Prerequisites

Ensure you have the following installed before proceeding:

- **Python 3.8+** — [Download here](https://www.python.org/downloads/)
- **pip** — Comes bundled with Python
- **Jupyter Notebook** — For running the `.ipynb` files

Install Jupyter if you don't have it:

```bash
pip install notebook
```

### Steps

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install the required dependencies:

```bash
pip install torch torchvision
pip install segmentation-models-pytorch
pip install albumentations opencv-python matplotlib seaborn scikit-learn
```

---

## Usage

Launch Jupyter Notebook and open the model of your choice:

```bash
jupyter notebook
```

Then open and run any of the following notebooks:

```bash
Mobilenet.ipynb     # MobileNet-based segmentation
Unet.ipynb          # U-Net segmentation
Deeplabv3.ipynb     # DeepLabV3 segmentation
```

Each notebook covers data loading, model training, evaluation metrics, and prediction visualisation in a step-by-step format.

---

## Deploy

To deploy a trained model for inference on new images or video streams:

- **ONNX Export** — Convert the trained PyTorch model to ONNX format for cross-platform deployment
- **TorchScript** — Serialize the model for production use without a Python dependency
- **Edge Deployment** — Use tools such as TensorRT or OpenVINO for deployment on devices like NVIDIA Jetson Nano
- **Web API** — Wrap the model in a Flask or FastAPI server to serve predictions via REST endpoints

---

## Technologies

- **PyTorch** — Primary deep learning framework
- **segmentation-models-pytorch** — Pre-built segmentation model architectures
- **Albumentations** — Fast and flexible data augmentation library
- **OpenCV** — Image loading and preprocessing
- **Scikit-learn** — Evaluation metrics (F1, Kappa, etc.)
- **Matplotlib & Seaborn** — Result visualisation and heatmaps
- **NumPy** — Numerical operations

---

## Contributing

Contributions are welcome. To contribute:

1. Fork the repository
2. Create a new branch for your feature or fix:
```bash
git checkout -b feature/your-feature-name
```
3. Commit your changes with a clear message:
```bash
git commit -m "Add: description of your change"
```
4. Push to your fork and open a Pull Request:
```bash
git push origin feature/your-feature-name
```
5. Your Pull Request will be reviewed and merged if it aligns with the project goals

Please ensure your code is well-commented and follows existing notebook conventions.

---

## Documentation

- [PyTorch Documentation](https://pytorch.org/docs/)
- [segmentation-models-pytorch Docs](https://smp.readthedocs.io/en/latest/)
- [Albumentations Docs](https://albumentations.ai/docs/)
- [U-Net Original Paper](https://arxiv.org/abs/1505.04597)
- [DeepLabV3 Original Paper](https://arxiv.org/abs/1706.05587)

---

## Acknowledgments

- [Olaf Ronneberger et al.](https://arxiv.org/abs/1505.04597) — Original U-Net architecture
- [Liang-Chieh Chen et al.](https://arxiv.org/abs/1706.05587) — DeepLabV3 architecture
- [Pavel Iakubovskii](https://github.com/qubvel/segmentation_models.pytorch) — segmentation-models-pytorch library
- [Albumentations Team](https://github.com/albumentations-team/albumentations) — Data augmentation framework

---

## License

This project is licensed under the MIT License.

```
MIT License

Copyright (c) 2025 Adithya Shankar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
