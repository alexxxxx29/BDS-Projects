# Kaggle Competitions
I participated in four Kaggle competitions in a group of three students, competing with another 15 groups.

## Competition 1: Personality Profiling of YouTube Bloggers
- Built a classifier that predicts five personality trait scores of YouTube bloggers. The dataset includes speech transcripts of YouTubers' blogs, gender information, as well as audiovisual features
- *Feature engineering*: sentiment scores based on Afinn and NRC lexicons, a proportion of long words, an average sentence length, a proportion of long sentences, and a stop word count. Already available audiovisual features and gender were added to computed features
- *Fitted models*: stepwise regressions with second-order polynomial terms and interactions

## Competition 2: Physical Activity Recognition
- Built a classifier that recognizes different types of physical activity (e.g., sitting, standing) and postural transitions (e.g., sit-to-stand) from signals measured by the accelerometer and gyroscope in a smartphone, which both measure aspects of movement and orientation
- *Feature engineering*: statistical features (e.g., skewness, kurtosis entropy), time domain features (e.g., lagged correlations), and frequency domain features (e.g., spectral peak, spectral standard deviation). Removed near zero variance features, highly correlated features, features that form linear combinations
- *Fitted models*: linear discriminant analysis, quadratic discriminant analysis, k-nearest neighbours, k-nearest neighbours with standardized features (best performance), and Naive Bayes method

## Competition 3: Amazon Customer Reviews
- Built a classifier that predicts the probability of customer satisfaction from textual reviews of products sold on Amazon.com
- *Feature engineering*: token counts, total number of words per review, term frequency-inverse document frequency, counts of exclamation and question marks per review, and negation counts per review. All features, except for counts of exclamation and question marks per review, were calculated for both unigrams and bigrams
- *Fitted models*: lasso regression (best performance) and ridge regression. Predictive performance measures: area under the ROC curve, accuracy, sensitivity, and specificity

## Competition 4: Facial Expression Recognition
- Built an algorithm that classifies images of faces into the emotion being expressed
- *Feature engineering*: raw pixels (we compared full image size vs 2x2 pooled image size), spectral features from raw pixels, and histogram features from the horizontal, vertical, and diagonal edges. Removed near zero variance features, highly correlated features, and features that form linear combinations
- *Fitted models*: classification tree, random forest, k-nearest neighbours, boosted tree, multinomial regression with lasso and ridge regularization, support vector machine (best performance), as well as linear discriminant analysis with PCA preprocessing

# Deep Learning Project: Sarcasm Detection in News Headlines
BERT, a transformer model, excels in text analysis using bidirectional context, parallelization, attention mechanisms, and pre-trained representations. Yet, evidence suggests bidirectional LSTM may outperform BERT on smaller datasets. For that reason, we split the data into short versus long news headlines, and conducted a comparative analysis of LSTM and BERT for sarcasm detection using four models: BERT trained on short headlines, BERT trained on long headlines, LSTM trained on short headlines, and LSTM trained on long headlines.

# External Projects
## Consultancy Project | Company: eelloo 
- Went through the CRISP-DM cycle for data mining, including a series of consultancy sessions with the client 
- Addressed client’s inquiries regarding the characteristics of returning users and non-returning users on the Talent Development platform 
- Learned how to handle sensitive data and implemented security measure

## Software Usage Analytics | Company: Oefenweb.nl 
- Extracted project-specific data from a rich relational database in SQL server
- Investigated variations in the use of a Math Garden program between high-performing and low-performing schools by developing a customized performance metric  
- Gained experience in working with the online RStudio environment 
- Acquired skills in creating interactive dashboards using Tableau

## Forecasting the Electrical Vehicle Market | Company: Vandebron 
- Addressed client’s inquiries regarding the future development of the EV market in NL and its impact on the company’s customer base growth  
- Mastered the creation of dynamic geographical maps in GIF format to illustrate the evolution of key metrics across various provinces in NL 
- Enhanced proficiency in using GitHub for project collaboration 
- Maintained consistent communication with stakeholders through weekly meetings   
