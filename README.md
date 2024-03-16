<h1 align="center" style="border-bottom: none">
    <b>
        <a href="https://www.google.com"> LIP BUDDY </a><br>
    </b>
    ⭐️DECODE THE RAW TOKENS INTO WORDS  ⭐️ <br>
</h1>

# [`code link`](https://colab.research.google.com/drive/1By_wUt72ZitpS6O3X-9ctHUJA1Gmgm5K?usp=sharing)  [`Demo video link `](https://drive.google.com/drive/folders/1l7ARlEyMC3lOTEcVqfA7v6-k7zpBlGyG?usp=sharing) [`git hub repo links `](https://github.com/Hemanth-sai-reddy/lip-read-hack-/tree/main)
Lip Reading: The prototype takes input video clips of people speaking and processes them to understand the spoken words by analyzing lip movements. Lip reading involves interpreting the movements and shapes of the lips to understand the spoken language.

Sequence Modeling: We employ sequence modeling techniques, which are well-suited for tasks where input data has a sequential nature, such as video frames or audio samples. Sequence modeling allows the model to learn temporal dependencies and patterns in the input data.

Connectionist Temporal Classification (CTC): CTC is a technique commonly used in sequence modeling tasks like speech and handwriting recognition. It enables the model to learn to align input sequences with target sequences without the need for exact alignment during training. This is particularly useful in lip reading, where the timing of spoken words may vary.

Training: During training, the model learns to predict sequences of characters or words from input video frames. It is trained using a dataset containing pairs of video clips and corresponding transcripts.

Inference: Once trained, the model can take new video clips as input and generate predictions for the spoken words. This allows the model to transcribe spoken language from lip movements in real-time or on recorded video footage.
## Team Details
`Team number` : VH150

| Name    | Email           |
|---------|-----------------|
| D Hemanth Sai | 9921004168@klu.ac.in |
| Ch Venkata Prudhvi| 99210041164@klu.ac.in |
| Yalavarthi Vikas | 99210042092@klu.ac.in |
| M Venkatesh | 99210041220@klu.ac.in |

## Problem statement 
The problem addressed by our lip reading project is the communication barrier faced by individuals with hearing impairments or deafness. This barrier arises from the reliance on auditory cues for communication, which excludes those who cannot hear or have limited hearing ability from fully participating in spoken conversations.

Severity of the Problem:
The severity of this problem is significant, as it impacts the daily lives and social interactions of millions of individuals worldwide. People with hearing impairments often face challenges in various aspects of life, including education, employment, socialization, and access to essential services. This exclusion can lead to feelings of isolation, frustration, and limited opportunities for personal and professional development.

Need for a Solution:
A solution is essential to address the communication gap and improve the quality of life for individuals with hearing impairments. Lip reading offers a promising solution by providing an alternative method of communication that does not rely on auditory cues. By accurately interpreting lip movements and facial expressions, individuals with hearing impairments can better understand spoken language and participate more fully in conversations, social interactions, and everyday activities.

Groups Affected:
The problem of communication barriers due to hearing impairments affects a wide range of people, including:

Individuals born with congenital deafness or hearing loss.
People who have acquired hearing impairments due to illness, injury, or aging.
Individuals with temporary hearing impairments, such as those recovering from surgery or experiencing temporary hearing loss due to ear infections or other medical conditions.
Deaf or hard-of-hearing individuals from diverse cultural and linguistic backgrounds.

## About the project
Real-Time Lip Reading: Our project utilizes deep learning techniques to perform real-time lip reading on video input. By analyzing the movements of the lips and facial expressions, the system transcribes spoken language into text.

Sequence Modeling with CTC: We employ sequence modeling with the Connectionist Temporal Classification (CTC) loss function to train our model. This enables the model to learn temporal dependencies in the input video frames and predict sequences of characters or words without the need for exact alignment.

Accuracy and Robustness: The model is trained on large datasets containing diverse speakers, lighting conditions, and backgrounds to ensure robustness and accuracy in lip reading. This allows the system to perform well in various real-world scenarios.

Multi-Speaker Support: Our system is designed to handle videos with multiple speakers, making it suitable for group conversations and scenarios where there are multiple people speaking simultaneously.

User-Friendly Interface: The project includes a user-friendly interface that allows individuals with hearing impairments to easily interact with the system. The interface may include features such as visual feedback, text display, and customizable settings for improved accessibility.

Customization and Adaptation: Our system can be customized and adapted to different languages, accents, and speaking styles to accommodate the diverse needs of users worldwide. This flexibility ensures inclusivity and accessibility for a broader range of individuals.

Integration with Assistive Technologies: We aim to integrate our lip reading technology with existing assistive technologies, such as hearing aids, cochlear implants, and speech-to-text systems, to enhance their functionality and effectiveness for individuals with hearing impairments.

