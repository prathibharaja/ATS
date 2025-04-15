📄 Candidate Resume Filter
This project helps streamline the hiring process by automatically filtering and ranking candidate resumes based on relevance to predefined job criteria. It uses TF-IDF vectorization to match keywords and skills from resumes (PDFs) against job-specific queries.

🚀 Features

🔍 Automatically reads and processes PDF resumes from Google Drive
🧠 Uses NLP (tokenization, stemming, stopword removal) to clean and analyze text
🧮 Applies TF-IDF to rank resumes against multiple custom queries
📊 Outputs a ranked list of top candidates per skill/query focus

🧰 Tech Stack
Python (Google Colab)
PyPDF2, scikit-learn, nltk, numpy
Google Drive integration for file management
