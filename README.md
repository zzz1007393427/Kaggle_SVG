# Kaggle_SVG
LoRA fine-tuning for SVG generation (DL Spring 2026)

## Dataset:
The dataset (train.csv and test.csv) is from the Kaggle competition.
Please download it and place it in the project root directory.

## Training:
1.Run final_training.ipynb to train the LoRA model.
2.The trained weights will be saved locally.

## Inference:
1.Run final_inference.ipynb to generate predictions.
2.Make sure to update the path:

```python
LORA_PATH = "./your_model_path"
