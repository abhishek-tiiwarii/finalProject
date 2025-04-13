# finalProject
This is Project Cura. Cura is an intelligent chatbot built on GPT-4O-mini, fine-tuned with Gale's Encyclopedia of Medicine, and powered by Pinecone for efficient database search. It provides accurate, reliable answers to medical queries, making healthcare knowledge accessible, fast, and user-friendly.

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/abhishek-tiiwarii/finalProject.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n your_preffered_environment_name python=3.10 -y
```

```bash
conda activate your_preffered_environment_name
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone & OpenAI credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# run the following command to store the embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command to run the application
python app.py
```

Now,
```bash
open up localhost:8080
```