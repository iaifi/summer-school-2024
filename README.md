# [2024 IAIFI Summer School](https://iaifi.org/phd-summer-school.html)

## 1. Deep generative models: A latent variable model perspective
(Author: Gilles Louppe)

Instructor: [Gilles Louppe](https://glouppe.github.io/)
Slides: [https://glouppe.github.io/iaifi-summer-school-2024/lecture/](https://glouppe.github.io/iaifi-summer-school-2024/lecture/)

### Useful materials

Lecture Notes:
* Gilles Louppe, [Deep Learning lecture notes](https://github.com/glouppe/info8010-deep-learning?tab=readme-ov-file#agenda), 2023-2024 (lectures 10, 11 and 12).
* Siddarth Mishra-Sharma, [Generative modeling, with connection to and applications in physics](https://smsharma.github.io/iaifi-summer-school-2023/), 2023.
* Karsten Kreis, Ruiqi Gao, Arash Vahdat, [Latent Diffusion Models: Is the Generative AI Revolution Happening in Latent Space?](https://neurips2023-ldm-tutorial.github.io/), 2023.

Books: 
* Jakub M. Tomczak, [Deep generative modeling](https://link.springer.com/book/10.1007/978-3-030-93158-2), 2022.
* Simon J.D. Prince, [Understanding deep learning](https://udlbook.github.io/udlbook/), 2023 (chapters 16, 17, 18).

Code: 
* Siddarth Mishra-Sharma, Minified generative models: A repository with minimal/pedagogical implementations of some generative models.

### Tutorial
(Author: Gaia Grosso)

Instructor: [Gaia Grosso](https://scholar.google.com/citations?user=hSk0b3oAAAAJ&hl=it)
Notebook 1: [Diffusion models for galaxy images generation](https://github.com/glouppe/iaifi-summer-school-2024/blob/master/tutorials/1-TUTORIAL-Diffusion-Galaxy-cosmos128.ipynb)
Notebook 2: [Variational auto-encoders for anomaly detection at the LHC](https://github.com/glouppe/iaifi-summer-school-2024/blob/master/tutorials/2-TUTORIAL-VAE-collider-data-torch.ipynb)
Notebook 3: [How good is your generative model?](https://github.com/glouppe/iaifi-summer-school-2024/blob/master/tutorials/3-TUTORIAL-Validation-generative-models.ipynb)

## 2. Geometric Machine Learning
(Author: Melanie Weber)

### Useful materials

### Tutorial
(Author: Thomas Harvey & Sokratis Trifinopoulos)

* Tutorial Materials
  
  *  The exercise notebooks can be found here: https://github.com/iaifi/summer-school-2024/tree/main/Geometric_NNs
* Reference papers and book chapters for tutorials:
  
  *   Equivariant machine learning structured like classical physics: https://arxiv.org/pdf/2106.06610

## 3. Scaling and renormalization in high-dimensional regression
(Author: Cengiz Pehlevan & Alex Atanasov)



### Useful materials


### Tutorial
(Author: Alex Atanasov)

* Tutorial Materials
  
  *   Plase see the folder: https://github.com/iaifi/summer-school-2024/tree/main/RMT_Scaling_Laws

### Reference papers and book chapters for tutorials

Key paper:
  *  Scaling and Renormalization in High Dimensional Regression https://arxiv.org/abs/2405.00592
  
 Related work:
  * Dynamical Model of Neural Scaling Laws: https://arxiv.org/abs/2402.01092
  * Spectral Bias and Task-Model Alignmeny Explain Generalization: https://arxiv.org/abs/2006.13198 

Recommended Books:
  * Potters and Bouchaud "A first course in Random Matrix Theory". Strongly recommended!


## 4. Uncertainty Quantification
(Author: Carol Cueta-Lazaro)
  
### Useful materials

  
### Tutorial
(Author: [Jessie Micallef](https://jessimic.github.io/tech-portfolio/))

* Tutorial Materials
  
  * Intro slides: https://github.com/jessimic/sbi-tutorial-iaifi/blob/main/assets/SBI_Tutorial_Intro.pdf
  * Tutorials: https://github.com/jessimic/sbi-tutorial-iaifi/tree/a8730f55642b7280c3c3bc1c33c8483af78f8305
      * Main branch has fill in code blanks
      * Answers branch has some solutions, including all solutions for Tutorial 1
* Reference papers and book chapters for tutorials
  * [The frontier of simulation-based inference](https://arxiv.org/abs/1911.01429) (Cranmer, Brehmer, Louppe): Review paper
  * [simulation-based-inference.org](http://simulation-based-inference.org/): List of papers and resources
  * [awesome-neural-sbi](https://github.com/smsharma/awesome-neural-sbi): List of papers and resources
  
    
## 5. Hackathon
At the end of the Hackathon on Friday, August 9, we will have a block for presentations of work done on these topics. Forming groups is strongly encouraged!

### Prompts
* Train a variational auto-encoder on calorimeter data and use it for anomaly detection and/or for super-resolution of astronomical images.
* Train a diffusion model on galaxy images and generate samples conditionally on noisy observations (e.g., corrupted by noise, missing pixels, etc).
* Train a normalizing flow for simulation-based inference on gravitational lenses (e.g., substructure properties in strong lensing systems).
* Apply simulation-based inference (SBI) to a new dataset (examples below). Can we use different ML methods for SBI outside of dense NNs and CNNs? Transformer? Other methods? 
  * Astronomy
  * Breast cancer histology
  * Drift tube chamber data
* Quantum reservoir computing: How does the QRC perform if we only collect 〈Zi〉 expectation values and drop 〈ZiZj〉 correlations? Why do you think this happens? How about adding connected 〈ZiZjZk〉 where {i, j, k} belong to a cluster of sites connected by the nearest neighbor bonds? Hint: Try to modify the readouts vector to exclude/include the correlations that are calculated. Based on this notebook: https://github.com/QuEraComputing/QRC-tutorials/blob/main/QRC%20Demo%20MNIST.ipynb
* Work on your own project! 

### Datasets
* Astro: [https://camels-multifield-dataset.readthedocs.io/en/latest/]([https://camels-multifield-dataset.readthedocs.io/en/latest/)
* IceCube dataset: [https://www.kaggle.com/competitions/icecube-neutrinos-in-deep-ice](https://www.kaggle.com/competitions/icecube-neutrinos-in-deep-ice)
* Breast cancer histology: [https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images](https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images)
* Drift tube chamber data: [https://zenodo.org/records/7128223](https://zenodo.org/records/7128223)
  * Associated paper about data quality monitoring for this dataset: [https://iopscience.iop.org/article/10.1088/2632-2153/acebb7/pdf](https://iopscience.iop.org/article/10.1088/2632-2153/acebb7/pdf)
* Calorimeter data (Calo challenge): [https://github.com/CaloChallenge/homepage](https://github.com/CaloChallenge/homepage)
* Gravitational lens dataset: [https://lweb.cfa.harvard.edu/castles/noimages.html](https://lweb.cfa.harvard.edu/castles/noimages.html)
* Galaxies (COSMOS real galaxies dataset): [https://zenodo.org/records/3242143](https://zenodo.org/records/3242143)
 
### Prize Categories
* Best project (effort, presentation, use of summer school topics): 1st, 2nd, and 3rd place
* Best visualization
* Best team effort

## NSF ACCESS Instructions

[https://github.com/alexandergagliano/summer-school-2024/tree/main/computing](https://github.com/alexandergagliano/summer-school-2024/tree/main/computing)
