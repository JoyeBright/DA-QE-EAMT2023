# DA-QE-EAMT2023
Welcome to the repository for the experiments described in: "Tailoring Domain Adaptation for Machine Translation Quality Estimation"

## Abstract
While quality estimation (QE) can play an important role in the translation process, its effectiveness relies on the availability and quality of training data. For QE in particular, high-quality labeled data is often lacking due to the high cost and effort associated with labeling such data. Aside from the data scarcity challenge, QE models should also be generalizable, i.e., they should be able to handle data from different domains, both generic and specific. To alleviate these two main issues -- data scarcity and domain mismatch -- this paper combines domain adaptation and data augmentation within a robust QE system. Our method first trains a generic QE model and then fine-tunes it on a specific domain while retaining generic knowledge. Our results show a significant improvement for all the language pairs investigated, better cross-lingual inference, and a superior performance in zero-shot learning scenarios as compared to state-of-the-art baselines.

## Models
### NO TAG
|Model   | Baseline | DAG 1 | DAG 2|
|:------:|:--------:|:-----:|:----:|
|EN-DE   |[Download](https://huggingface.co/joyebright/EAMT2023-Baseline-EN-DE)|       |      |
|EN-ZH   |[Download](https://huggingface.co/joyebright/EAMT2023-Baseline-EN-ZH)|       |      |
|RO-EN   |[Download](https://huggingface.co/joyebright/EAMT2023-Baseline-RO-EN)|       |      |
|RU-EN   |          |       |      |

### (With) TAG
|Model   | Baseline | DAG 1 | DAG 2|
|:------:|:--------:|:-----:|:----:|
|EN-DE   |          |       |      |
|EN-ZH   |          |       |      |
|RO-EN   |          |       |      |
|RU-EN   |          |       |      |

## Cite the paper
If you find this repository helpful, feel free to cite our publication:
```
@misc{sharami2023tailoring,
      title={Tailoring Domain Adaptation for Machine Translation Quality Estimation}, 
      author={Javad Pourmostafa Roshan Sharami and Dimitar Shterionov and Frédéric Blain and Eva Vanmassenhove and Mirella De Sisto and Chris Emmery and Pieter Spronck},
      year={2023},
      eprint={2304.08891},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
