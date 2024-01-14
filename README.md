## TECHIN510Lab

A personal website for TECHIN 510 Lab 1.

## How to Run

Open the terminal and run the following commands:

```
python -m venv venv
source venv/bin/activate
pip install streamlit
streamlit run app.py
```
Or just go the link : [Personal Portfolio](https://aayush9-techin510-lab1.azurewebsites.net/)

## What's Included

- `app.py`: The main application made with streamlit

## Lessons Learned

- How to make a Web App using streamlit
- How to use requirements.txt to manage Python dependencies
- How to use venv to work on a project with localized python dependencies
- How to use Azure App Service and GitHub actions to deploy the Web App

## Questions / Uncertainties

- How the Azure App services know to setup an venv and install the python dependencies
- How to customize the web page using css
- Why we create .venv and not venv, both of them works only I don't see a venv file in github repo when using just venv (without the dot)
- Do we also need to commit and push the venv file? Will is create any problems when the deployed code will be run by Azure App Service?
