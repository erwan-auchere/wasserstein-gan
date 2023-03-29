# Does Wasserstein-GAN approximate Wasserstein distances?

The [Wasserstein-GAN](https://arxiv.org/abs/1701.07875) paper proposes a proxy for the 1-Wasserstein distance that uses neural networks. While that proxy seems to work for the task of training GANs, it is not well understood whether that approach can approximate, numerically, the Wasserstein distance. In this project, we implement the Wasserstein-GAN approach to solve optimal transport problems and benchmark it against other approaches.
