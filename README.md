### Swasthya: Transformative Mental Health Support Chatbot

#### Overview

Swasthya is a groundbreaking project that aims to address the escalating prevalence of mental health issues in today's society. The project focuses on creating a conversational agent dedicated to providing vital mental health support. By leveraging advanced machine learning algorithms, natural language processing, and text-to-speech functionality, Swasthya offers personalized and stigma-free assistance to individuals in need.

#### Features
Conversational Engagement: Engages users in meaningful conversations to understand their unique mental health needs.
Resource Provision: Provides a variety of resources, including coping strategies, relaxation techniques, and links to relevant mental health materials.
Tailored Support: Utilizes sentiment analysis, natural language processing, and data analytics to tailor support to each individual, enhancing effectiveness.
Text-to-Speech Communication: Enables the chatbot to audibly communicate with users for an enhanced user experience.

#### How to Use

##### Phase 1: Running the ML Model

Import Libraries: Ensure you have the required libraries for natural language processing, speech recognition, and machine learning. Install them using pip install -r requirements.txt.

Initialize Text-to-Speech Engine: Set up the text-to-speech engine using pyttsx3 with voice selection.

Load Intent Data: Load intent data from the intents.json file for training the chatbot.

Prepare Training Data: Process intent data to create training and output sets for the neural network.

Define Neural Network Model: Design a neural network model using tflearn with input, hidden, and output layers.

Train the Model: Train the model on the prepared data, adjusting parameters for optimal performance.

Implement Bag of Words: Create a function to convert sentences into a "bag of words" representation.

Facilitate Conversation: Develop a chat() function for user interaction with the trained chatbot.

###### In short Run the ML model and run main.py 

##### Phase 2: Automated Support using Gemini Pro AI

Install Gemini Pro AI: Follow the instructions to install Gemini Pro AI, a powerful tool for automated mental health support.

Run the Python File: Execute the Python file to initiate the chatbot and provide users with automated mental health assistance.

#### Challenges and Accomplishments
During development, challenges included data preprocessing, neural network fine-tuning, text-to-speech configuration, and seamless user interaction. Accomplishments include successful model training, integration of natural language processing, and robust error handling.

#### Learning Experiences
The project provided valuable learning experiences in machine learning, natural language processing, text-to-speech integration, error handling, and user interface design.

#### What's Next for Swasthya

Future enhancements include advanced conversation handling, expanded intent data coverage, sentiment analysis for empathetic responses, voice recognition, multi-language support, personalization features, integration of external resources, deployment on a platform, continuous monitoring, and prioritizing security and privacy.

Nurturing Mental Wellness Together: Swasthya represents a comprehensive step towards transforming mental health care into an accessible, stigma-free, and efficient system for those in need.