SHL Assessment Recommendation Engine
This is a simple content-based recommendation system built using Python and Streamlit. It helps users find the most relevant SHL assessments based on their input, leveraging SHL's product catalog and semantic search techniques.

🔍 Features
🔎 Search for SHL assessments based on job role, skills, or keywords

🤖 Recommends top relevant assessments using semantic similarity

⚡ Powered by Sentence Transformers for improved results

🧾 Clean, minimal UI with Streamlit

🛠️ Tech Stack
Python

Streamlit

Sentence Transformers

scikit-learn

Pandas

BeautifulSoup

Requests

🚀 How to Run
Follow these steps to run the project locally:

1. Clone the Repository
git clone https://github.com/lawkeshdhurve/shl.git

2. Create and Activate Virtual Environment
On Windows:
python -m venv venv
venv\Scripts\activate

On macOS/Linux:
python3 -m venv venv
source venv/bin/activate

3. Install Dependencies
Make sure you have a requirements.txt file in the root directory, then run:
pip install -r requirements.txt

Alternatively, you can manually install dependencies:
pip install streamlit sentence-transformers pandas scikit-learn beautifulsoup4 requests

4. Run the App
python -m streamlit run shl_recommender.py

6. Open in Browser
Visit: http://localhost:8501

📬 Feedback or Contributions
Feel free to fork the repository, raise issues, or submit pull requests to improve the project!
