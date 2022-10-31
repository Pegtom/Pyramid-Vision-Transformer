# Pyramid Vision Transformer
here's the official implementation for PViT [link](https://github.com/whai362/PVT/tree/f09200f52108651c441a928df1e3dbba2278ff37/classification)

The author did not provide a straightforward solution for finetuning the trained model for classification, so I cooked up this notebook that can work with any dataset. I used cat-and-dog dataset from Kaggle.
# training a dataset in PViT
I changed cat-and-dog dataset structure for finetuning the model (PVT-Tiny method) a little bit.
# Finetuning
I used `gdown` to download the pre-trained model, after training the model for 10 epochs, the accuracy reached 99%
