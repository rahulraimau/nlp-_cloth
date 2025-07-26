🛍️ NLP Capstone Project: Customer Review Analysis – Women’s Clothing E-Commerce
📌 Project Overview
This project analyzes over 23,000 customer reviews for a leading women’s clothing e-commerce platform. The goal is to extract meaningful insights using Natural Language Processing (NLP), understand customer sentiment, and build predictive models for recommendation and rating prediction.

🎯 Business Objectives
🔍 Perform exploratory data analysis (EDA) on customer reviews and demographics.

💬 Conduct text mining to identify frequent words in positive and negative reviews.

🌍 Analyze sentiment trends by category, location, age group, and channel (Web/Mobile).

🤖 Build predictive models to:

Classify customers likely to recommend a product.

Predict product ratings based on review text.

🧠 Perform topic modeling to uncover themes in customer reviews.

📁 Dataset Details
Column Name	Description
Product ID	Unique ID of the product
Category	Product category
Subcategory1	Subcategory level 1
Subcategory2	Subcategory level 2
Location	Customer’s geographic location
Customer Age	Age of the customer
Channel	Purchase channel (Web or Mobile)
Review Title	Short title for the review
Review Text	Full review text
Rating	Rating given by the customer
Recommend Flag	Whether the customer recommends the product (Yes/No)

🧪 Techniques & Tools Used
Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly

NLP: NLTK, spaCy, WordCloud, scikit-learn, TextBlob

Modeling: Logistic Regression, XGBoost, Random Forest

Topic Modeling: LDA (Latent Dirichlet Allocation)

Dashboarding: Streamlit / Plotly Dash (optional)

📊 Key Features
📈 EDA Dashboard: Category-wise review count, age distribution, recommendation trends

🌐 Word Clouds: For positive vs negative reviews

📊 Sentiment Analysis: By channel, location, product category, and age group

🔍 Topic Modeling: Extracting key themes from customer feedback

🧠 Classification Models: Predicting recommendation flag

🎯 Regression Models: Predicting customer rating from review text

🚀 How to Run
Clone the repo

bash
Copy
Edit
git clone https://github.com/rahulraimau/womens-clothing-nlp.git
cd womens-clothing-nlp
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter notebook or Streamlit app

bash
Copy
Edit
jupyter notebook
# or
streamlit run app.py
📌 Sample Visualizations
WordCloud of Top Positive/Negative Words

Sentiment by Age Group

Top Recommended Categories

Topic Clusters per Product Type

📦 Outputs
sentiment_model.joblib: Trained sentiment classification model

rating_predictor.pkl: Regression model for rating prediction

lda_model.pkl: Topic model with top keywords

final_dashboard.html: Interactive dashboard output (optional)

👤 Author
Rahul Rai
📧 rahulraimau5@gmail.com
🔗 GitHub | Kaggle | HackerRank

