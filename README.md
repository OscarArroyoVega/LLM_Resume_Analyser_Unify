# LLM-Resume-Analyser-using-Unify 
#### ** This repository is the main development repository for the LLM Resume Analyser. Originally forked from a repository with just a default GitHub README file, all development has been done here.

[Demo](https://github.com/OscarArroyoVega/LLM_Resume_Analyser_Unify/assets/103512255/5cfbb620-e6e1-4cbb-b619-1b087e0b379b) 

<video width="640" height="480" autoplay>
  <source src="[Demo](https://github.com/OscarArroyoVega/LLM_Resume_Analyser_Unify/assets/103512255/5cfbb620-e6e1-4cbb-b619-1b087e0b379b)" type="video/mp4">
Your browser does not support the video tag.
</video>

LLM Resume Analyser: A Comprehensive LLM-Powered Demo App

The LLM Resume Analyser demonstrates the transformative potential of large language models (LLMs) in recruitment, connecting job applicants with employers or recruiters.

Key Features:

Resume Analysis: Extracts and analyzes key skills and qualifications from resumes.
Matching Score: Computes a match score for resumes against job descriptions.
Semantic Matching: Uses the Unify API to semantically analyze and match resumes with job descriptions using multiple LLMs.
Distributed Skills Match: Highlights how job requirements are represented across all applicant skills and experiences.
Suggestions and Resume Improvement: Provides suggestions for resume enhancement and compares the original with the improved version.
Alternative Job Titles: Suggests other job titles that match the resume.
Custom Model Utilization: Allows dynamic routing and integration of various models under OpenAI standards.
The app leverages the Unify API for dynamic routing and access to various models, ensuring precise and comprehensive recruitment analysis.

## Tech Stack
Streamlit: Used for creating the web application interface that is intuitive and interactive.

Unify AI: Provides the backend LLMs that power the interactions within the application. Unify's API is utilized to send prompts to the LLMs and receive their responses in real-time.

Langchain: LangChain is a powerful framework designed for building applications that integrate with large language models (LLMs), enabling complex interactions and workflows by chaining together various components like prompts, LLMs, and data sources




## Introduction
 
You find more model/provider information in the [Unify benchmark interface](https://unify.ai/hub).

## Usage:
1. Visit the application: [LLM Resume Analyser](https://ai-llm-resume-analyser.streamlit.app/)
2. Input your Unify API Key. If you don’t have one yet, log in to the [Unify Console](https://console.unify.ai/) to get yours.
3. Select the model and provider of your choice
4. Upload your document(s) and click the Submit button
5. Enter your job description and job title
6. Gain insights on Resume match with the job offer and on how to improve your Resume

## Repository and Deployment
The repository [link1](https://github.com/OscarArroyoVega/LLM_Resume_Analyser_Unify).

To run the application locally, follow these steps:
1. Clone the repository to your local machine.
```bash
git clone https://github.com/Sanjay8602/LLM-Resume-Analyser-using-Unify
```
2. Set up your virtual environment and install the dependencies from `requirements.txt`:
```bash
python -m venv .venv    # create virtual environment 
```
```bash
source .venv/bin/activate   # on Windows use .venv\Scripts\activate.bat
```
```bash
pip install -r requirements.txt
```
3. Run app.py from Streamlit module 

```bash
python -m streamlit run analyser.py
```

## Contributors

|       Name       |                  GitHub Profile                 |
|------------------|-------------------------------------------------|
| OscarArroyoVega  | [OscarAV](https://github.com/OscarArroyoVega)   |
| Sanjay Suthar    | [Sanjay0806](https://github.com/Sanjay8602)     |
| Mayssa Rekik     | [Mayssa Rekik](https://github.com/iammayssa)    |
| Jeya Balang      | [Jeyabalang](https://github.com/jeyabalang)     |
