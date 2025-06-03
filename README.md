# Emotift-A-Multimodal-Emotion-System-using-fusion-model
This work introduces EmotiFy, a multimodal emotion recognition system based on deep learning 
that employs facial and speech modalities to effectively recognize human emotions. As opposed 
to conventional unimodal approaches which make use of facial expressions or speech alone, 
EmotiFy utilizes both to provide better prediction accuracy and context sensitivity. The 
architecture uses a ResNet50 convolutional neural network for extracting facial images' visual 
features and bi-directional LSTM to process the temporal MFCC features of the speech. Two such 
representations are combined to produce an integrated emotional context, and that is passed on to 
categorize the input to one out of seven categories of emotions: Angry, Disgust, Fear, Happy, Sad, 
Surprise, and Neutral.The model is trained on two established datasets—FER2013 for visual 
emotion and TESS for speech—and is released as an easy-to-use Streamlit web app where users 
can upload audio and image inputs for real-time emotion prediction.The findings show that 
multimodal fusion has a remarkable improvement in emotion recognition performance over 
unimodal models, pointing to the potential of EmotiFy in applications such as human-computer 
interaction, virtual assistants, mental health monitoring, and more.
