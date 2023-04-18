# Ground Truthing GPT3.5
Repository to hold the code for our UMICH SIADS Master of Applied Data Science Capstone project, with a focus on fact checking OpenAI's GPT-3.

![team_ambitious_project_poster pptx (1)](https://user-images.githubusercontent.com/36832027/232674649-8dc6891a-115c-48ba-a4af-a7bd10805f23.png)

## Setup
```pip install -r requirements.txt``` 

Will install:
- **Pandas** (Operate on tabular data)
- **TQDM** (prints progress bars)
- **Wikidata** (structured queries to Wikidata; punches under it's weight, we're also firing off SparQL queries with the Python `Requests` built-in package)
- **OpenAI** (GPT-3 interface, among other things)
- **Seaborn** (Visualization Package)
- **Plotly** (Visualization Package)
- **python-dotenv** (Secrets management)
- Specific versions of Python 3 Built-ins (Requests, matplotlib)


## Data
- Check the `set_subset_responses_complete.csv` for the "set subset" results; more to follow as we continue to hit the OpenAI API
