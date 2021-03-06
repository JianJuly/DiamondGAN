# DiamondGAN: Unified Multi-Modal Adversarial Networks for MRI Sequences Synthesis
### Q. 1: what are the applications that *DiamondGAN* can be used for? 
Answer: With the projects with our colaborators in TUM hosipital, we used *DiamondGAN* for synthesizing missing modalities for MS and glioma patients. As mentioned in the  [miccai paper](https://arxiv.org/abs/1904.12894), the double inversion recovery (DIR) can be synthesized/well-reconstructed using FLAIR, T1 and T2. 
### Q. 2: Does *DiamondGAN* promise to genereate expected pathological information such as the texture of lesion or tumor? 
Answer: you can combine as much information as possible from multiple sources. The hypothesis behind **DiamondGAN** is that the information of a target modality is distributed among other input modalities. Please see our experiment about the reconstruction of T1 constrast which requires a paramagnetic contrast agent. We somewhat failed to synthesize T1 contrast modality.
