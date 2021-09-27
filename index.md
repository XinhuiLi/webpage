---
layout: default
---

# About Me

I am a first-year Ph.D. student in the School of Electrical and Computer Engineering/Bioengineering at the Georgia Institute of Technology, advised by Dr. [Vince D. Calhoun](https://scholar.google.com/citations?user=WNOoGKIAAAAJ&hl=en). My research interests focus on multi-modal neuroimaging, deep learning and brain-computer interface. I hope to improve the interpretability and generalizability of deep learning algorithms for clinical applications and better understand mental disorders.

![CV](/assets/img/icons8-resume.png =20x) [CV](/assets/cv/XinhuiLi-CV-09-21.pdf)
![Scholar](/assets/img/icons8-google-scholar.png =20x) [Google Scholar](https://scholar.google.com/citations?user=YKtWorEAAAAJ&hl=en)
![GitHub](/assets/img/icons8-github.png =20x) [GitHub](https://github.com/XinhuiLi)
![Twitter](/assets/img/icons8-twitter.png =20x) [Twitter](https://twitter.com/xin_hui_li)
![LinkedIn](/assets/img/icons8-linkedin.png =20x) [LinkedIn](https://www.linkedin.com/in/xinhui-li/)

# Software Development

### C-PAC

Before I started my Ph.D., I worked as a research engineer at the Computational Neuroimaging Lab of [Child Mind Institute](https://childmind.org/). I developed a software toolbox [Configurable Pipeline for the Analysis of Connectomes (C-PAC)](https://fcp-indi.github.io/) for MRI processing, including its pipeline configuration [GUI](https://github.com/FCP-INDI/C-PAC_GUI) and [user documentation](https://github.com/FCP-INDI/fcp-indi.github.com).


# Research Highlights

### Cross-Pipeline Reproducibility

As part of C-PAC development, we evaluated preprocessing methods across different fMRI pipelines, including [fMRIPrep](https://fmriprep.org/en/stable/), [XCP](https://xcpengine.readthedocs.io/), [ABCD](https://github.com/DCAN-Labs/DCAN-HCP/tree/master) and [CCS](https://github.com/zuoxinian/CCS), and expanded C-PAC configuration options to enhance cross-pipeline reproducibility. Check out our [OHBM 2021 poster](/assets/poster/OHBM21_XL.pdf) and [OHBM 2020 poster](/assets/poster/OHBM20_XL.pdf). We have a cool paper in preparation, stay tuned!

### NHP U-Net Tissue Segmention/Brain Extraction

I am developing a deep learning model U-Net to segment tissues for non-human primate (NHP) MRI data. Take a look at our [NIBS 2021 poster](/assets/poster/NIBS21_XL.pdf). I also contributed to the [NHP U-Net brain extraction](https://github.com/HumanBrainED/NHP-BrainExtraction) project ([Wang et al., 2021](https://www.sciencedirect.com/science/article/pii/S1053811921002780)).

### Deep Learning for Visual Science

From 2018 to 2019, I worked as a research assistant at [the Hood Visual Science Lab](https://hoodvisualscience.psychology.columbia.edu/), Columbia University. I applied deep learning models to detect glaucoma and evaluated model transferability ([Thakoor et al., 2019](https://doi.org/10.1109/EMBC.2019.8856899); [Li et al., 2020](https://iovs.arvojournals.org/article.aspx?articleid=2769404)). We proposed multiple strategies to enhance model generalizability across different datasets and evaluated the impact of reference standards ([Thakoor et al., 2021](https://tvst.arvojournals.org/article.aspx?articleid=2772481)). In addition, we designed a MATLAB-based deep learning toolbox [Ollie](https://github.com/XinhuiLi/Ollie) to identify glaucoma and won the first prize at Columbia Hackathon.

# Publications

Wang, X., **Li, X.,** Cho, J. W., Russ, B., Rajamani, N., Omelchenko, A., Ai, L., Korchmaros, A., Garcia, P., Wang, Z., Kalin, N. H., Schroeder, C. E., Craddock, C., Fox, A. S., Evans, A., Messinger, A., Milham, M. P., & Xu, T. (2021). **U-net model for brain extraction: Trained on humans for transfer to non-human primates.** NeuroImage. [[paper](https://www.sciencedirect.com/science/article/pii/S1053811921002780)]

Thakoor, K. A., **Li, X.,** Tsamis, E., Zemborain, Z. Z., Moraes, C. G. D., Sajda, P., & Hood, D. C. (2021). **Strategies to Improve Convolutional Neural Network Generalizability for Glaucoma Detection from OCT Scans.** Translational Vision Science and Technology. [[paper](https://tvst.arvojournals.org/article.aspx?articleid=2772481)]

Thakoor, K. A., **Li, X.,** Tsamis, E., Sajda, P., & Hood, D. C. (2019). **Enhancing the Accuracy of Glaucoma Detection from OCT Probability Maps using Convolutional Neural Networks.** 2019 41st Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC), 2036–2040. https://doi.org/10.1109/EMBC.2019.8856899 [[paper](https://doi.org/10.1109/EMBC.2019.8856899)]


# Selected Presentation/Posters

**Li, X.,** Ai, L., Giavasis, S., Jin, H., Franco, A. R., Feczko, E., Vogelstein, J. T., Craddock, R. C., Xu, T., Esteban, O., Poldrack, R. A., Fair, D., Satterthwaite, T., Milham, M. P. (2021). **Putting Pipeline Implementation-related Variation into Perspective for Functional Connectomics.** 2021 Organization for Human Brain Mapping 2021 Annual Meeting. [[poster](/assets/poster/OHBM21_XL.pdf)]

**Li, X.,** Giavasis, S., Jin, H., Ai, L., Sólon, A., Adebimpe, A., Franco, A. R., Poldrack, R. A., Vogelstein, J. T., Xu, T., Satterthwaite, T., Craddock, R. C., & Milham, M. P. (2020). **Evaluating and Improving Cross-Pipeline Reproducibility in Functional Connectomics: A Case Study.** 2020 Organization for Human Brain Mapping Annual Meeting. [[poster](/assets/poster/OHBM20_XL.pdf)]

**Li, X.,** Wang, X., Mantell, K., Casillo, E. C., Milham, M. P., Opitz, A., & Xu, T. (2021). **Toward Automatic Segmentation for Non-human Primates.** 2nd International Workshop on Non-invasive Brain Stimulation (NIBS). [[poster](/assets/poster/NIBS21_XL.pdf)]

**Li, X.,** Tsamis, E., Thakoor, K. A., Zemborain, Z., Moraes, C. G. D., & Hood, D. C. (2020). **Evaluating the transferability of deep learning models that distinguish glaucomatous from non-glaucomatous OCT circumpapillary disc scans.** Investigative Ophthalmology & Visual Science, 61(7), 4548–4548. [[abstract](https://iovs.arvojournals.org/article.aspx?articleid=2769404)]

**Li, X.**, & Jin, H. fMRI Preprocessing with Containers: How to run C-PAC with Docker and Singularity. Brainhack Global, New York, November 2019. [[oral presentation](/assets/presentation/brainhack19.pdf)]