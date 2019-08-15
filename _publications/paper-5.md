---
title: "PPGAN: Privacy-preserving Generative Adversarial Network (under review)"
collection: publications
permalink: /publication/paper-5
excerpt: 'Generative Adversarial Network (GAN) and its variants serve as a perfect representation of the data generation model, providing researchers with a large amount of highquality generated data. They illustrate a promising direction for research with limited data availability. When GAN learns the semantic-rich data distribution from a dataset, the density of the generated distribution tends to concentrate on the training data. Due to the gradient parameters of the deep neural network contain the data distribution of the training samples, they can easily remember the training samples. When GAN is applied to private or sensitive data, for instance, patient medical records, as private information may be leakage. To address this issue, we propose a Privacy-preserving Generative Adversarial Network (PPGAN) model, in which we achieve differential privacy in GANs by adding well-designed noise to the gradient during the model learning procedure. Besides, we introduced the Moments Accountant strategy in the PPGAN training process to improve the stability and compatibility of the model by controlling privacy loss. We also give a mathematical proof of the differential privacy discriminator. Through extensive case studies of the benchmark datasets, we demonstrate that PPGAN can generate high-quality synthetic data while retaining the required data available under a reasonable privacy budget.'
date: 2019-12-04
venue: 'The 25th IEEE International Conference on Parallel and Distributed Systems (ICPADS) (CCF-C, Core-B Conference)'
paperurl: 'https://github.com/niklausliu/niklausliu.github.io/raw/master/files/ICPADS2019_paper_194.pdf'

---
# Abstart
Generative Adversarial Network (GAN) and its variants serve as a perfect representation of the data generation model, providing researchers with a large amount of highquality generated data. They illustrate a promising direction for research with limited data availability. When GAN learns the semantic-rich data distribution from a dataset, the density of the generated distribution tends to concentrate on the training data. Due to the gradient parameters of the deep neural network contain the data distribution of the training samples, they can easily remember the training samples. When GAN is applied to private or sensitive data, for instance, patient medical records, as private information may be leakage. To address this issue, we propose a Privacy-preserving Generative Adversarial Network (PPGAN) model, in which we achieve differential privacy in GANs by adding well-designed noise to the gradient during the model learning procedure. Besides, we introduced the Moments Accountant strategy in the PPGAN training process to improve the stability and compatibility of the model by controlling privacy loss. We also give a mathematical proof of the differential privacy discriminator. Through extensive case studies of the benchmark datasets, we demonstrate that PPGAN can generate high-quality synthetic data while retaining the required data available under a reasonable privacy budget.

## Introduction
training data to perform data mining tasks, in the field of medical and health informatics, such as disease prediction and auxiliary diagnosis. Deep learning models are employed to remember the characteristics of a large number of training sample for classification or prediction purposes. However, organizations such as hospitals and research institutes are paying more and more attention to the protection of data. Additionally, General Data Protection Regulation (GDPR) issued by the European Union prohibits organizations from sharing private data. It is increasingly difficult for researchers to obtain training data unlimited legally.

## Model
As shown in Fig. 3. DPDM reduces the sensitivity of these gradient-decreasing updates (and thus the overall accuracy) by clipping the stochastic gradients, essentially ensuring that the gradient will be within a bounded range. Hence, we only need to add noise proportional to the sensitivity to ensure differential privacy. (In the Algorithm 2.) We present the steps of PPGAN in Fig. 2:

<img src="/images/fig3.pdf" alt="PPGAN" title="PPGAN" width="700" height="500" />
## Result

## Citations
<pre>
Coming soon....
</pre>

[[Download]](https://github.com/niklausliu/niklausliu.github.io/raw/master/files/ICPADS2019_paper_194.pdf)
