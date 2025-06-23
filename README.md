# Generative AI Introduction 2024 - Course Assignments & Projects

This repository contains materials and solutions for the "Generative AI Introduction 2024" course.

## Course Information
  * **Course Website:** [https://speech.ee.ntu.edu.tw/\~hylee/genai/2024-spring.php](https://speech.ee.ntu.edu.tw/~hylee/genai/2024-spring.php)

## Setup

Before running the code in this repository, please follow these steps:

1.  **Clone the Repository:**

    ```bash
    git clone <your-repository-url>
    cd <your-repository-name>
    ```

2.  **API Key Configuration:**
    Create a file named `cred.py` in the **root directory** of this repository. Inside `cred.py`, paste the following content, replacing `'這裡放入你的API Key'` with your actual Google Gemini API Key:

    ```python
    # cred.py
    keys = {
        'GEMINI_API_KEY': 'YOUR_GEMINI_API_KEY_HERE',
    }
    ```

    **Note:** It is highly recommended to use environment variables for sensitive information like API keys in production environments. For local development, this `cred.py` approach is acceptable but ensure `cred.py` is **not** committed to version control if your repository is public.

## Framework Versions

This project utilizes the following framework version:

  * **PEFT:** 0.15.2

## Project Structure & Contents

This repository is organized by course assignments (HW) and personal projects.

### Course Assignments (HW)

* **AI_HW3_calling_API:**
    * **Description:** Demonstrates how to link and interact with the Google Gemini API using Python to ask questions.
* **AI\HW4\build_application:**
    * **Description:** Focuses on building an application using Gemini with suitable prompts for answering mathematical questions.
* **AI\HW5\fine\tune\model\to\poet:**
    * **Description:** Explores fine-tuning a smaller language model (e.g., LLaMA) to generate poetry.
* **AI\HW6\train\model\with\human\preference:**
    * **Description:** Implements training a model based on different ratios of human preference data.
* **AI\HW7\open\AI\brain:**
    * **Description:** Investigates LLMs as a series of probabilities, using heatmaps to visualize token probabilities.
* **AI\HW8\avoid\AI\reply\harmful\information:**
    * **Description:** Addresses strategies and techniques to prevent AI models from generating harmful or inappropriate information to users.
* **AI\HW9\video\to\text:**
    * **Description:** Develops a solution for transcribing a YouTube video into text.

### Personal Projects

* **AI\RAG\introduction\of\dan:**
    * **Description:** A personal project demonstrating the application of Retrieval-Augmented Generation (RAG) to introduce "Dan" without fine-tuning a model.
* **Youtube\Translation:**
    * **Description:** A personal project that uses a YouTube subscription list to retrieve videos, translate them into text, and summarize the content via email.