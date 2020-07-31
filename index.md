---
layout: default
---

I am an assistant research engineer at [Child Mind Institute](https://childmind.org/). My research interests focus on fMRI/EEG analysis, brain computer interaction, deep learning, and artificial general intelligence.

[[Google Scholar](https://scholar.google.com/citations?user=YKtWorEAAAAJ&hl=en)] 
[[GitHub](https://github.com/SucyLi)]
[[Twitter](https://twitter.com/xin_hui_li)]
[[CV](/assets/cv/XinhuiLi-CV.pdf)]

# Software Development

### C-PAC

At the Computational Imaging Lab of Child Mind Institute, I am developing the software [Configurable Pipeline for the Analysis of Connectomes (C-PAC)](https://fcp-indi.github.io/), including its pipeline configuration [GUI](https://github.com/FCP-INDI/C-PAC_GUI) and [user documentation](https://github.com/FCP-INDI/fcp-indi.github.com).


# Research

### Cross-Pipeline Reproducibility

As part of C-PAC development, we evaluated preprocessing methods across different packages, including [fMRIPrep](https://fmriprep.org/en/stable/) and [XCP](https://xcpengine.readthedocs.io/), and expanded C-PAC configuration options to enhance cross-pipeline reproducibility. Check out our [poster](/assets/poster/OHBM20_XL.pdf) at OHBM2020.

### Monkey Brain Extraction/Tissue Segmention using U-Net

Supervised by [Ting Xu](https://scholar.google.com/citations?hl=en&user=Ks7ywnAAAAAJ&view_op=list_works&sortby=pubdate) at Child Mind Institute, I am developing a deep learning model U-Net to segment tissues with macaque structure MRI data. Besides, I also contributed to [the PRIME-DE brain extraction project](https://github.com/TingsterX/PRIME-DE/tree/master/BrainExtraction).

### Connectivity-based Shared Response Model

Supervised by Ting Xu, I am exploring shared response model for behavior and movie prediction using functional connectivity data.

### Deep Learning in Visual Science

I worked as a research assistant at [the Hood Visual Science Lab](https://hoodvisualscience.psychology.columbia.edu/) of Columbia University, where I applied deep learning models to detect glaucoma and achieved decent performance. Furthermore, we proposed multiple strategies to enhance model generalizability across different datasets and evaluated the impacts of reference standards. In addition, we designed a MATLAB-based deep learning toolbox [Ollie](https://github.com/SucyLi/Ollie) to identify glaucoma, which won the first prize at COLUMBIA HACKATHON 2019.

### Real-time EEG Classification

Collaborating with [Xiaofu He](https://scholar.google.com/citations?hl=en&user=QJnxJFIAAAAJ&view_op=list_works&sortby=pubdate) at New York State Psychiatry Institute, we tried to develop a real-time EEG feedback system where participants can receive prompt feedback classified by neural networks while performing tasks during EEG recording. We have made progress on designing a promising deep learning model - [a cascade Convolutional Neural Network – Recurrent Neural Network (CNN-RNN)](/assets/poster/NYSDS19_YF.pdf). My MCIT classmates and I built a [simulation system](https://github.com/SucyLi/Neural-Feedback-System) as a class project, which can serve as the front end for this system.


# Publications

**Moving Functional MRI Beyond Pipeline-Related Variation in Preprocessing.** (paper in preparation)

**Strategies to Improve Convolutional Neural Network Generalizability for Glaucoma Detection from OCT Scans.** (paper in preparation)

**Li, X.,** Cho, J. W., Milham, M. P. & Xu, T. (2020). **Improving brain-behavior prediction using individual-specific components from connectivity-based shared response model.** Resting-State Brain Connectivity Conference 2020. (abstract in review)

**Li, X.,** Giavasis, S., Jin, H., Ai, L., Sólon, A., Adebimpe, A., Franco, A. R., Poldrack, R. A., Vogelstein, J. T., Xu, T., Satterthwaite, T., Craddock, R. C., & Milham, M. P. (2020). **Evaluating and Improving Cross-Pipeline Reproducibility in Functional Connectomics: A Case Study.** 2020 Organization for Human Brain Mapping (OHBM) Annual Meeting. [[poster](/assets/poster/OHBM20_XL.pdf)]

Jin, H., Giavasis, S., **Li, X.,** Sólon, A., Ai, L., Franco, A. R., Ramirez, J. S. B., Wang, X., Gozzi, A., Pagani, M., Fox, A., Messinger, A., Fair, D. A., Keilholz, S., Russ, B., Xu, T., Craddock, R. C., & Milham, M. P. (2020). **A Unified, End-to-End Pipeline Solution for Human and Nonhuman Functional Connectomics.** 2020 Organization for Human Brain Mapping (OHBM) Annual Meeting. [[poster](/assets/poster/OHBM20_HJ.pdf)]

**Li, X.,** Tsamis, E., Thakoor, K. A., Zemborain, Z., Moraes, C. G. D., & Hood, D. C. (2020). **Evaluating the transferability of deep learning models that distinguish glaucomatous from non-glaucomatous OCT circumpapillary disc scans.** Investigative Ophthalmology & Visual Science, 61(7), 4548–4548. [[abstract](https://iovs.arvojournals.org/article.aspx?articleid=2769404)]

Thakoor, K. A., **Li, X.,** Tsamis, E., Sajda, P., & Hood, D. C. (2019). **Enhancing the Accuracy of Glaucoma Detection from OCT Probability Maps using Convolutional Neural Networks.** 2019 41st Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC), 2036–2040. https://doi.org/10.1109/EMBC.2019.8856899 [[paper](https://doi.org/10.1109/EMBC.2019.8856899)]

Feng, Y., Chung, E., **Li, X.,** Cycowicz, Y. M., & He, X. (2019). **Deep Learning for Motor Imagery Classification based on EEG Data.** New York Scientific Data Summit 2019. [[poster](/assets/poster/NYSDS19_YF.pdf)]

Thakoor, K. A., Zheng, Q., Nan, L., **Li, X.,** Tsamis, E., Rajshekhar, R., Dwivedi, I., Drori, I., Sajda, P., & Hood, D. C. (2019). **Assessing the Ability of Convolutional Neural Networks to Detect Glaucoma from OCT Probability Maps.** Investigative Ophthalmology & Visual Science, 60(9), 1464–1464. [[abstract](http://iovs.arvojournals.org/article.aspx?articleid=2741905)][[poster](/assets/poster/ARVO19_KT.pdf)]

Joiner, D., **Li, X.,** Eguia, M., Tsamis, E., Sun, A., Moraes, C. G. D., Ritch, R., & Hood, D. C. (2019). **Detecting progression of preserved areas of retinal nerve fiber layer in advanced glaucoma using optical coherence tomography.** Investigative Ophthalmology & Visual Science, 60(9), 5547–5547. [[abstract](http://iovs.arvojournals.org/article.aspx?articleid=2746331)][[poster](/assets/poster/ARVO19_DJ.pdf)]

Eguia, M., **Li, X.,** Joiner, D., Tsamis, E., Moraes, C. G. D., Ritch, R., & Hood, D. C. (2019). **Detecting progression on local areas of retinal nerve fiber layer in glaucoma suspects and early glaucoma using optical coherence tomography.** Investigative Ophthalmology & Visual Science, 60(9), 5594–5594. [[abstract](http://iovs.arvojournals.org/article.aspx?articleid=2747020)][[poster](/assets/poster/ARVO19_ME.pdf)]

Sun, A., Tsamis, E., **Li, X.,** Tsang, K., Al-Aswad, L., Blumberg, D., Cioffi, G., Liebmann, J. M., Moraes, C. G. de, & Hood, D. C. (2019). **Detecting progression of early glaucoma using alternative methods with optical coherence tomography.** Investigative Ophthalmology & Visual Science, 60(9), 5545–5545. [[abstract](http://iovs.arvojournals.org/article.aspx?articleid=2746329)][[poster](/assets/poster/ARVO19_AS.pdf)]