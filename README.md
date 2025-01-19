# Clone du repository Github
git clone https://github.com/ThibaultDAGUIN/Projet-LLM.git

# Se positionner dans le projet
cd .\Projet-LLM\ 

# Environnement
python -m venv .venv
.venv\Scripts\activate sous Windows # ou source env/bin/activate sinon

# installation des librairies
pip install -r requirements.txt

# Lancer l'application
streamlit run app.py

# Dans l'application, renseigner la clé API de Google
https://aistudio.google.com/
