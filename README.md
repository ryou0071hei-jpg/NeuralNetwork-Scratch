# Neural Network from Scratch

NumPyのみを用いて実装した3層ニューラルネットワークです。

MNIST手書き数字データセットを用いて分類を行い、ニューラルネットワークの学習アルゴリズムをスクラッチ実装しました。

## Features

* NumPyのみで実装
* Forward Propagation
* Backpropagation
* Gradient Descent
* Softmax
* Cross Entropy Loss

## Experiments

以下のハイパーパラメータについて比較実験を行いました。

* Activation Function (ReLU / Sigmoid)
* Learning Rate (0.001 / 0.01 / 0.1)
* Epoch (10 / 50 / 100 / 200)
* Hidden Layer Size (32 / 64 / 128 / 256)
* Weight Initialization (0.01 / 0.05 / 0.10 / 0.25)

## Directory Structure

```
src/
    main.py
    model.py
    dataset.py

report/
    report.pdf
    report.tex
    eee.sty
    jlisting.sty

results/
    *.png
```

## Report

詳細な実験内容は `report/report.pdf` を参照してください。
