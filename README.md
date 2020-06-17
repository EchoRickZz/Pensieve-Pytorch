This is a pytorch version of Pensieve (SiGCOMM'19)

Recommend Pytorch 1.5.0 (we don't test in other versions) and tenroboardX

All training data and Testing data have been prepared, and you can train the model just running


```
python multi_pytorch.py
```

The training process can be visualized by running

```
tensorboard --logdir=./results/
```

where the plot can be viewed at `localhost:6006` from a browser. 

Put up the issue if you have any questions.