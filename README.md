# reu-code

A repository of all of the code I wrote during my summer 2021 TRIPODS REU at University of Massachusetts Amherst.

I mainly focused on equivariant neural networks in deep learning. Essentially a form of convolution that can
respect inherent properties in image recognition to reduce needed parameters/increase preformance on datasets.

Specifically, I worked to train and explore a model described in this paper [\[Cohen & Welling, 2016\]](#gcnn)
for group equivariant networks. Essentially, a network with convolutions that "sees" all rotations and mirrors
of its input image equivalently. I successfully reproduced the results from the paper on my own machine using
the MNIST dataset and others. Check out [\[p4m-gconv\]](https://github.com/jack-champagne/p4m-conv) for more
details.

## References
1. <a name="gcnn"></a> T.S. Cohen, M. Welling, [Group Equivariant Convolutional Networks](http://www.jmlr.org/proceedings/papers/v48/cohenc16.pdf). Proceedings of the International Conference on Machine Learning (ICML), 2016.