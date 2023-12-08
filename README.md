Using @karpathy's nanoGPT to reproduce a bug.

Steps to reproduce (on my machine):

```
cd data/shakespeare_char
python prepare.py
cd ../..
python train.py
```

This should produce a `bug.pickle` that will fail to visualize on `https://pytorch.org/memory_viz`.
