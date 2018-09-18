# Awesome GAN for Medical Imaging
A curated list of awesome GAN resources in medical imaging, inspired by the other awesome-* initiatives.

For a complete list of GANs in general computer vision, please visit [really-awesome-gan](https://github.com/nightrome/really-awesome-gan).

To complement or correct it, please contact me at xiy525@mail.usask.ca or send a pull request.

## Overview
- [Low Dose CT Denoising](#low-dose-ct-denoising)
- [Segmentation](#segmentation)
- [Detection](#detection)
- [Medical Image Synthesis](#medical-image-synthesis)
- [Reconstruction](#reconstruction)
- [Classification](#classification)
- [Others](#others)

# Low Dose CT Denoising
- [Generative Adversarial Networks for Noise Reduction in Low-Dose CT]  [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&sciodt=0%2C5&cites=18303813038948630123&scipsc=&q=Generative+Adversarial+Networks+for+Noise+Reduction+in+Low-Dose+CT&btnG=) [[TMI]](http://ieeexplore.ieee.org/document/7934380/)
- [Low Dose CT Image Denoising Using a Generative Adversarial Network with Wasserstein Distance and Perceptual Loss] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Low+Dose+CT+Image+Denoising+Using+a+Generative+Adversarial+Network+with+Wasserstein+Distance+and+Perceptual+Loss&btnG=) [[arXiv]](https://arxiv.org/abs/1708.00961)
- [Sharpness-aware Low dose CT denoising using conditional generative adversarial network] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Sharpness-aware+Low+dose+CT+denoising+using+conditional+generative+adversarial+network&btnG=) [[arXiv]](https://arxiv.org/abs/1708.06453) [[JDI]](https://link.springer.com/article/10.1007/s10278-018-0056-0) [[code]](https://github.com/xinario/SAGAN)
- [Cycle Consistent Adversarial Denoising Network for Multiphase Coronary CT Angiography] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Cycle+Consistent+Adversarial+Denoising+Network+for+Multiphase+Coronary+CT+Angiography&btnG=) [[arXiv]](https://arxiv.org/abs/1806.09748)
- [Structure-sensitive Multi-scale Deep Neural Network for Low-Dose CT Denoising] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Structure-sensitive+Multi-scale+Deep+Neural+Network+for+Low-Dose+CT+Denoising&btnG=) [[arXiv]](https://arxiv.org/abs/1805.00587)
- [3-D Convolutional Encoder-Decoder Network for Low-Dose CT via Transfer Learning From a 2-D Trained Network] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=3-D+Convolutional+Encoder-Decoder+Network+for+Low-Dose+CT+via+Transfer+Learning+From+a+2-D+Trained+Network&btnG=) [[arXiv]](https://arxiv.org/abs/1802.05656) [[code]](https://github.com/hmshan/CPCE-3D.git)

# Segmentation
- [SegAN: Adversarial Network with Multi-scale L1 Loss for Medical Image Segmentation] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=SegAN%3A+Adversarial+Network+with+Multi-scale+L1+Loss+for+Medical+Image+Segmentation&btnG=) [[arXiv]](https://arxiv.org/abs/1706.01805)
- [Adversarial training and dilated convolutions for brain MRI segmentation] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Adversarial+training+and+dilated+convolutions+for+brain+MRI+segmentation&btnG=) [[arXiv]](https://arxiv.org/abs/1707.03195)
- [Retinal Vessel Segmentation in Fundoscopic Images with Generative Adversarial Networks] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Retinal+Vessel+Segmentation+in+Fundoscopic+Images+with+Generative+Adversarial+Networks&btnG=) [[arXiv]](https://arxiv.org/abs/1706.09318)
- [Automatic Liver Segmentation Using an Adversarial Image-to-Image Network] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Automatic+Liver+Segmentation+Using+an+Adversarial+Image-to-Image+Network&btnG=) [[arXiv]](https://arxiv.org/abs/1707.08037)
- [Deep Adversarial Networks for Biomedical Image Segmentation Utilizing Unannotated Images] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Deep+Adversarial+Networks+for+Biomedical+Image+Segmentation+Utilizing+Unannotated+Images&btnG=) [[MICCAI17]](https://link.springer.com/chapter/10.1007/978-3-319-66179-7_47)
- [SCAN: Structure Correcting Adversarial Network for Organ Segmentation in Chest X-rays] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=SCAN%3A+Structure+Correcting+Adversarial+Network+for+Organ+Segmentation+in+Chest+X-rays&btnG=) [[arXiv]](https://arxiv.org/abs/1703.08770)
- [Adversarial Deep Structured Nets for Mass Segmentation from Mammograms] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Adversarial+Deep+Structured+Nets+for+Mass+Segmentation+from+Mammograms&btnG=) [[arXiv]](https://arxiv.org/abs/1710.09288) [[code]](https://github.com/wentaozhu/adversarial-deep-structural-networks)
- [Adversarial Synthesis Learning Enables Segmentation Without Target Modality Ground Truth] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Adversarial+Synthesis+Learning+Enables+Segmentation+Without+Target+Modality+Ground+Truth&btnG=) [[arXiv]](https://arxiv.org/abs/1712.07695)
- [Adversarial neural networks for basal membrane segmentation of microinvasive cervix carcinoma in histopathology images] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Adversarial+neural+networks+for+basal+membrane+segmentation+of+microinvasive+cervix+carcinoma+in+histopathology+images&btnG=) [[ICMLC]](https://ieeexplore-ieee-org.cyber.usask.ca/abstract/document/8108952/)
- [Unsupervised domain adaptation in brain lesion segmentation with adversarial networks] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+domain+adaptation+in+brain+lesion+segmentation+with+adversarial+networks&btnG=) [[IPMI2017]](https://link.springer.com/chapter/10.1007/978-3-319-59050-9_47)
- [whole heart and great vessel segmentation with context aware generative adversarial network] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=whole+heart+and+great+vessel+segmentation+with+context+aware+generative+adversarial+network&btnG=) [[BM]](https://link.springer.com/chapter/10.1007/978-3-662-56537-7_89)
- [Generative Adversarial Neural Networks for Pigmented and Non-Pigmented Skin Lesions Detection in Clinical Images] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Generative+Adversarial+Neural+Networks+for+Pigmented+and+Non-Pigmented+Skin+Lesions+Detection+in+Clinical+Images&btnG=) [[CSCS2017]](https://ieeexplore.ieee.org/document/7968584/)
- [Generative Adversarial Networks to Segment Skin Lesions] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Generative+Adversarial+Networks+to+Segment+Skin+Lesions&btnG=) [[ISBI2018]](http://www.cs.sfu.ca/~hamarneh/ecopy/isbi2018b.pdf)
- [A conditional adversarial network for semantic segmentation of brain tumor] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Conditional+Adversarial+Network+for+Semantic+Segmentation+of+Brain+Tumo&btnG=) [[arXiv]](https://arxiv.org/abs/1708.05227)
- [Brain Tumor Segmentation Using an Adversarial Network] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Brain+Tumor+Segmentation+Using+an+Adversarial+Network&btnG=) [[MICCAI Brainlesion workshop]](https://link.springer.com/chapter/10.1007/978-3-319-75238-9_11)
- [Joint Optic Disc and Cup Segmentation using Fully Convolutional and Adversarial Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Joint+Optic+Disc+and+Cup+Segmentation+using+Fully+Convolutional+and+Adversarial+Networks&btnG=) [[OMIA2017]](https://link.springer.com/chapter/10.1007/978-3-319-67561-9_19)
- [Splenomegaly Segmentation using Global Convolutional Kernels and Conditional Generative Adversarial Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Splenomegaly+Segmentation+using+Global+Convolutional+Kernels+and+Conditional+Generative+Adversarial+Networks&btnG=) [[SPIE MI]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10574/1057409/Splenomegaly-segmentation-using-global-convolutional-kernels-and-conditional-generative-adversarial/10.1117/12.2293406.short?SSO=1)
- [CC-GAN A Robust Transfer-Learning Framework for HEp-2 Specimen Image Segmentation] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=CC-GAN+A+Robust+Transfer-Learning+Framework+for+HEp-2+Specimen+Image+Segmentation&btnG=) [[TA]](https://ieeexplore.ieee.org/abstract/document/8301400/)
- [Unsupervised Cross-Modality Domain Adaptation of ConvNets for Biomedical Image Segmentations with Adversarial Loss] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+Cross-Modality+Domain+Adaptation+of+ConvNets+for+Biomedical+Image+Segmentations+with+Adversarial+Loss&btnG=) [[arXiv]](https://arxiv.org/abs/1804.10916)
- [Retinal Vessel Segmentation under Extreme Low Annotation: A Generative Adversarial Network Approach] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Retinal+Vessel+Segmentation+under+Extreme+Low+Annotation%3A+A+Generative+Adversarial+Network+Approach&btnG=) [[arXiv]](https://arxiv.org/abs/1809.01348)


# Detection
- [Unsupervised Anomaly Detection with Generative Adversarial Networks to Guide Marker Discovery] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+Anomaly+Detection+with+Generative+Adversarial+Networks+to+Guide+Marker+Discovery&btnG=) [[arXiv]](https://arxiv.org/abs/1703.05921)
- [Generative adversarial networks for brain lesion detection] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Generative+adversarial+networks+for+brain+lesion+detection&btnG=) [[JMI]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10133/1/Generative-adversarial-networks-for-brain-lesion-detection/10.1117/12.2254487.short)
- [Adversarial Networks for the Detection of Aggressive Prostate Cancer] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=dversarial+Networks+for+the+Detection+of+Aggressive+Prostate+Cancer&btnG=) [[arXiv]](https://arxiv.org/abs/1702.08014)
- [Visual Feature Attribution using Wasserstein GANs] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Visual+Feature+Attribution+using+Wasserstein+GANs&btnG=) [[arXiv]](https://arxiv.org/abs/1711.08998)
- [Unsupervised Detection of Lesions in Brain MRI using constrained adversarial auto-encoders] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+Detection+of+Lesions+in+Brain+MRI+using+constrained+adversarial+auto-encoders&btnG=) [[arXiv]](https://arxiv.org/abs/1806.04972)


# Medical Image Synthesis
- [Medical Image Synthesis with Context-Aware Generative Adversarial Networks] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Medical+Image+Synthesis+with+Context-Aware+Generative+Adversarial+Networks&btnG=) [[arXiv]](https://arxiv.org/abs/1612.05362)
- [Medical Image Synthesis with Deep Convolutional Adversarial Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Medical+Image+Synthesis+with+Deep+Convolutional+Adversarial+Networks&btnG=) [[TBME]](https://ieeexplore.ieee.org/abstract/document/8310638/) (published vision of the above preprint)
- [Deep MR to CT Synthesis using Unpaired Data] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Deep+MR+to+CT+Synthesis+using+Unpaired+Data&btnG=) [[arXiv]](https://arxiv.org/abs/1708.01155)
- [Synthesizing Filamentary Structured Images with GANs] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Synthesizing+Filamentary+Structured+Images+with+GANs&btnG=) [[arXiv]](https://arxiv.org/abs/1706.02185) [[code]](https://web.bii.a-star.edu.sg/archive/machine_learning/Projects/filaStructObjs/Synthesis/downloads.html)
- [Synthesizing retinal and neuronal images with generative adversarial nets] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Synthesizing+retinal+and+neuronal+images+with+generative+adversarial+nets&btnG=) [[MIA]](https://www.sciencedirect.com/science/article/pii/S1361841518304596) (published vision of the above preprint)
- [Synthesis of Positron Emission Tomography (PET) Images via Multi-channel Generative Adversarial Networks] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Synthesis+of+Positron+Emission+Tomography+%28PET%29+Images+via+Multi-channel+Generative+Adversarial+Networks&btnG=) (GANs) [[arXiv]](https://arxiv.org/abs/1707.09747)
- [Freehand Ultrasound Image Simulation with Spatially-Conditioned Generative Adversarial Networks] [[scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Freehand+Ultrasound+Image+Simulation+with+Spatially-Conditioned+Generative+Adversarial+Networks&btnG=) [[arXiv]](https://arxiv.org/abs/1707.05392)
- [Synthetic Medical Images from Dual Generative Adversarial Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Synthetic+Medical+Images+from+Dual+Generative+Adversarial+Networks&btnG=) [[arXiv]](https://arxiv.org/abs/1709.01872)
- [Virtual PET Images from CT Data Using Deep Convolutional Networks: Initial Results] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Virtual+PET+Images+from+CT+Data+Using+Deep+Convolutional+Networks&btnG=) [[arXiv]](https://arxiv.org/abs/1707.09585)
- [Towards Adversarial Retinal Image Synthesis] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Towards+Adversarial+Retinal+Image+Synthesis&btnG=) [[arXiv]](https://arxiv.org/abs/1701.08974)
- [End-to-end Adversarial Retinal Image Synthesis] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=End-to-end+Adversarial+Retinal+Image+Synthesis&btnG=) [[TMI]](http://ieeexplore.ieee.org/abstract/document/8055572/) (published vision of the above preprint)
- [Adversarial Image Synthesis for Unpaired Multi-Modal Cardiac Data] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Adversarial+Image+Synthesis+for+Unpaired+Multi-Modal+Cardiac+Data&btnG=) [[SASHIMI 2017]](https://link.springer.com/chapter/10.1007/978-3-319-68127-6_1)
- [Biomedical Data Augmentation Using Generative Adversarial Neural Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Biomedical+Data+Augmentation+Using+Generative+Adversarial+Neural+Networks&btnG=) [[ICANN 2017]](https://link.springer.com/chapter/10.1007/978-3-319-68612-7_71)
- [Towards Virtual H&E Staining of Hyperspectral Lung Histology Images Using Conditional Generative Adversarial Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Towards+Virtual+H%26E+Staining+of+Hyperspectral+Lung+Histology+Images+Using+Conditional+Generative+Adversarial+Networks&btnG=) [[ICCV2017 workshop]](http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w1/Bayramoglu_Towards_Virtual_HE_ICCV_2017_paper.pdf)
- [How to Fool Radiologists with Generative Adversarial Networks? A Visual Turing Test for Lung Cancer Diagnosis] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=How+to+Fool+Radiologists+with+Generative+Adversarial+Networks%3F+A+Visual+Turing+Test+for+Lung+Cancer+Diagnosis&btnG=) [[arXiv]](https://arxiv.org/abs/1710.09762)
- [Unsupervised Reverse Domain Adaptation for Synthetic Medical Images via Adversarial Training] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+Reverse+Domain+Adaptation+for+Synthetic+Medical+Images+via+Adversarial+Training&btnG=) [[arXiv]](https://arxiv.org/abs/1711.06606)
- [Unsupervised Histopathology Image Synthesis] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+Histopathology+Image+Synthesis&btnG=) [[arXiv]](https://arxiv.org/abs/1712.05021)
- [Image Synthesis in Multi-Contrast MRI with Conditional Generative Adversarial Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Image+Synthesis+in+Multi-Contrast+MRI+with+Conditional+Generative+Adversarial+Networks&btnG=) [[arXiv]](https://arxiv.org/abs/1802.01221)
- [Translating and Segmenting Multimodal Medical Volumes with Cycle- and Shape-Consistency Generative Adversarial Network] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Translating+and+Segmenting+Multimodal+Medical+Volumes+with+Cycle-+and+Shape-Consistency+Generative+Adversarial+Network&btnG=) [[arXiv]](https://arxiv.org/abs/1802.09655)
- [MRI Image-to-Image Translation for Cross-Modality Image Registration and Segmentation] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=MRI+Image-to-Image+Translation+for+Cross-Modality+Image+Registration+and+Segmentation&btnG=) [[arXiv]](https://arxiv.org/abs/1801.06940)
- [Cross-modality image synthesis from unpaired data using CycleGAN: Effects of gradient consistency loss and training data size] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Cross-modality+image+synthesis+from+unpaired+data+using+CycleGAN%3A+Effects+of+gradient+consistency+loss+and+training+data+size&btnG=) [[arXiv]](https://arxiv.org/abs/1803.06629)
- [Cross-Modality Synthesis from CT to PET using FCN and GAN Networks for Improved Automated Lesion Detection] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Cross-Modality+Synthesis+from+CT+to+PET+using+FCN+and+GAN+Networks+for+Improved+Automated+Lesion+Detection&btnG=) [[arXiv]](https://arxiv.org/abs/1802.07846)
- [MelanoGANs: High Resolution Skin Lesion Synthesis with GANs] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=MelanoGANs%3A+High+Resolution+Skin+Lesion+Synthesis+with+GANs&btnG=) [[arXiv]](https://arxiv.org/abs/1804.04338)
- [Domain-adversarial neural networks to address the appearance variability of histopathology images] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Domain-adversarial+neural+networks+to+address+the+appearance+variability+of+histopathology+images&btnG=) [[arXiv]](https://arxiv.org/abs/1707.06183)
- [Neural Stain-Style Transfer Learning using GAN for Histopathological Images] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=https%3A%2F%2Farxiv.org%2Fabs%2F1710.08543&btnG=) [[arXiv]](https://arxiv.org/abs/1710.08543)
- [Generative Adversarial Training for MRA Image Synthesis Using Multi-Contrast MRI
] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Generative+Adversarial+Training+for+MRA+Image+Synthesis+Using+Multi-Contrast+MRI&btnG=) [[arXiv]](https://arxiv.org/abs/1804.04366)
- [Histopathology Stain-Color Normalization Using Generative Neural Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Histopathology+Stain-Color+Normalization+Using+Generative+Neural+Networks&btnG=) [[MIDL2018]](https://openreview.net/pdf?id=SkjdxkhoG)
- [3D cGAN based cross-modality MR image synthesis for brain tumor segmentation] [[scholar]](https://scholar.google.ca/scholar?q=3D+CGAN+BASED+CROSS-MODALITY+MR+IMAGE+SYNTHESIS+FOR+BRAIN+TUMOR+SEGMENTATION&hl=en&as_sdt=0&as_vis=1&oi=scholart) [[ISBI2018]](https://ieeexplore.ieee.org/abstract/document/8363653/)
- [Deep CT to MR Synthesis using Paired and Unpaired Data] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Deep+CT+to+MR+Synthesis+using+Paired+and+Unpaired+Data&btnG=) [[arXiv]](https://arxiv.org/abs/1805.10790)
- [GAN-based synthetic brain MR image generation] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=GAN-based+synthetic+brain+MR+image+generation&btnG=) [[ISBI2018]](https://ieeexplore.ieee.org/abstract/document/8363678/)
- [StainGAN: Stain Style Transfer for Digital Histological Images] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=https%3A%2F%2Farxiv.org%2Fabs%2F1804.01601&btnG=) [[arXiv]](https://arxiv.org/abs/1804.01601)
- [Adversarial Stain Transfer for Histopathology Image Analysis] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Adversarial+Stain+Transfer+for+Histopathology+Image+Analysis&btnG=) [[TMI]](https://ieeexplore.ieee.org/document/8170242/)
- [Chest x-ray generation and data augmentation for cardiovascular abnormality classification] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Chest+x-ray+generation+and+data+augmentation+for+cardiovascular+abnormality+classification&btnG=) [[SPIE MI2018]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10574/105741M/Chest-x-ray-generation-and-data-augmentation-for-cardiovascular-abnormality/10.1117/12.2293971.short?SSO=1)
- [blood vessel geometry synthesis using generative adversarial networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=blood+vessel+geometry+synthesis+using+generative+adversarial+networks&btnG=) [[MIDL2018]](https://arxiv.org/abs/1804.04381)
- [Synergistic Reconstruction and Synthesis via Generative Adversarial Networks for Accelerated Multi-Contrast MRI] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Synergistic+Reconstruction+and+Synthesis+via+Generative+Adversarial+Networks+for+Accelerated+Multi-Contrast+MRI&btnG=) [[arXiv]](https://arxiv.org/abs/1805.10704)
- [Stain normalization of histopathology images using generative adversarial networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Stain+normalization+of+histopathology+images+using+generative+adversarial+networks&btnG=) [[ISBI2018]](https://ieeexplore.ieee.org/abstract/document/8363641/)
- [MedGAN: Medical Image Translation using GANs] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=MedGAN%3A+Medical+Image+Translation+using+GANs&btnG=) [[arXiv]](https://arxiv.org/abs/1806.06397)
- [Retinal Image Synthesis for CAD Development] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Retinal+Image+Synthesis+for+CAD+Development&btnG=) [[ICIAR]](https://link.springer.com/chapter/10.1007/978-3-319-93000-8_70)
- [High-Resolution Mammogram Synthesis using Progressive Generative Adversarial Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=High-Resolution+Mammogram+Synthesis+using+Progressive+Generative+Adversarial+Networks&btnG=) [[arXiv]](https://arxiv.org/abs/1807.03401)
- [High-resolution medical image synthesis using progressively grown generative adversarial networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=High-resolution+medical+image+synthesis+using+progressively+grown+generative+adversarial+networks&btnG=) [[arXiv]](https://arxiv.org/abs/1805.03144)
- [Learning Myelin Content in Multiple Sclerosis from Multimodal MRI through Adversarial Training] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Learning+Myelin+Content+in+Multiple+Sclerosis+from+Multimodal+MRI+through+Adversarial+Training&btnG=) [[MICCAI2018]](https://arxiv.org/abs/1804.08039)
- [Generation of structural MR images from amyloid PET: Application to MR-less quantification] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Generation+of+structural+MR+images+from+amyloid+PET%3A+Application+to+MR-less+quantification.&btnG=) [[JNM]](https://europepmc.org/abstract/med/29217736)
- [Task Driven Generative Modeling for Unsupervised Domain Adaptation Application to X-ray Image Segmentation] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Task+Driven+Generative+Modeling+for+Unsupervised+Domain+Adaptation+Application+to+X-ray+Image+Segmentation&btnG=) [[arXiv]](https://arxiv.org/abs/1806.07201)
- [Exploring the potential of generative adversarial networks for synthesizing radiological images of the spine to be used in in silico trials] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Exploring+the+potential+of+generative+adversarial+networks+for+synthesizing+radiological+images+of+the+spine+to+be+used+in+in+silico+trials&btnG=) [[FBB]](https://www.frontiersin.org/articles/10.3389/fbioe.2018.00053/full)
- [Semantic-Aware Generative Adversarial Nets for Unsupervised Domain Adaptation in Chest X-ray Segmentation] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Semantic-Aware+Generative+Adversarial+Nets+for+Unsupervised+Domain+Adaptation+in+Chest+X-ray+Segmentation&btnG=) [[arXiv]](https://arxiv.org/abs/1806.00600)
- [Learning Data Augmentation for Brain Tumor Segmentation with Coarse-to-Fine Generative Adversarial Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Learning+Data+Augmentation+for+Brain+Tumor+Segmentation+with+Coarse-to-Fine+Generative+Adversarial+Networks+&btnG=) [[arXiv]](https://arxiv.org/abs/1805.11291)
- [Learning implicit brain MRI manifolds with deep learning] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Learning+implicit+brain+MRI+manifolds+with+deep+learning&btnG=) [[SPIE MI2018]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10574/105741L/Learning-implicit-brain-MRI-manifolds-with-deep-learning/10.1117/12.2293515.short?SSO=1)
- [Optimized generation of high-resolution phantom images using cGAN: Application to quantification of Ki67 breast cancer images] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Optimized+generation+of+high-resolution+phantom+images+using+cGAN%3A+Application+to+quantification+of+Ki67+breast+cancer+images&btnG=) [[PloS one]](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0196846)
- [Generative Adversarial Networks for Image-to-Image Translation on Multi-Contrast MR Images-A Comparison of CycleGAN and UNIT] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Generative+Adversarial+Networks+for+Image-to-Image+Translation+on+Multi-Contrast+MR+Images-A+Comparison+of+CycleGAN+and+UNIT&btnG=) [[arXiv]](https://arxiv.org/abs/1806.07777) [[code]](https://github.com/simontomaskarlsson/GAN-MRI)

# Reconstruction
- [Compressed Sensing MRI Reconstruction with Cyclic Loss in Generative Adversarial Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Compressed+Sensing+MRI+Reconstruction+with+Cyclic+Loss+in+Generative+Adversarial+Networks&btnG=) [[arXiv]](https://arxiv.org/abs/1709.00753)
- [Compressed Sensing MRI Reconstruction using a Generative Adversarial Network with a Cyclic Loss] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Compressed+Sensing+MRI+Reconstruction+using+a+Generative+Adversarial+Network+with+a+Cyclic+Loss&btnG=) [[TMI]](https://ieeexplore-ieee-org.cyber.usask.ca/abstract/document/8327637/) (published version of the above preprint)
- [Deep Generative Adversarial Networks for Compressed Sensing (GANCS) Automates MRI] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0,5&q=Deep+Generative+Adversarial+Networks+for+Compressed+Sensing+(GANS)+Automated+MRI) [[arXiv]](https://arxiv.org/abs/1706.00051) [[code]](https://github.com/gongenhao/GANCS)
- [Accelerated Magnetic Resonance Imaging by Adversarial Neural Network] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Accelerated+Magnetic+Resonance+Imaging+by+Adversarial+Neural+Network&btnG=) [[DLMIA MICCAI 2017]](https://link.springer.com/chapter/10.1007/978-3-319-67558-9_4)
- [Deep De-Aliasing for Fast Compressive Sensing MR] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Deep+De-Aliasing+for+Fast+Compressive+Sensing+MR&btnG=) [[arXiv]](https://arxiv.org/abs/1705.07137)
- [3D conditional generative adversarial networks for high-quality PET image estimation at low dose] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=3D+conditional+generative+adversarial+networks+for+high-quality+PET+image+estimation+at+low+dose&btnG=) [[NI]](https://www.sciencedirect.com/science/article/pii/S1053811918302507?via%3Dihub)
- [Improving resolution of MR images with an adversarial network incorporating images with different contrast] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Improving+resolution+of+MR+images+with+an+adversarial+network+incorporating+images+with+different+contrast&btnG=) [[MP]](https://aapm.onlinelibrary.wiley.com/doi/abs/10.1002/mp.12945)
- [Synergistic Reconstruction and Synthesis via Generative Adversarial Networks for Accelerated Multi-Contrast MRI] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Synergistic+Reconstruction+and+Synthesis+via+Generative+Adversarial+Networks+for+Accelerated+Multi-Contrast+MRI&btnG=) [[arXiv]](https://arxiv.org/abs/1805.10704)
- [CT Super-resolution GAN Constrained by the Identical, Residual, and Cycle Learning Ensemble(GAN-CIRCLE)] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=CT+Super-resolution+GAN+Constrained+by+the+Identical%2C+Residual%2C+and+Cycle+Learning+Ensemble+%28GAN-CIRCLE%29&btnG=) [[arXiv]](https://arxiv.org/abs/1808.04256)
- [Denoising of 3-D Magnetic Resonance Images Using a Residual Encoder-Decoder Wasserstein Generative Adversarial Network] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Denoising+of+3-D+Magnetic+Resonance+Images+Using+a+Residual+Encoder-Decoder+Wasserstein+Generative+Adversarial+Network&btnG=) [[arXiv]](Denoising of 3-D Magnetic Resonance Images Using a Residual Encoder-Decoder Wasserstein Generative Adversarial Network)

# Classification
- [Semi-supervised Assessment of Incomplete LV Coverage in Cardiac MRI Using Generative Adversarial Nets] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Semi-supervised+Assessment+of+Incomplete+LV+Coverage+in+Cardiac+MRI+Using+Generative+Adversarial+Nets&btnG=) [[SASHIMI 2017]](https://link.springer.com/chapter/10.1007/978-3-319-68127-6_7)
- [Generalization of Deep Neural Networks for Chest Pathology Classification in X-Rays Using Generative Adversarial Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Generalization+of+Deep+Neural+Networks+for+Chest+Pathology+Classification+in+X-Rays+Using+Generative+Adversarial+Networks&btnG=) [[arXiv]](https://arxiv.org/abs/1712.01636)
- [Unsupervised Learning for Cell-level Visual Representation in Histopathology Images with Generative Adversarial Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+Learning+for+Cell-level+Visual+Representation+in+Histopathology+Images+with+Generative+Adversarial+Networks&btnG=) [[arXiv]](https://arxiv.org/abs/1711.11317) [[code]](https://github.com/hbkunn/nu_gan)
- [Synthetic Data Augmentation using GAN for Improved Liver Lesion Classification] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Synthetic+Data+Augmentation+using+GAN+for+Improved+Liver+Lesion+Classification&btnG=) [[arXiv]](https://arxiv.org/abs/1801.02385)
- [GAN-based Synthetic Medical Image Augmentation for increased CNN Performance in Liver Lesion Classification] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=GAN-based+Synthetic+Medical+Image+Augmentation+for+increased+CNN+Performance+in+Liver+Lesion+Classification&btnG=) [[arXiv]](https://arxiv.org/abs/1803.01229)(extended version of above preprint)
- [Unsupervised and semi-supervised learning with Categorical Generative Adversarial Networks assisted by Wasserstein distance for dermoscopy image Classification] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+and+semi-supervised+learning+with+Categorical+Generative+Adversarial+Networks+assisted+by+Wasserstein+distance+for+dermoscopy+image+Classification&btnG=) [[arXiv]](https://arxiv.org/abs/1804.03700)
- [Semi-supervised learning with generative adversarial networks for chest X-ray classification with ability of data domain adaptation] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=SEMI-SUPERVISED+LEARNING+WITH+GENERATIVE+ADVERSARIAL+NETWORKS+FOR+CHEST+X-RAY+CLASSIFICATION+WITH+ABILITY+OF+DATA+DOMAIN+ADAPTATION&btnG=) [[ISBI2018]](https://ieeexplore.ieee.org/abstract/document/8363749/)
- [Generative adversarial learning for reducing manual annotation in semantic segmentation on large scale miscroscopy images: Automated vessel segmentation in retinal fundus image as test case] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Generative+adversarial+learning+for+reducing+manual+annotation+in+semantic+segmentation+on+large+scale+miscroscopy+images%3A+Automated+vessel+segmentation+in+retinal+fundus+image+as+test+case&btnG=) [[CVPRW2017]](http://openaccess.thecvf.com/content_cvpr_2017_workshops/w8/papers/Lahiri_Generative_Adversarial_Learning_CVPR_2017_paper.pdf)

# Others
- [Intraoperative Organ Motion Models with an Ensemble of Conditional Generative Adversarial Networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Intraoperative+Organ+Motion+Models+with+an+Ensemble+of+Conditional+Generative+Adversarial+Networks&btnG=) [[arXiv]](https://arxiv.org/abs/1709.02255)
- [Retinal Vasculature Segmentation Using Local Saliency Maps and Generative Adversarial Networks For Image Super Resolution] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Retinal+Vasculature+Segmentation+Using+Local+Saliency+Maps+and+Generative+Adversarial+Networks+For+Image+Super+Resolution&btnG=) [[arXiv]](https://arxiv.org/abs/1710.04783)
- [Adversarial training with cycle consistency for unsupervised super-resolution in endomicroscopy
] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Adversarial+training+with+cycle+consistency+for+unsupervised+super-resolution+in+endomicroscopy&btnG=) [[MIDL2018]](https://openreview.net/forum?id=BktMD6isM)
- [Brain MRI super-resolution using 3D generative adversarial networks
] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Brain+MRI+super-resolution+using+3D+generative+adversarial+networks&btnG=) [[MIDL2018]](https://openreview.net/pdf?id=rJevSbniM)
- [Generative Spatiotemporal Modeling Of Neutrophil Behavior] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Generative+Spatiotemporal+Modeling+Of+Neutrophil+Behavior&btnG=) [[ISBI2018]](https://arxiv.org/abs/1804.00393)
- [Deformable medical image registration using generative adversarial networks] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Deformable+medical+image+registration+using+generative+adversarial+networks&btnG=) [[ISBI2018]](https://ieeexplore.ieee.org/document/8363845/)
- [Adversarial Image Registration with Application for MR and TRUS Image Fusion] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Adversarial+Image+Registration+with+Application+for+MR+and+TRUS+Image+Fusion&btnG=) [[arXiv]](https://arxiv.org/abs/1804.11024)
- [Exploiting the potential of unlabeled endoscopic video data with self-supervised learning] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Exploiting+the+potential+of+unlabeled+endoscopic+video+data+with+self-supervised+learning&btnG=) [[IJCARS]](https://link.springer.com/content/pdf/10.1007/s11548-018-1772-0.pdf)
- [Generative Adversarial Networks for MR-CT Deformable Image Registration] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Generative+Adversarial+Networks+for+MR-CT+Deformable+Image+Registration&btnG=) [[arXiv]](https://arxiv.org/abs/1807.07349)
- [Efficient and Accurate MRI Super-Resolution using a Generative Adversarial Network and 3D Multi-Level Densely Connected Network] [[scholar]](https://scholar.google.ca/scholar?hl=en&as_sdt=0%2C5&q=Efficient+and+Accurate+MRI+Super-Resolution+using+a+Generative+Adversarial+Network+and+3D+Multi-Level+Densely+Connected+Network&btnG=) [[arXiv]](https://arxiv.org/abs/1803.01417)
