[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AI4EnergyJustice/Tutorials/master)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI4EnergyJustice/Tutorials)


# AI for Energy Justice

This repository contains a series of Jupyter notebook tutorials for the AI for
Energy Justice project. The tutorials cover a range of topics, including machine
learning, large language models (LLMs), web scraping, and fine-tuning LLMs.

The goal of AI for Energy Justice is to create a question answering model
customized for energy justice. The students can choose any open-source LLM to
base their model and fine-tune it with the reports, news articles, and bills
related to energy justice. To evaluate the performance of their models, students
should identify a set of questions that they can use to monitor the accuracy of
their models.

## Tutorials

1. [Machine Learning Tutorial](./ml_tutorial.ipynb): This tutorial provides an introduction to machine learning using the Scikit-Learn library. It covers the basics of loading data, training a model, and evaluating its performance.

2. [Large Language Models Tutorial](./llm_tutorial.ipynb): This tutorial introduces the concept of Large Language Models (LLMs). It explains what LLMs are, how they work, and how they can be used for tasks like text generation and question answering.

3. [Web Scraping Tutorial](./web_scraping_tutorial.ipynb): This tutorial covers
   the basics of web scraping, a technique for extracting data from websites. It
   introduces the Beautiful Soup library and shows how it can be used to parse
   HTML and extract useful information.

4. [Fine-tuning Tutorial](./fine_tune_tutorial.ipynb): This tutorial delves into the process of customizing LLMs with additional data, a process known as "fine-tuning". It shows how fine-tuning can be used to adapt a general-purpose LLM to a specific task or domain.


Please note that these tutorials are designed to be followed in order, as each one builds on concepts introduced in the previous tutorials.

## Setting Up a Virtual Environment and Installing Dependencies

Before you start the tutorials, we recommend setting up a virtual environment and installing the required Python libraries. This ensures that the libraries don't interfere with any other Python projects you may have on your system.

Follow these steps to set up a virtual environment and install the dependencies:

1. **Create a Virtual Environment:** Navigate to the directory where you want to store your virtual environment, then run the following command to create a new virtual environment. Replace `env` with the name you want to give to your virtual environment.

    ```bash
    python3 -m venv env
    ```

2. **Activate the Virtual Environment:** Before you can start installing libraries or running Python scripts, you need to activate the virtual environment. On Windows, run:

    ```bash
    .\\env\\Scripts\\activate
    ```

    On macOS and Linux, run:

    ```bash
    source env/bin/activate
    ```

    You should now see `(env)` at the start of your command line, indicating that the virtual environment is active.

3. **Install Dependencies:** Now that the virtual environment is active, you can install the required libraries using the `requirements.txt` file. Navigate to the directory containing `requirements.txt`, then run:

    ```bash
    pip install -r requirements.txt
    ```

4. **Deactivate the Virtual Environment:** Once you're done working on the project, you can deactivate the virtual environment by simply running:

    ```bash
    deactivate
    ```

Remember to activate the virtual environment every time you work on the project,
and deactivate it when you're done.

Note: I used GPT-4 to help me create the content for these tutorials.
