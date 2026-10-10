# Liver and Tumour Segmentation

A medical imaging deep learning project using the Liver Tumor Segmentation (LiTS) datasets.

## Objectives

- Explore and validate CT volumes and segmentation masks.
- Build a reproducible medical image preprocessing pipeline.
- Develop liver and liver tumour segmentation models.
- Evaluate model performance using metrics such as Dice score and Hausdorff distance.

## Datasets

- [LiTS – Part 1](https://www.kaggle.com/datasets/andrewmvd/liver-tumor-segmentation)
- [LiTS – Part 2](https://www.kaggle.com/datasets/andrewmvd/liver-tumor-segmentation-part-2)

Dataset files are stored locally and are not included in this repository.

## Technologies

- Python
- PyTorch
- MONAI
- SimpleITK
- Jupyter Notebook

## Project Structure

```text
seg_00/
├── notebooks/
├── src/
├── tests/
├── data/
├── .gitignore
├── README.md
└── requirements.txt
```

## Environment Setup

Create and activate a Python environment, then install the dependencies:

```bash
python -m pip install -r requirements.txt
```

## Status

Initial environment and repository setup.
