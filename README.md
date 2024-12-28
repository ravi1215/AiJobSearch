<img width="1470" alt="Screenshot 2024-12-28 at 22 56 53" src="https://github.com/user-attachments/assets/7bddca0d-5b74-45d9-bf9a-046df34ddd6a" /># AiJobSearch || Job Scraping & Interview Prep AI

This project is designed to automatically scrape job postings from career pages, analyze the required skills, and match them with a user's portfolio. It also generates relevant interview questions to help users prepare for job interviews.

## Features

- **Job Scraping**: Scrapes job postings from provided URLs (career pages) to extract key details such as the role, experience required, skills, and job description.
- **Skills Analysis**: Matches the extracted job skills with those present in the user's portfolio (CSV file format) to calculate a skill match percentage.
- **Interview Question Generation**: Based on the job description, the system generates a list of relevant interview questions that align with industry standards.
- **Gradio Interface**: A simple web interface for users to interact with the tool and upload their portfolio for analysis.

## Requirements

- Python 3.x
- Google Colab (Recommended for running this project)
- Required Libraries:
  - `langchain_groq`
  - `langchain_community`
  - `langchain_core`
  - `chromadb`
  - `pandas`
  - `gradio`
  - `uuid`

To install the necessary dependencies, run the following:

```bash
pip install langchain-core langchain_groq langchain_community chromadb pandas gradio
```

## How to Use
1. Prepare Your Portfolio CSV: Create a CSV file that contains your resume data. The CSV should have a column labeled Resume with the text of your resume in it.

2. Scrape Job Posting:

3. Provide the URL of the job posting you want to analyze.
   Upload your portfolio CSV file.
   Run the Application

4. Launch the Gradio interface.
   Click the "✨ Analyze Job Posting" button.
   The application will scrape the job posting, analyze the skills required, match them with your portfolio, and generate a set of interview questions.


<img width="1470" alt="Screenshot 2024-12-28 at 22 56 53" src="https://github.com/user-attachments/assets/9614a844-1b9c-4353-a321-32e89451b0da" />
<img width="1470" alt="Screenshot 2024-12-28 at 22 57 16" src="https://github.com/user-attachments/assets/407e51fc-d906-43bd-a98d-f63088181302" />







