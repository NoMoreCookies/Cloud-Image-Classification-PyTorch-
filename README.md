# Cloud Image Classification (PyTorch)

Image classification project built in **PyTorch**, documented as a single Jupyter Notebook:
`sieci_splotowe_pytorch.ipynb`.

The notebook walks through the full pipeline:
**data loading → transformations → model → training → evaluation → inference on test images**.

---

##  What’s inside

- End-to-end training pipeline in a single notebook (easy to review)
- Data preprocessing / **torchvision transforms** (resize/normalize/augmentation — see notebook section “Transforms”)
- CNN model training in PyTorch
- Evaluation (accuracy + optional confusion matrix / sample predictions)
- Quick inference on images from `test_image/test`

> **Result:** ~`<YOUR_ACCURACY>%` accuracy on `<DATASET_NAME>` (details in the “Results” section of the notebook)

---

##  Repository structure

```text
.
├── sieci_splotowe_pytorch.ipynb   # main notebook (training + evaluation)
├── requirements.txt               # Python dependencies
├── images/                        # (optional) assets used in notebook/README
└── test_image/
    └── test/                      # sample images for quick inference
```

## Quickstart

```bash

python -m venv .venv

# Windows:
.venv\Scripts\activate

# macOS/Linux:
source .venv/bin/activate

pip install -r requirements.txt

```