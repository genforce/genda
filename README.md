# GenDA - One-Shot Generative Domain Adaptation

![image](./docs/assets/teaser.png)

> **One-Shot Generative Domain Adaptation** <br>
> Ceyuan Yang*, Yujun Shen*, Zhiyi Zhang, Yinghao Xu, Jiapeng Zhu, Zhirong Wu, Bolei Zhou <br>
> *arXiv preprint*

[[Paper]()]
[[Project Page](https://genforce.github.io/genda/)]

This work aims at transferring a Generative Adversarial Network (GAN) pre-trained on one image domain to a new domain referring to as few as just one target image. Different from existing approaches that adopt the vanilla fine-tuning strategy, we import two lightweight modules called attribute adaptor and attribute classifier  to the generator and the discriminator respectively. By efficiently learning these two modules, we manage to reuse the prior knowledge and hence enable one-shot transfer with impressively high diversity.  Our method demonstrates substantial improvements over existing baselines in a wide range of settings.

## Qualitative results

Here we provide some synthesis after one-shot adaptation.
![image](./docs/assets/1shotadaptation.png)
![image](./docs/assets/outofdomain.png)

## BibTeX

```bibtex
@article{yang2021genda,
  title   = {One-Shot Generative Domain Adaptation},
  author  = {Yang, Ceyuan and Shen, Yujun and Zhang, Zhiyi and Xu, Yinghao and Zhu, Jiapeng and Wu, Zhirong and Zhou, Bolei},
  article = {arXiv preprint},
  year    = {2021}
}
```
