# Generative AI Introduction - Course Assignments & Projects

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

* **AI\_HW3\_calling\_API:**
    * **Description:** Demonstrates how to link and interact with the Google Gemini API using Python to ask questions.
* **AI\_HW4\_build\_application:**
    * **Description:** Focuses on building an application using Gemini with suitable prompts for answering mathematical questions.
* **AI\_HW5\_fine\_tune\_model\_to\_poet:**
    * **Description:** Explores fine-tuning a smaller language model (e.g., LLaMA) to generate poetry.
* **AI\_HW6\_train\_model\_with\_human\_preference:**
    * **Description:** Implements training a model based on different ratios of human preference data.
* **AI\_HW7\_open\_AI\_brain:**
    * **Description:** Investigates LLMs as a series of probabilities, using heatmaps to visualize token probabilities.
* **AI\_HW8\_avoid\_AI\_reply\_harmful\_information:**
    * **Description:** Addresses strategies and techniques to prevent AI models from generating harmful or inappropriate information to users.
* **AI\_HW9\_video\_to\_text:**
    * **Description:** Develops a solution for transcribing a YouTube video into text.

### Personal Projects

* **AI\_RAG\_introduction\_of\_dan:**
    * **Description:** A personal project demonstrating the application of Retrieval-Augmented Generation (RAG) to introduce "Dan" without fine-tuning a model. This project highlights RAG's efficiency in leveraging existing knowledge bases. For a detailed comparison between RAG and traditional fine-tuning, refer to my article: [RAG Deep Dive](https://medium.com/@p123456dan.mse99/generative-ai-introduction-2024-rag-deep-dive-15d5a9763177)
    * **Key Technologies:** RAG, Generative AI
* **Youtube\_Translation:**
    * **Description:** An automated personal project designed to manage and summarize YouTube content. It retrieves videos from a user's subscription list, translates their content into text, and then summarizes the information, delivering it via email. This streamlines staying updated with preferred channels.
    * **More Details:** Explore the full automation process and its benefits in the accompanying Medium article: [Youtube summary project](https://medium.com/@p123456dan.mse99/%E5%9C%A8%E8%B3%87%E8%A8%8A%E7%88%86%E7%82%B8%E7%9A%84%E6%99%82%E4%BB%A3-%E5%85%89%E6%98%AF%E6%AF%8F%E5%A4%A9%E8%BF%BD%E8%B9%A4%E5%96%9C%E6%AD%A1%E7%9A%84-youtuber-%E6%88%96%E6%96%B0%E8%81%9E%E9%A0%BB%E9%81%93%E6%9B%B4%E6%96%B0%E5%B0%B1%E8%80%97%E8%B2%BB%E4%B8%8D%E5%B0%91%E6%99%82%E9%96%93-%E7%82%BA%E4%BA%86%E6%9B%B4%E5%B0%88%E5%BF%83%E6%8A%95%E5%85%A5-ai-%E5%B0%88%E6%A1%88-%E6%88%91%E8%A8%AD%E8%A8%88%E4%BA%86%E4%B8%80%E5%A5%97%E8%87%AA%E5%8B%95%E5%8C%96%E6%B5%81%E7%A8%8B-%E5%B9%AB%E6%88%91%E5%B0%87-youtube-%E5%BD%B1%E7%89%87%E5%85%A7%E5%AE%B9%E5%BF%AB%E9%80%9F%E8%BD%89%E5%8C%96%E7%82%BA%E9%87%8D%E9%BB%9E%E6%91%98%E8%A6%81-%E4%B8%A6%E9%80%8F%E9%81%8E-052cb615bfeb)
    * **Key Technologies:** YouTube API, Text Translation, Summarization, Email Automation
* **AI\_Function\_Call\_LeetCode\_Assistant**
    * **Description:** A personal project leveraging Gemini's Function Calling capabilities to create an intelligent LeetCode information assistant. Users can interact using natural language to query LeetCode daily challenge questions and weekly contest details for specific dates. The assistant dynamically determines whether a queried date is a holiday and adjusts its information retrieval accordingly, fetching both daily and weekly contest data for holidays, but only daily challenges for non-holidays. This demonstrates conditional function execution based on API responses. [Project introduction](https://medium.com/@p123456dan.mse99/%E9%81%8B%E7%94%A8%E7%94%9F%E6%88%90%E5%BC%8F-ai-%E5%AF%A6%E7%8F%BE%E6%99%BA%E6%85%A7%E4%BA%92%E5%8B%95-%E6%88%91%E7%9A%84-leetcode-%E5%8A%A9%E7%90%86%E5%B0%88%E6%A1%88-e36278fa7d69)
    * **Key Technologies:** Gemini API (Function Calling), Natural Language Processing (NLP), Python
