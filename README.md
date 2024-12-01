# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

# Copy the repo to Github:
### I first copied the repository to my Github account using the “Use This Template” button and specified myself as the owner.
When I opened VS Code I shift + control + P to open a new session. Then I clicked on Terminal to open a terminal below and also selected GitBash because I was going to need it. So now I have a Powershell and GitBash windows open on the bottom of my page.
# Clone down the repo to local machine:
### I cloned down the repo to my local machine in VS Code by making a copy from my repo and opening VS Code and clicking on Git: Clone and pasting in the web address from my Github account.
I made markdown and code boxes where applicable. I made the markdown boxes for the question titles.

### Set up your virtual environment in VS Code or Juypter Notebook
### I set up my virtual environment in powershell and GitBash terminals.
 You can add the following to your requirements.txt and it will automatically add those to your environment.
 (Ex: requests
spacy
spacytextblob
jupyter
matplotlib
numpy
Beautifulsoup4
Collections)

#### In GitBash
$ python -m venv .env
$ .env/Scripts/activate
$ pip install -U pip setuptools wheel
$ pip install -U spacy
$ python -m spacy download en_core_web_sm
$ pip install -r requirements.txt
$ pip install spacy
$ pip install spacytextblob


## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt
