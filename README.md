# medical-marijuana

Train a Convolutional Neural Network (CNN) using Keras to automatically classify root health without having to physically touch the plants.

roots needed to be classified into two groups:
“Hairy” roots
“Non-hairy” roots


![Dataset Sample](?https://github.com/walae-br/medical-marijuana/blob/main/images/mm_dataset.png?raw=true)


The dataset of 1,524 root images includes:

Hairy: 748 images (left)
Non-hairy: 776 images (right)


##### Project structure

```
├── dataset
│   ├── hairy_root [748 images]
│   └── non_hairy_root [776 images]
├── pipeline
│   ├── __init__.py
│   └── simplenet.py
├── train_model.py
└── plot.png
```

Clone the repository:
```
git clone git@github.com:walae-br/medical-marijuana.git
```

Go ahead and train SimpleNet on our hydroponics, and medical marijuana dataset.

```
python train_model.py
```

The network obtained 95% classification accuracy, and as the plot demonstrates, there is no overfitting.

![Fig1]("")
