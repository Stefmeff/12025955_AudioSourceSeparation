# Audio Source Seperation (Stefan Moser, 12025955)

- **Goal:** Seperating a song into its individual stems like vocals, drums, bass and other instrumentals

- **Project Type:** *Bring your own method*

Since I am new to deep learning, I choose this proposed topic as I found there is much learning material
available on the provided source SigSep [1].

My goal would be to implement my own neural network architecture and learn all the needed deep learning concepts, 
while having an already existing open source project with dataset as an orientation [2]. Additionally to the provided datasets on SigSep, I found a dataset [3] for music source seperation, including 240 tracks with their associated stems covering different genres (available on github [4]). Since this dataset is not part of the datasets available on SigSep, one of my tasks would be to preprocess this dataset making it compatible with the model. The idea would then be to implement and train the model by pairing the full audio tracks with their seperated sources. For a general introduction to the topic of source seperation, I also found this survey "Musical Source Separation: An Introduction" [5]. 

# Work Breakdown

- Literature Review: Study deep learning methods for source seperation and understand the open source implementation on SigSep (2 days)
- Design a rough draft of my own pipeline (1 day)
- Data Preparation: Understand and implement data preprocessing (e.g. Short-Time Fourier Analysis for spectorgrams) (2 days)
- Base Implementation of Model (4 days)
- Training, Debugging and Fine Tuning (4 days)
- Testing and evaluation results (1-2 days)
- Implementing Application (1 day) 
- Report (6 h)
- Presentation Preparation (4 h)


# References:
- [1] Open Resources for Music Source Separation: https://sigsep.github.io/
- [2] Open-Unmix Paper: https://www.theoj.org/joss-papers/joss.01667/10.21105.joss.01667.pdf
- [3] Moisesdb: A dataset for source separation beyond 4-stems: https://arxiv.org/abs/2307.15913 
- [4] Moisesdb github: https://github.com/moises-ai/moises-db
- [5] Survey on Source Separation: https://inria.hal.science/hal-01945345v1/document
