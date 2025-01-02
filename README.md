Step 1: Checkout above files. <br>
Step 2: Create .env file with below KEY and value
    LANGCHAIN_TRACING_V2=true
    LANGCHAIN_ENDPOINT=https://api.smith.langchain.com
    LANGCHAIN_API_KEY=lsv2_pt_13ffd4b0531f4a31ba8caXXXXXXXXXXX
    LANGCHAIN_PROJECT=project_name
    MISTRAL_API_KEY=4uk7S6ZZI7TuaaLBpYXXXXXXXXX
    TAVILY_API_KEY=tvly-BLjVCCo5v80OCjVxXXXXXXXXXXX
    GROQ_API_KEY=gsk_aTchAhy0kM0yGTDYTWrYWGdyb3FY30zTXXXXXXXXXX

Step 3: Open terminal where you checkout above code
source ~/.bash_profile
poetry shell
poetry run jupyter notebook


Step 4: If required, To add any new library, open another terminal on same folder
source ~/.bash_profile
poetry shell
poetry add library name

** How to setup tracing using Langchain Smith ** 
Add three in .env file
LANGCHAIN_TRACING_V2=true
LANGCHAIN_ENDPOINT=https://api.smith.langchain.com
LANGCHAIN_API_KEY=lsv2_pt_13ffd4b0531f4a31ba8caXXXXXXXXXXX
LANGCHAIN_PROJECT=demo_project

After using poetry shell, add this library
poetry add langsmith

from dotenv import load_dotenv
import os
load_dotenv()

Re run the code from start including load_dotenv() to update env key value in running code.

Go to chrome (Safar some time does not support)  https://smith.langchain.com/ use gmail 

You will notice new project ”demo_project”

