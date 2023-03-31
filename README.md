# SIADS-Capstone
Repository to hold the code for the UMICH SIADS Master of Applied Data Science Capstone project, with a focus on fact checking OpenAI's GPT-3.

## Setup
```pip install -r requirements.txt``` 

Will install:
- **Pandas** (Operate on tabular data)
- **TQDM** (prints progress bars)
- **Wikidata** (structured queries to Wikidata; punches under it's weight, we're also firing off SparQL queries with the Python `Requests` built-in package)
- **OpenAI** (GPT-3 interface, among other things)

## Data
- Check the `Set_Subset_Responses_60%_done.csv` for the interim results; more to follow as we continue to hit the OpenAI API
