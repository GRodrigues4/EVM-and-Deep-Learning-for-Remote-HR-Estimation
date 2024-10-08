# EVM plus Deep Learning approach for Remote Heart Rate Estimation
This repository contains the code developed for a Master's dissertation by Gonçalo Rodrigues, a student at Faculdade de Ciências da Universidade de Lisboa (FCUL). The dissertation explores an approach combining remote Photoplethysmography (rPPG), Eulerian Video Magnification (EVM), and deep learning, aiming to estimate the Heart Rate with enhanced performance and efficiency by utilizing Long Short-Term Memory (LSTM) networks combined with 1D Convolutions.

## Overview
This project explores an approach, utilizing LSTM networks combined with 1D Convolutions, to perform heart rate estimation based on facial videos. Unlike the usual CNN-based methods, this approach offers faster processing, potentially making the model more efficient for real-time applications.

## Key Features
LSTM and 1D Convolutional Architecture: By leveraging LSTMs, the model effectively captures temporal dependencies in the video data, while the 1D convolutions provide efficient feature extraction.
Open Source: All code related to this project is available on GitHub for further exploration, replication, and improvement.

## Dataset
The original Dataset is available on request. The dataset consists of various facial videos accompanied by corresponding electrocardiogram signals. Its purpose is to support research in remote photoplethysmography (rPPG) applications and Eulerian video magnification, developing innovative approaches to measure biomedical signals from videos.
The dataset consists of 27 subjects (13M, 14F), each with up to 90 videos of 20 seconds. The original videos were recorded in 10-minute segments under natural lighting conditions, divided into 30 intervals of 20 seconds each. For each interval, three regions were extracted: Forehead, Cheek1, and Cheek2, resulting in a total of 90 videos per subject. The videos are organized as follows:
	- Subject Number: From 1 to 27
	- Region: Forehead, Cheek1 (right), Cheek2 (left)
	- Interval Number: From 0 to 29 (e.g., 0 corresponds to 0-20 seconds, 1 corresponds to 20-40 seconds, etc.)
 More information is available with the dataset

### Video Specifications:
The code is prepared to handle videos in the following format but all the constructors are prepared to be personalized with other video specifications.
	- Resolution: 64x64 pixels
	- Frame Rate: 30 fps

## Acknowledgements
This work was carried out as part of the requirements for the Master’s degree at Faculdade de Ciências da Universidade de Lisboa. I would like to thank my advisors and colleagues for their guidance and support throughout this project.

## Contact info:
For any questions or suggestions, feel free to reach out through GitHub or email.
Gonçalo Rodrigues, institutional: fc54909@alunos.fc.ul.pt; secondary: goncalorodrigues.4@hotmail.com
Nuno M Garcia, institutional: nmgsantos@ciencias.ulisboa.pt; secondary: ngarcia@ngarcia.net
