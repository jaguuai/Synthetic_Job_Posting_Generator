# Job Description Generator

## Project Overview
This project utilizes an AI-based **Job Description Generator** to dynamically create job descriptions. The goal is to generate short, effective, and professional job descriptions based on a selected role, industry, and experience level. Users can quickly access job descriptions tailored to specific job titles.

## Features
- **Dynamic Job Descriptions:** Users can generate job descriptions based on role, industry, and experience level.
- **Customizable:** The generator can produce customized job descriptions with specific parameters.
- **AI-Powered:** It leverages open-source models such as GPT-2 or DistilGPT-2 for generating job descriptions in natural language.
- **Concise and Professional:** Job descriptions are generated with a focus on key responsibilities, keeping them under 50 words.

## Installation
The project is written in Python and requires the following dependencies:

### Required Dependencies
- **transformers** (HuggingFace library)
- **torch** (PyTorch)
- **pandas**
- **Faker** (Fake data generation)
    ```
### User Inputs
- **Role:** The user selects a specific job role (e.g., "Developer", "Data Analyst").
- **Industry:** The generated job descriptions will be based on the selected industry (e.g., "Tech", "Finance").
- **Experience Level:** The model adjusts the descriptions based on the chosen experience level, such as "Junior", "Mid-Level", or "Senior".

## Model and Technology
This project uses HuggingFace's **DistilGPT-2**  model, which are optimized for natural language generation. These models are employed to quickly and efficiently generate job descriptions.

## Advanced Features
- **Customizable Prompts:** Users can create custom prompts (starting text) to make job descriptions more unique.
- **Randomized Output:** Each time the generator is run, it produces different job descriptions, ensuring variety.

