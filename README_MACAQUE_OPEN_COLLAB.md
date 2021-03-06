# Open Collaboration on Audio Classification

![includes-data](https://img.shields.io/badge/includes%20data-yes-green)

## Getting Started
This is a collaborative development of techniques to classify/individuate 
macaques based on [bioacoustics cues](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4806230/) ('coos').

Please check out the [Introduction](https://github.com/earthspecies/open_collaboration_on_audio_classification/blob/master/introduction.ipynb) to learn more and get started!

### Leaderboard

| Epochs | URL | Error rate |
|--|--|--|
|9|[vanilla DataBlock torchaudio spectrograms](https://github.com/dienhoa/open_collaboration_on_audio_classification/tree/torchspec)|0.002745|
|6|[fastai2 audio xresnet18](https://github.com/AdPostma/open_collaboration_on_audio_classification)|0.002745|
|40|[fastai2 raw audio conv1d](https://github.com/floleuerer/open_collaboration_on_audio_classification)|0.010295|
|NA|[rocket: features from 1d conv + ridge regression](https://github.com/PomoML/open_collaboration_on_audio_classification/tree/rocketupdate2)|0.026767|
|2|[pretrained resnet18](https://github.com/earthspecies/open_collaboration_on_audio_classification/blob/master/introduction.ipynb)|0.063143|
