# breast-cancer-detection

**Dataset**: [BreakHis Dataset](https://www.kaggle.com/datasets/ambarish/breakhis)

**Current accuracy**: 85.21%

### Possible improvements ###
- We can use transfer learning to increase accuracy (currently could not do it because it is computationally expensive).
- We can use data augmentation to make the model more robust (There are some bugs in TensorFlow while using Data Augmentation with image_dataset_from_directory and it is very slow as of now). [Bug](https://stackoverflow.com/questions/73304934/tensorflow-data-augmentation-gives-a-warning-using-a-while-loop-for-converting)
