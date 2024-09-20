# Project Title: Implementation of 'Decoding Human Activities: Analyzing Wearable Accelerometer and Gyroscope Data for Activity Recognition'

This repository contains the implementation code for the paper **'Decoding Human Activities: Analyzing Wearable Accelerometer and
Gyroscope Data for Activity Recognition'**. You can find the paper via the following ([10.1109/LSENS.2024.3423340](https://doi.org/10.1109/LSENS.2024.3423340)).

## Abstract

_A person's movement or relative positioning can be effectively captured by different types of sensors and corresponding sensor output can be utilized in various manipulative techniques for the classification of different human activities. This letter proposes an effective scheme for human activity recognition, which introduces two unique approaches within a multistructural architecture, named FusionActNet. The first approach aims to capture the static and dynamic behavior of a particular action by using two dedicated residual networks and the second approach facilitates the final decision-making process by introducing a guidance module. A two-stage training process is designed where at the first stage, residual networks are pretrained separately by using static (where the human body is immobile) and dynamic (involving movement of the human body) data. In the next stage, the guidance module along with the pretrained static/dynamic models are used to train the given sensor data. Here, the guidance module learns to emphasize the most relevant prediction vector obtained from the static/dynamic models, which helps to effectively classify different human activities. The proposed scheme is evaluated using two benchmark datasets and compared with state-of-the-art methods. The results clearly demonstrate that our method outperforms existing approaches in terms of accuracy, precision, recall, and F1 score, achieving 97.35% and 95.35% accuracy on the UCI HAR and MotionSense datasets, respectively which highlights both the effectiveness and stability of the proposed scheme._

## Installation

To use this repository, clone it and install the required dependencies using `requirements.txt`.

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/utsabbuet17/FusionActNet.git


## Dataset:
All the datasets used in this project are not included in the repository due to size constraints. Please refer to the paper for instructions on how to acquire the dataset. You can place the dataset in the appropriate directory as described in the code comments.

## Results

The table below presents the performance metrics of the model on two different datasets: **UCI HAR** and **MotionSense**.

| Dataset      | Accuracy | Precision | Recall | F1-Score |
|--------------|----------|-----------|--------|----------|
| **UCI HAR**  | 97.35%    | 97.00%     | 97.10%  | 97.39%    |
| **MotionSense** | 95.35%    | 95.00%     | 95.07%  | 95.21%    |

For detailed results and analysis, please refer to the paper ([10.1109/LSENS.2024.3423340](https://doi.org/10.1109/LSENS.2024.3423340)).

## Copyright

© Utsab Saha and Sawradip Saha, 2024. All rights reserved.

## Citation:
If you use this code or find it helpful for your research, please cite the paper as follows:
**Citation in BibTeX format:**
```bibtex
@article{author2024fusionactnet,
  title={Decoding Human Activities: Analyzing Wearable Accelerometer and Gyroscope Data for Activity Recognition},
  author={Utsab Saha, Sawradip Saha, Md. Tahmid Kabir, Shaikh Anowarul Fattah, and Mohammad Saquib},
  journal={IEEE Sensors Letters},
  volume={8},
  issue={8},
  pages={1--4},
  year={2024},
  publisher={IEEE},
  doi={10.1109/LSENS.2024.3423340}
}




