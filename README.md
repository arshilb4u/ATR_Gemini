
# ATR System Gemini Pro

This is a Application Tracking System(ATR) work on the Gemini Pro LLM model this application uses PyPDF2 for pdf extraction and also we have created a unique prompt which can take the JD description to get below points

1) JD Match percentage
2) Key points which are missing in resume
3) Profile summary



## How to use this Repo

create a virtual environment

you can create virtual env by 3 methods mentioned below

```bash
 virtualenv venv
 python -m venv venv
 conda create -n envname python=x.x anaconda
```
Install requirement.txt
After activiting the Virtual environment

 ```bash
 pip install -r requirements.txt
```

crete a .env file to store gimini API key

```bash
 GOOGLE_API_KEY= " " # mention API key here
```

Run streamlit app
```bash
 streamlit run app.py
```
