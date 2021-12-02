# 544 Project: Story Generation
## Overview
Our project consisted of two main goals:
### Reimplement BiLSTM/LSTM static models from Plan-and-Write
`seq2seq` includes:
- `544_seq2seq.ipynb`: runs encoder/decoder code within `codelab` folder.
- `544Project (1).ipynb`: our attempt at restructuring the `codelab` code to be run in a single Google Colab file. While the code generated relevant storylines, training for the story generation needed more GPU resources. 
- `StoryGenerator.ipynb`: our attempt at implementing the baseline Seq2Seq model from scratch. While the code was able to generate storylines and stories, the storylines were repetitive and the stories were not coherent. We did not continue with this code due to a lack of proper resources required to train many more epochs.
- `plan_write_codelab/`: we modified parts of [rishishian/plan_write repo](https://github.com/rishishian/plan_write) to be able to run it ourselves.
### Replace baseline Seq2Seq model with BART to achieve better results
`bart/` includes :
- ipynb files that will generate and test the BART title-to-storyline and storyline-to-story models (and their pdf versions).
- ROCStories datasets.
- output results in csv format.


## References
[1] Rishishian. 2019. plan_write. Last accessed Dec 1st, 2021.

