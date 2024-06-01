# Mission: Gemini Quizify

## Overview

Welcome to the Gemini Quizify! This repository leverages the power of Google Gemini, a large language model AI, to generate quizzes aimed at making studying more efficient and effective.

## Table of Contents

- [Mission: AI-Powered Quiz Generator](#mission-ai-powered-quiz-generator)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Project Structure](#project-structure)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contact](#contact)

## Project Structure
```plaintext
.
├── LICENSE
├── README.md
├── authentication.json
├── main.py
├── project-structure.txt
├── requirements.txt
└── tasks
    ├── __init__.py
    ├── task_10
    │   └── task_10.py
    ├── task_3
    │   └── task_3.py
    ├── task_4
    │   └── task_4.py
    ├── task_5
    │   └── task_5.py
    ├── task_6
    │   └── task_6.py
    ├── task_7
    │   └── task_7.py
    ├── task_8
    │   └── task_8.py
    └── task_9
        └── task_9.py

10 directories, 15 files

```

10 directories, 15 files

## Features

- Generate quizzes based on given topic and number of questions
- Process uploaded pdf's and create ChromaDB for quiz generation
- Efficiently review and assess knowledge through AI-generated questions
- Support for multiple-choice

## Installation

To get started with the Mission project, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/ty1erz/mission-quizify.git
    cd mission
    ```

2. **Set up environment and Install dependencies:**
    ```sh
    python3 -m venv env
    source env/bin/activate
    pip install -r requirements.txt
    ```

3. **Google Cloud Authentication:**
   - Create a project in your Google Cloud, create a service account and download the key `authentication.json` of the serveice account.
   - Place your Google Credentials `authentication.json` in the root directory.
   - Authenticate your credentials for the project
   ```sh
   export GOOGLE_APPLICATION_CREDENTIALS="/path/to/your/authentication.json"
   gcloud auth application-default login
   ```

## Usage

**Run the quiz generator:**<br>
    ```sh
    cd task/task_10
    streamlit run task_10.py
    ```
## Acknowledgments
- Radical AI for the application fundation and tutorials.
- Google Cloud for providing the powerful AI models.
- Streamlit for the intuitive app framework.
## Contact

For questions, suggestions, or feedback, please contact Tianyue Tyler Zhang at ovotylerz@gmail.com.

---

Thank you for using the Mission project! Happy studying!
