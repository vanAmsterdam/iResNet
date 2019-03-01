# iResNet - invertible residual network

Attempt at implementing iResNet, from Behrmann 2019

## todo

[x] use ELU instead of ReLU (now argument of block-generator)
[x] implement spectral norm regularization according to equation 3
[ ] get fast Jacobian (torch.autograd for all output values?)
[ ] truncated power series for estimating det(J)


##

To get started with spectral norm, forked from:

Based on the paper "Spectral Normalization for Generative Adversarial Networks" by Takeru Miyato, Toshiki Kataoka, Masanori Koyama, Yuichi Yoshida
ICLR 2018 preprint:
https://openreview.net/forum?id=B1QRgziT-
