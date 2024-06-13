# AudioProficiency
This research project focuses on the development of a deep learning model for assessing language proficiency through the analysis of spoken responses.Assessing language proficiency is a critical aspect of language learning and education. Traditional methods of evaluating language skills often rely on manual assessments, which can be time-consuming, subjective, and prone to human biases. To address these challenges, we propose a novel deep learning model for voice-based proficiency assessment that leverages advanced techniques in neural networks and natural language processing to analyze spoken responses and provide a comprehensive evaluation of pronunciation, fluency, and vocabulary usage. The proposed deep learning model aims to automate the assessment process by capturing and analyzing various linguistic features present in spoken language samples. These features include phonetic accuracy, intonation, rhythm, and lexical richness. By considering multiple aspects of spoken language, the model aims to provide a holistic assessment of a student's language proficiency, enabling a more accurate and comprehensive understanding of their language skills.
The dataset is divided into 2 parts, one for audio processing and the other for audio generated text evaluation. 

Dataset is taken from hewlett foundation competition for essay scoring
“You are provided access to hand scored essays, so that you can build, train and test scoring engines against a wide field of competitors.  Your success depends upon how closely you can deliver scores to those of human expert graders.  While we believe that these financial incentives are important, we also intend to introduce top performers both to leading vendors in the industry and/or an established base of interested buyers.  Hewlett is opening the field of automated student assessment to you.  We want to induce a breakthrough that is both personally satisfying and game-changing for improving public education.”



Audio Dataset: The audio dataset contains over 100 hours of recorded audio in wave format. The dataset will be used to train and process the the audio model and generate the text data from the audio files.

Essay Dataset: A dataset of several evaluated essays has been used to train the model. This will help model to score the text generated from audio files to be evaluated.
Purpose:
The primary purpose of this dataset is automated essay scoring.
 It serves as training data for LSTM (Long Short-Term Memory) models.
Contents:
The dataset contains evaluated essays.
Each essay is associated with a domain score.
Data Format:
The essays are stored in a tab-separated values (TSV) file.
Columns include:
Essay: The actual essay content.
Domain1_score: The assigned score for the essay.
