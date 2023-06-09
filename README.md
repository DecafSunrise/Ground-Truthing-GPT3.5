# Ground Truthing GPT3.5
Repository to hold the code for our UMICH SIADS Master of Applied Data Science Capstone project, with a focus on fact checking OpenAI's GPT-3.

![team_ambitious_project_poster pptx (1)](https://user-images.githubusercontent.com/36832027/232674649-8dc6891a-115c-48ba-a4af-a7bd10805f23.png)

## Setup
1. Git clone this repository
2. Create a new Python or Anaconda environment for this project
3. ```pip install -r requirements.txt``` 

Will install:
- **Pandas** (Operate on tabular data)
- **TQDM** (prints progress bars)
- **Wikidata** (structured queries to Wikidata; we're also firing off SparQL queries with the Python `Requests` built-in package)
- **OpenAI** (GPT-3 interface, among other things)
- **Seaborn** (Visualization Package)
- **Plotly** (Visualization Package)
- **python-dotenv** (Secrets management)
- Specific versions of Python 3 Built-ins (Requests, matplotlib)

## Running the code
To replicate this analysis, open the Notebooks folder, and step through the numbered notebooks. The notebooks are numbered because certain stages build upon data retrieved in earlier stages, with exploratory data analysis (EDA) separated from long-running data gathering code.

## Licenses
- Code wholly generated by this team is released under the CC-0 License ("[Universal Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)")
- Other code used in this project released under a specific license can be reviewed in the `LICENSE` folder.

## Data Access Statement
- Taxonomic Wikidata data was used in the creation of the prompts for this project. The data is available under CC-0 license, as per the [Wikidata Data Access Policy](https://www.wikidata.org/wiki/Wikidata:Data_access#Using_Wikidata's_data).
- OpenAI GPT 3.5 was used in the creation of the responses. The use thereof is in accordance with the [OpenAI Sharing & Publication Policy](https://openai.com/policies/sharing-publication-policy). 

![image](https://user-images.githubusercontent.com/36832027/232679298-00804f1d-d47d-4acb-8566-02bb12cd15a4.png)
