# Pytorch_PointCNN

## PointCNN Usage

* ### Classification
  * #### ModelNet40
  ```
  python3 dataset/download_datasets.py -f [path to data folder] -d modelnet
  CUDA_VISIBLE_DEVICES=[your available gpu] python3 run.py
  ```

* ### Notification
 The hyperparameters and performance are now align with the official tensorflow implementation.
