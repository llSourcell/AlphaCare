# AlphaCare
![AlphaCare](https://i.imgur.com/d7dkit1.png)

## Background

AlphaCare is a work-in-progress, open-source Deep Learning Engine for Healthcare that aims to treat and prevent major diseases. The goal is to eventually target the root cause of all disease, aging. We'll be building new features every week as a community and in the process, learn about all the potential ways that Deep Learning can be used in Healthcare. 

## Coding Challenge (Due Date: October 7, 2021 at 12 PM PST)

Use DeepMind's Perceiver IO model to classify any type of Medical Image (CT scans, Brain Scans, etc.). You can use the alphacare notebook in the computer vision folder as a starting point, labeled "perceiver". Submit your code to this link and post a classified image example on your favorite social network with the hashtag #AlphaCare. I'll announce the winner in 2 weeks, and we'll integrate their code into this repository. AlphaCare will become more and more multi-purpose as we continually add capabilities to it. 

[Submission Link](https://forms.gle/2DJkYts4HAfHMKpm8)

## Dependencies
- keras
- tensorflow
- pywt (pip install PyWavelets)
- scipy
- sklearn
- matplotlib
- csv
- numpy
- pandas
- os
- itertools
- collections

Use [pip](https://pip.pypa.io/en/stable/installation/) install to install each dependency.

example:
```sh
pip install scipy
```

## Instructions

After installing each dependency, go to the Computer Vision folder and open the notebook titled AlphaCare_Notebook_v1 via [jupyter notebook](https://jupyter.org/) or upload it to [google colab](https://colab.research.google.com/). The Dataset used is the[MIT BIH dataset](https://www.kaggle.com/taejoongyoon/mitbit-arrhythmia-database).

## TODOs (Pull requests are encouraged

- [x] Computer Vision Notebook for ECG Classification
- [ ] Integrate notebook into Flask web app (in progress)
- [ ] Visualize each ECG signal in real-time
- [ ] Add NLP module for Electronic Health Record interpretation
- [ ] Chatbot for Diagnostic Recommendations
- [ ] Data Generation for improved accuracy in text, image, and numeric classification
- [ ] Add Reinforcement Learning engine for real-time predictions on biometric data streams
- [ ] Add Patient privacy preservation functionality via Ethereum Blockchain
- [ ] Add Quantum Machine Learning use case
- [ ] Create Integration pre processing file to allow end to end prediction using any type of data


## Credits

The credits for this code go to [Yomnahesham](https://www.kaggle.com/yomnahesham/cse616-final-project), Keshav Boudaria, and MIT for their dataset. More credits will be added as we integrate more open source repositories into our code base. 
