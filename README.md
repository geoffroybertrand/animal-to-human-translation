## Animal-to-human translation | 💻 + 🐁 = ❤️
In the context of **Machine Learning** applied to **Genomics data** for improving **clinical trials**.

This repo is based on the survey paper:
[Machine Learning Applications for Therapeutic Tasks with Genomics Data](https://www.cell.com/patterns/pdf/S2666-3899(21)00176-8.pdf).
*Kexin Huang, Cao Xiao, Lucas M. Glass, Cathy W. Critchlow, Greg Gibson, Jimeng Sun* Published in Patterns.

It focuses on the **ML for Genomics in Clinical Study** part of the above paper.

**Theme 1:** Translating pre-clinical animal models to humans

**Task 1:** Cross-species genotype-phenotype translation   

**Task Description:** Given genotype-phenotype data of animals and only the genotype data of humans, train the model to fit phenotype from the genotype and transfer this model to human.


<p align="center">
<img src="images/animal_to_human_translation.png" width="400px">
</p>


## System requirements
- Operating System: Linux.
- 64-bit Python 3.7 installation.
- blastp: 2.6.0+
- TensorFlow 1.13.1 or newer with GPU support.
- One or more NVIDIA GPUs. Recomendation: NVIDIA at least P100 GPU with 16GB.
- NVIDIA driver 418.87 or newer, CUDA toolkit 10.1 or newer, cuDNN 7.6.2 or newer.

### Conda environment
environment.yml contains all the dependencies required in order to run ProteinGAN. You can simply run:
`conda env create --file environment.yml`

## Data for training

## Training networks

## Useful links

- Database of genome wide association studies - https://www.ebi.ac.uk/gwas/
- Database of annotated enzymes by its function - http://www.uniprot.org/. 
- Database of enzyme reactions: https://www.expasy.org/.
- Paper on generating DNA sequences using GANs - https://arxiv.org/pdf/1712.06148.pdf
- Paper on generating peptides: https://arxiv.org/pdf/1804.01694.pdf

Papers influenced final solution:
- An Empirical Evaluation of Generic Convolutional and Recurrent Networksfor Sequence Modeling: https://arxiv.org/pdf/1803.01271.pdf
- Large Scale GAN Training for High Fidelity Natural Image Synthesis: https://arxiv.org/pdf/1809.11096.pdf
- Progressive Growing of GANs for Improved Quality, Stability, and Variation: https://arxiv.org/pdf/1710.10196.pdf
- Spectral Normalization for Generative Adversarial Networks: https://arxiv.org/abs/1802.05957.pdf
- Improved Techniques for Training GANs: https://arxiv.org/pdf/1606.03498.pdf
- Spectral Normalization for Generative Adversarial Networks: https://arxiv.org/pdf/1802.05957.pdf
- Multi-Scale Context Aggregation by Dilated Convolutions: https://arxiv.org/pdf/1511.07122.pdf
- Self-Attention Generative Adversarial Networks: https://arxiv.org/pdf/1805.08318.pdf
- cGANs with Projection Discriminator: https://arxiv.org/pdf/1802.05637.pdf
- A Style-Based Generator Architecture for Generative Adversarial Networks: https://arxiv.org/pdf/1812.04948.pdf
- Which Training Methods for GANs do actually Converge? https://arxiv.org/pdf/1801.04406

