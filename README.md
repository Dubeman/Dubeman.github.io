# Data Science Graduate

#### Technical Skills: Python, SQL, JMP, Mathematica
[Resume]([https://drive.google.com/drive/u/0/my-drive](https://drive.google.com/file/d/1mVZKnLeARw0FJoylbgCWR2qhq2fcQEHS/view?usp=sharing))

## Education
					       		
- M.S., Data Science	| Rochester Institute of Technology , N.Y. (_August 2023_ - _Present_)	 			        		
- B.S., Data Science and Engineering  | Indian Institute of Science Education and Research, Bhopal (_May 2023_)

## Bachelor's Thesis

[Thesis blog](https://medium.com/@dubemanas10)

### TELI: Teacher-Ensemble distillation based learned Label Interpolation

![TELI methodology](/assets/img/TELI.jpeg)

Imagine a neural network based learning strategy that combines the wisdom of multiple teacher models, dynamically adjusts its learning approach, and enriches the model's understanding of data relationships. Enter TELI.

#### Knowledge Distillation
The model learns not just from labeled data but distills the collective knowledge of a group of teacher models. These teachers, each a specialist in its own right, contribute nuanced insights to the learning process.

#### Meta Learning 
Using meta-learning, the model dynamically tunes its mixing ratio (lambda) between teacher predictions. This adaptability ensures that the model becomes more than a learner; it becomes an agile decision-maker, adjusting to the complexity of different datasets.

#### Teacher Ensemble
Ensembling is the power of collaboration. TELI brings together an ensemble of teacher models, each providing a unique perspective on the data. The collective intelligence of this ensemble strengthens the model's grasp of intricate patterns.

#### Why TELI ?

##### Improved Generalization
TELI doesn't just memorize examples; it learns the relationships between classes. This results in a model that not only performs well on labeled data but excels in making accurate predictions on unseen, unlabeled data.

##### Meta Learning Adaptability 
The ability to dynamically adjust the mixing ratio means the model adapts to the idiosyncrasies of each dataset. No more one-size-fits-all; TELI tailors its approach for optimal performance.

##### Enriched Knowledge Transfer
Knowledge distillation takes center stage, transferring the distilled wisdom of teacher models to the student. The ensemble of teachers ensures a diverse range of knowledge is at the model's disposal.

##### Achievements 

- Utilized heavyweight and lightweight neural networks (e.g., VGG-16, ResNet-50, Masked Auto Encoders).
- Performed GradCam analysis to optimize model interpretability.
- Improved the robustness of the semi-supervised student model with Stochastic Data Augmentation by 2%.
- Utilized custom data loaders for dynamic data allocation and complete GPU utilization.
- Boosted the student model performance by 12 % by utilizing knowledge distillation.
- Designed an interactive UI for streamlining model training, testing, and evaluation.
- Presented the research at my university's Data science board to their great acclaim.

## Projects

### Advanced NLP for Safer Online Communities: A Multi-label classification problem

In pursuit of fostering safer online spaces, I applied  Natural Language Processing (NLP) techniques to detect Patronizing and Condescending Language (PCL) on Twitter using the _Dont Patronize Me!_ (Perez et. al 2020) dataset. This content moderation challenge, framed as a SemEval problem, demanded a nuanced approach.

#### Diverse Approaches
I embraced both Statistical and Deep NLP techniques to address the intricacies of PCL detection comprehensively.

#### Deep Learning Architectures 
My experimentation included renowned models such as bI-LSTM, RNN, BERT, Feed-forward NN, Stacked RNN, Stacked LSTM, and RoBERTa transformer (pre-trained and trained from scratch) using TensorFlow. Each architecture brought unique strengths to the task.

#### Word Embeddings for Context 
Using word embeddings, specifically GloVe, to enhance content representation and capture the semantic nuances critical for accurate PCL detection.

#### Hyperparameter Tuning
Streamlining the models for stability was achieved through meticulous hyperparameter tuning. This not only improved accuracy but also optimized resource utilization.

#### Multifaceted Analysis
Recognizing the multifactorial nature of the challenge, I experimented with various preprocessing techniques—Stemming, Lemmatization, Word2Vec—analyzing their impact on overall model performance.

### Twitter Sentiment Analysis to gauge Vaccination reception during COVID-19

![Twitter Vaccination Heatmap](/assets/img/heatmap.jpeg)

In the dynamic landscape of the COVID-19 pandemic, we undertook a Twitter Sentiment Analysis project to gauge public sentiment regarding vaccinations during December 2021. Leveraging the Twitter REST API, our goal was to distill valuable insights for health authorities, aiding vaccination campaigns and safety measures.

#### Insights from Tweets:

Gathered and cleaned Twitter data to grasp public sentiment around COVID-19 vaccinations.
Applied machine learning models (Logistic Regression, Naive Bayes, SVMs) to quantify sentiments.
Mapped sentiment trends on interactive maps, offering health authorities a geographical view of public feelings.

#### Actionable Findings:

Extracted practical insights to guide vaccination campaigns and enhance safety measures.
Health authorities can use sentiment analysis to adapt strategies based on real-time public reactions.

#### User-Friendly Maps:

Simplified complex sentiment data into easy-to-understand maps for the public.
These intuitive visuals made intricate information accessible to a wider audience.
















