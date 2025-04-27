# HireMeow - AI-Powered Interview Question Generator

HireMeow is a smart NLP-based application that reads job descriptions and automatically generates relevant interview questions. It is designed to assist recruiters by saving time and help candidates practice job-specific questions.

## About the Project

- Parses job descriptions to extract key skills, tools, and role details.
- Uses Named Entity Recognition (NER) and Dependency Parsing to understand context.
- Generates customized, domain-specific interview questions dynamically.

## Dataset Details

- Scraped job descriptions from leading job portals using **BeautifulSoup**.
- Dataset includes:
  - Job Titles
  - Role Descriptions
  - Skill Requirements
- Preprocessing steps: Tokenization, Stop-word Removal, and Lemmatization.

## Algorithm and Approach

- **Named Entity Recognition (NER)**: Identifies skills, tools, and job roles.
- **Dependency Parsing**: Understands sentence structure and relationships.
- **Rule-Based Template System**: Frames interview questions from parsed data.

## Tech Stack

- **Python**: Backend development.
- **NLTK** and **SpaCy**: NLP tasks.
- **BeautifulSoup**: Web scraping job descriptions.
- **Streamlit**: Interactive UI for users to input job descriptions and view generated questions.

## Evaluation Metrics

- **Human Evaluation**: Manual relevance and clarity checking.
- **BLEU Scores**: Compared AI-generated questions to expert-written ones.
- **Peer Feedback**: Incorporated to fine-tune question generation.

## Demo

- Enter a job description in the app.
- Instantly receive a list of tailored interview questions.

## Future Work

- Add **resume parsing** functionality.
- Enhance domain-specific question generation.
- Improve evaluation metrics with larger datasets and expert reviews.

---

>  [Project Link](https://github.com/madhumithaaprasad/hiremeow.git)
