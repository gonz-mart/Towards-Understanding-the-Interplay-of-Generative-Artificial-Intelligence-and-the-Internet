# Towards-Understanding-the-Interplay-of-Generative-Artificial-Intelligence-and-the-Internet

The present repository contains the code of the experiments of the paper:

[[2306.06130] Towards Understanding the Interplay of Generative Artificial Intelligence and the Internet (arxiv.org)](https://arxiv.org/abs/2306.06130)


Please cite:
```
@misc{martínez2023understanding,
      title={Towards Understanding the Interplay of Generative Artificial Intelligence and the Internet},
      author={Gonzalo Martínez and Lauren Watson and Pedro Reviriego and José Alberto Hernández and Marc Juarez and Rik Sarkar},
      year={2023},
      eprint={2306.06130},
      archivePrefix={arXiv},
      primaryClass={cs.AI}
}
```


# Use

The code is intended for use on the GoogleColab platform but has been adapted so that it can be used locally or in other scenarios. Each of the notebooks represents an experiment from the paper.

For use simply use the notebooks and the results will be saved under the Results_Experiments folder.

# Requirements

The libraries required by this repository are the following:

- numpy, matplotlib
- torch, torchvision
- tensorflow, tensorflow-addons
- tqdm

# Acknowledges

This repository has been built on top of the following two repositories:

- [clear-diffusion-keras](https://github.com/beresandras/clear-diffusion-keras)
- [Conditional_Diffusion_MNIST](https://github.com/felix-ky/Conditional_Diffusion_MNIST)

Without them the development of this repository and the experiments would have been impossible. Therefore, I would like to acknowledge and thank them for their excellent code.