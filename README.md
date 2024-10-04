# Membuat virtual environment menggunakan conda
```
conda create --name main-ds python=3.12.16
conda activate main-ds
pip install -r requirements.txt
mkdir submission
cd submission
```

# Membuat virtual environment menggunakan pipenv
```
mkdir submission
cd submission
pipenv install
pipenv shell
pip install -r requirements.txt
```

# Run steamlit app
```
streamlit run dashboard.py
```