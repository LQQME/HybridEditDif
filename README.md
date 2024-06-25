# Coming Soon to Open Source: HybridEditDif
# HybridEditDif: Text and Exemplar Guided Object Inpainting with Diffusion Models
![Image description](https://github.com/LQQME/Figure/blob/main/figure/HybridEditDif/git1.png)

 
## OverView
The goal of image editing technology is to accurately restore missing regions in images, ensuring Image editing technology aims to accurately restore missing regions while maintaining visual consistency and aesthetic appeal. However, text-guided methods struggle with semantic inconsistencies between local content and global descriptions, causing disharmonious effects. Exemplar-guided tasks lose the advantage of shared text embeddings.
We propose the HybridEditDif model, which uses the Dynamic Decoupled Cross-Attention mechanism to integrate text and exemplar conditions for image restoration. Self-supervised training reduces manual annotation needs, ensuring data consistency and diversity. Reference image and mask shape augmentation further enhance performance.
By adjusting two parameters ($\lambda_1$ and $\lambda_2$), our model flexibly supports editing using either text or exemplars independently.

![Image description](https://github.com/LQQME/Figure/blob/main/figure/HybridEditDif/overnew.png)


## Requirements

A suitable conda environment named HybridEditDif can be created and activated with:
```bash
conda env create -f environment.yaml
conda activate HybridEditDif
```


## Reuslts
![Image description](https://github.com/LQQME/Figure/blob/main/figure/HybridEditDif/vis-duibi.png)



## Visualization of inputs and output:
![Image description](https://github.com/LQQME/Figure/blob/main/figure/HybridEditDif/vis4.png)

