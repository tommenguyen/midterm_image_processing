# Project description
A prediction model for Sino-nom character recognition using Residual Learning
# Repository structure
- sinonom_resnet.ipynb: Contains pipeline for the our model including: minor preprocessing, dataset loading, model defining and compiling, training, testing, update log to external source(ggsheet). The notebook is carefully commented for modification purposes.
# Information of contributors
- Hoàng Mạnh Bình - 20021305
- Nguyễn Tiến Đạt - 20021327
- Nguyễn Minh Phong - 21021526
- Trần Trọng Quân - 21020529
# Instructions
Our approach utilizes TensorFlow for modeling our project. However, TensorFlow has discontinued support for native Windows in its newer versions. Therefore, for the best experience and performance, we recommend using GPU cloud platforms such as Kaggle or Google Colab.
## Kaggle public notebook
https://www.kaggle.com/code/tommenguyen/sinonom-resnet
## Dataset
- Make sure to download the dataset and configure correct path in the notebook under *Dataset path*
```python
train_directory = '/kaggle/input/wb-recognition-dataset-plus/wb_recognition_dataset/wb_recognition_dataset/train'
```

## Using GPU cloud platforms
- Make sure dataset loader is configured correctly
- Parameter Configuration in the notebook (optional)
- Run all the cells 
## Using local machine (CUDA GPUs required)
- Installing required packages
```console
pip install -r requirements.txt
```
- Run all the cells
# Results 
Our Top-1 Accuracy model reach at 83.5%.
# Link to full report (updating)
URL: 
