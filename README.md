# Neuromatch2023_Medical_Imaging

This project was part of [NeuroMatch Academy Deep Learning 2023](https://deeplearning.neuromatch.io/tutorials/intro.html).

Contributors:

[Jason Bard](https://github.com/j4yb1rd)<br>
[Michael Utterback](https://github.com/Utterbackian)<br>
[Annie Tran](https://github.com/anniettr)<br>
[Edward Lin](https://github.com/EdwardLinS)<br>
[Ahmad Mahmoud Fouad](https://github.com/ahmadMfouad)

## Abstract:

In this study, we delve into the intricate relationship between human vision and brain activity by exploring the link between visual stimuli and corresponding electroencephalogram (EEG) data. Despite burgeoning interest in this area, encapsulated by initiatives such as DreamDiffusion, the precise nature of this relationship remains elusive. We hypothesize that visual stimuli evoked by images can be reconstructed from patterns in EEG brain signals. To this end, we have developed a Pytorch model comprising a two-layer Long Short-Term Memory (LSTM) encoder and a Generative Adversarial Network (GAN).
Our approach draws inspiration from both Brain2Image and EEG2Image; however, we have intentionally simplified our model’s architecture due to limited time and computational power. The encoder component of our framework translates the high-dimensional and temporally varying EEG brain signals into a compact 1D vector, extracting the salient features relevant for visual reconstruction. Subsequently, we employ a GAN architecture that takes the 1D vector from the encoder as a conditional input, supplemented with Gaussian noise, to generate visual images from the given EEG brain signal and the corresponding image class.
To test our hypothesis, we analyzed pre-existing EEG data ranging from 5 to 95 hertz, which were recorded while subjects viewed 40 different image classes from the ImageNet database. Our findings, which are yet to be fully detailed, may further our general understanding of human neural responses to visual stimuli and, with further development, may be used to visualize brain activity, such as dreams.

## List of resources

[• Link to filtered data](https://drive.google.com/file/d/1zUs8IQkTuepAQ_lqJA09lfo9nylmSuyL/view)<br>
[• Link to original EEG dataset](https://github.com/perceivelab/eeg_visual_classification)

## References

Brain2Image: Converting Brain Signals into Images. [(Paper)](https://doi.org/10.1145/3123266.3127907)<br>
Decoding Brain Representations by Multimodal Learning of Neural Activity and Visual Features. [(Paper)](https://doi.org/10.48550/arXiv.1810.10974) <br>
Deep Learning Human Mind for Automated Visual Classification. [(Paper)](https://doi.org/10.48550/arXiv.1609.00344)<br>
DreamDiffusion: Generating High-Quality Images from Brain EEG Signals. [(Paper)](https://doi.org/10.48550/arXiv.2306.16934) [(Github)](https://github.com/bbaaii/DreamDiffusion)<br>
EEG2IMAGE: Image Reconstruction from EEG Brain Signals. [(Paper)](https://doi.org/10.48550/arXiv.2302.10121) [(Github)](https://github.com/prajwalsingh/EEG2Image/tree/main)<br>
Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks. [(Paper)](https://doi.org/10.48550/arXiv.1511.06434)