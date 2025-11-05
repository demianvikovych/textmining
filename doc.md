python -m venv .venv
source .venv/Scripts/activate

pip install -r requirements.txt

python
> import nltk
> nltk.download("stopwords")
> nltk.download("punkt_tab")

git config --global user.name "KostiaUek"
git config --global user.email "146982394+KostiaUek@users.noreply.github.com"

pip freeze > requirements.txt