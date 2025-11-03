# Car Image Segmentation

Semantic segmentation model to isolate cars from background images using PyTorch.

## 🚗 Example Output

| Input | Segmentation Mask | Output |
|------|------------------|--------|
| ![input](docs/examples/car.jpg) | ![mask](docs/examples/mask.png) | ![output](docs/examples/output.png) |

> *(Replace these images with real examples from your project)*

## ✨ Features
- Binary car/background segmentation
- PyTorch training pipeline (CUDA + Apple M-series support)
- FiftyOne dataset explorer for data visualization & curation
- Efficient Parquet-based dataset workflow
- Training, inference, and preprocessing utilities included

## ⚡ Quickstart

```bash
# Clone repo
git clone <repo-url>
cd car-segmentation   # or your repo folder name

# Create environment
uv venv --python 3.11
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# Install packages
uv pip install -r requirements.txt

# Train model
python src/training/train.py

