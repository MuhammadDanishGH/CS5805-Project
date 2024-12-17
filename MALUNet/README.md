# Using Code

**0. Main Environments**
- python 3.8
- pytorch 1.8.0
- torchvision 0.9.0

**1. Prepare the dataset.**

- After downloading the datasets, you are supposed to put them into './data/isic18/', and the file format reference is as follows:

- './data/isic18/'
  - train
    - images
      - .png
    - masks
      - .png
  - val
    - images
      - .png
    - masks
      - .png

**2. Train the MALUNet.**
```
cd MALUNet
```
```
python train.py
```

**3. Obtain the outputs.**
- After trianing, you could obtain the outputs in './results/'
