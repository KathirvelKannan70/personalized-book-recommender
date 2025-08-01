📚 Personalized Book Recommender System
A Streamlit-based web application that provides personalized book recommendations using collaborative filtering.
Users can explore Top 50 popular books, get similar book recommendations, and view the dataset used.

🚀 Features
Top 50 Books – Quickly view the most popular books

Personalized Recommendations – Get similar books for your selected title

Interactive Web App – Built using Streamlit

Dataset Preview – Explore the books dataset used in the project

📸 Screenshot
<p align="center"> <img src="screenshot.png" width="600"> </p>
🗂 Project Structure
nginx
Copy
Edit
Personalized Book Recommender/
│
├── app.py                    # Main Streamlit app
├── books.pkl                 # Book details in pickle format
├── popular.pkl               # Precomputed top 50 popular books
├── pt.pkl                    # Pivot table for recommendations
├── similarity_scores.pkl     # Precomputed similarity scores
│
├── Code-3_page.py            # Experimental app script
├── code.py                   # Supporting Python code
├── Recommender.ipynb         # Notebook for recommendation model
├── Final_code b2.ipynb       # Final Jupyter notebook
│
├── Data/                     # Original datasets
│   ├── Books.csv             # Books metadata
│   ├── Ratings.csv           # User ratings
│   └── Users.csv             # User info
│
├── Data Dictionary.md        # Data dictionary for datasets
├── notes.md                  # Development notes
├── slides.md                 # Project presentation slides
└── README.md                 # Project documentation
⚙️ Installation
1️⃣ Clone the repository

bash
Copy
Edit
git clone https://github.com/KathirvelKannan70/personalized-book-recommender.git
cd personalized-book-recommender
2️⃣ Install dependencies

bash
Copy
Edit
python -m pip install -r requirements.txt
If no requirements.txt is provided:

bash
Copy
Edit
python -m pip install streamlit pandas numpy pickle-mixin
▶️ Usage
Navigate to the project folder:

bash
Copy
Edit
cd "C:\Personalized Book Recommender"
Run the Streamlit app:

bash
Copy
Edit
python -m streamlit run app.py
Open the local URL in your browser (usually http://localhost:8501)

📊 Dataset
Books.csv – Book details (ISBN, title, author, year, publisher)

Ratings.csv – User ratings for books

Users.csv – User demographic details

The .pkl files store preprocessed data and similarity scores to make the app faster.

🧠 How It Works
Collaborative Filtering generates book recommendations based on user preferences.

Precomputed Similarity matrix allows quick recommendation lookup.

Streamlit Web App provides an interactive interface for end-users.

👨‍💻 Author
Developed by Kathirvel Kannan
Project for academic/demo purposes.