## Technical implementation 
Data Collection and Preprocessing:

We collected a large dataset of video clips containing diverse speakers, speaking various languages, in different environments, and under varying lighting conditions.
We preprocessed the video data to extract individual frames, normalize lighting conditions, and resize images to a standard size for consistency.
Model Architecture:

We designed a deep learning model architecture suitable for lip reading, typically based on convolutional neural networks (CNNs) and recurrent neural networks (RNNs) or their variants like Long Short-Term Memory (LSTM) or Gated Recurrent Unit (GRU).
The model takes sequences of video frames as input and learns to predict sequences of characters or words corresponding to the spoken language.
Training with CTC Loss:

During training, we employ the CTC loss function, which allows the model to learn to align input sequences with target sequences without the need for exact alignment.
The model learns to associate sequences of video frames with corresponding transcripts, capturing temporal dependencies and patterns in the lip movements.
Validation and Testing:

We split the dataset into training, validation, and testing sets to evaluate the model's performance on unseen data.
We perform extensive validation and testing to ensure that the model generalizes well to diverse speakers, accents, languages, and environmental conditions.
Optimization and Fine-Tuning:

We optimize hyperparameters, such as learning rate, batch size, and network architecture, to improve model performance and convergence speed.
We fine-tune the model on specific tasks or domains to enhance its accuracy and robustness for real-world applications.
Integration and Deployment:

We integrate the trained model into a user-friendly interface or application, allowing individuals with hearing impairments to interact with the system easily.
The lip reading system is deployed on platforms or devices accessible to users, such as smartphones, tablets, or computers, enabling real-time transcription of spoken language into text.

![image](https://github.com/Hemanth-sai-reddy/lip-read-hack-/assets/128202236/d164dd4d-8acb-411c-9fa4-f94054bb52c7)
![image](https://github.com/Hemanth-sai-reddy/lip-read-hack-/assets/128202236/a006dff3-b877-4e23-8b8b-d57d55c08cd6)
![image](https://github.com/Hemanth-sai-reddy/lip-read-hack-/assets/128202236/ccbfa7e1-d070-4841-bf9c-a997df5d50dc)

![image](https://github.com/Hemanth-sai-reddy/lip-read-hack-/assets/128202236/d43fb884-1428-4f34-bb5f-2d853f2aff54)

![image](https://github.com/Hemanth-sai-reddy/lip-read-hack-/assets/128202236/c72e87ba-20d9-44b2-be45-3f221ba2f87d)


## How to run locally 
step 1 open lipnet.iypnb run this ML program 
step 2 open the folder app and run the streamlitapp.py,modelutil.py and utils.py
# What's next ?
Improved Model Performance: Continuously work on enhancing the accuracy and robustness of our lip reading model. This includes exploring advanced architectures, optimization techniques, and larger and more diverse datasets for training.

Multi-Language Support: Extend our system to support multiple languages to cater to a broader audience worldwide. This involves training language-specific models and adapting the system's interface and output to accommodate different languages and writing systems.

Real-Time Translation: Integrate real-time translation capabilities into our lip reading system, allowing it to transcribe spoken language into text and then translate it into the user's preferred language. This would enable seamless communication between individuals speaking different languages.

Accessibility Features: Enhance the accessibility features of our system to better serve individuals with various needs and preferences. This includes customizable visual feedback, text display options, and compatibility with assistive technologies.

User Interface Enhancements: Improve the user interface of our application to make it more intuitive, user-friendly, and engaging. This involves refining the design, layout, and interaction elements to enhance usability and accessibility for all users.

Integration with Assistive Technologies: Collaborate with manufacturers of hearing aids, cochlear implants, and other assistive devices to integrate our lip reading technology seamlessly with their products. This would enhance the functionality and effectiveness of assistive technologies for individuals with hearing impairments.

Community Engagement and Feedback: Engage with the deaf and hard-of-hearing community to gather feedback, insights, and suggestions for improving our system. Actively involve users in the development process to ensure that our technology meets their needs and preferences effectively.

Research and Collaboration: Collaborate with academic institutions, research organizations, and industry partners to advance the state-of-the-art in lip reading technology. This includes participating in collaborative research projects, sharing datasets and benchmarks, and contributing to academic publications and conferences.

Deployment in Real-World Settings: Deploy our lip reading system in real-world settings such as schools, workplaces, and public spaces to evaluate its effectiveness and gather real-world usage data. This would help validate the utility and impact of our technology in practical applications.

## Declaration
We confirm that the project showcased here was either developed entirely during the hackathon or underwent significant updates within the hackathon timeframe. We understand that if any plagiarism from online sources is detected, our project will be disqualified, and our participation in the hackathon will be revoked.
