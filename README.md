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

[Link to filtered data](https://drive.google.com/file/d/1zUs8IQkTuepAQ_lqJA09lfo9nylmSuyL/view)
