Step 1: Checkout above files. <br>
Step 2: Create .env file with below KEY and value <br>
    LANGCHAIN_TRACING_V2=true <br>
    LANGCHAIN_ENDPOINT=https://api.smith.langchain.com <br>
    LANGCHAIN_API_KEY=lsv2_pt_13ffd4b0531f4a31ba8caXXXXXXXXXXX <br>
    LANGCHAIN_PROJECT=project_name <br>
    MISTRAL_API_KEY=4uk7S6ZZI7TuaaLBpYXXXXXXXXX <br>
    TAVILY_API_KEY=tvly-BLjVCCo5v80OCjVxXXXXXXXXXXX <br>
    GROQ_API_KEY=gsk_aTchAhy0kM0yGTDYTWrYWGdyb3FY30zTXXXXXXXXXX <br>
 <br>
Step 3: Open terminal where you checkout above code <br>
source ~/.bash_profile <br>
poetry shell <br>
poetry run jupyter notebook <br>
 <br>
 <br>
Step 4: If required, To add any new library, open another terminal on same folder <br>
source ~/.bash_profile <br>
poetry shell <br>
poetry add library name <br>
 <br>
** How to setup tracing using Langchain Smith **  <br>
Add three in .env file <br>
LANGCHAIN_TRACING_V2=true <br>
LANGCHAIN_ENDPOINT=https://api.smith.langchain.com <br>
LANGCHAIN_API_KEY=lsv2_pt_13ffd4b0531f4a31ba8caXXXXXXXXXXX <br>
LANGCHAIN_PROJECT=demo_project <br>
 <br>
After using poetry shell, add this library <br>
poetry add langsmith <br>
 <br>
from dotenv import load_dotenv <br>
import os <br>
load_dotenv() <br>
 <br>
Re run the code from start including load_dotenv() to update env key value in running code. <br>
 <br>
Go to chrome (Safar some time does not support)  https://smith.langchain.com/ use gmail  <br>
 <br>
You will notice new project ”demo_project” <br>
 <br>

