
# Ewè Directional Voice Assistant: Hackathon Project
## Project Overview
Navigating public spaces is a significant challenge for visually impaired individuals, particularly in regions where accessibility tools are not widely available. This project focuses on developing a machine learning model capable of recognizing basic directional commands in Ewè, a language spoken in parts of West Africa.

The model supports a navigation voice assistant for visually impaired individuals, addressing a critical social issue while promoting linguistic diversity in AI. The commands include:

"up"
"down"
"stop"
"go"
"left"
"right"
"yes"
"no"
This repository documents the process, challenges, and skills developed during the hackathon.

## Objective
To build a machine learning model that accurately classifies audio recordings of directional commands in Ewè for use in a navigation assistant.

## Skills Learned
1. Audio Data Processing
Extracting and normalizing audio features (e.g., MFCCs, spectrograms).
Handling noise and variations in audio recordings.
2. Feature Engineering
Understanding and extracting features relevant to speech recognition tasks.
Utilizing libraries like Librosa for feature extraction.
3. Machine Learning and Deep Learning
Building classification models using machine learning algorithms.
Training and fine-tuning deep learning architectures for speech recognition, including convolutional and recurrent neural networks.
4. Model Evaluation and Optimization
Implementing metrics like accuracy, F1-score, and confusion matrices for model evaluation.
Using optimization techniques to improve accuracy and deployability.
5. Edge Deployment Optimization
Reducing model size for deployment on low-resource devices.
Ensuring inference efficiency on edge devices.
6. Social Impact in AI
Understanding the intersection of technology and social good.
Addressing underrepresented African languages in AI applications.
## Process and Steps Taken
Step 1: Dataset Collection
Collected audio samples in Ewè containing the basic commands.
Ensured dataset diversity by including variations in accents, tones, and background noise.
Step 2: Preprocessing
Cleaned the audio data to remove noise and normalize volume.
Extracted audio features like MFCCs and spectrograms using Librosa.
Step 3: Data Augmentation
Enhanced the dataset by applying techniques such as time-shifting, pitch alterations, and noise addition to improve model robustness.
Step 4: Model Development
Experimented with traditional machine learning models (e.g., Random Forest, SVM).
Developed and fine-tuned deep learning models, including CNN and RNN architectures.
Step 5: Model Evaluation
Evaluated models using metrics such as accuracy, precision, recall, and F1-score.
Iteratively improved performance through hyperparameter tuning and architecture enhancements.
Step 6: Edge Deployment Optimization
Quantized the model to reduce size and improve inference speed.
Ensured the model met the constraints of edge devices for deployment.
Step 7: Testing and Validation
Tested the model on unseen data and in simulated real-world conditions.
Validated the accuracy and usability of the model for visually impaired users.
## Future Work
Scalability: Expand the vocabulary to include more commands and languages.
Real-World Testing: Deploy and gather feedback from visually impaired individuals in Ewè-speaking communities.
Collaboration: Work with linguists and accessibility experts to further refine the solution.
## Acknowledgments
This project is inspired by the need to promote linguistic diversity in AI and to develop technologies that improve accessibility and independence for visually impaired individuals.

If you find this project inspiring or would like to contribute, feel free to submit pull requests or raise issues for discussion.

Contact
If you have questions or feedback about this repository, please reach out:

Email: ayodelemudavanhu@gmail.com
GitHub Profile: @Ayoworker
