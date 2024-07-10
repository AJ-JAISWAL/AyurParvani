# AyurParvani

AyurParvani is a powerful tool designed to provide Ayurveda information by answering user queries using state-of-the-art language models and vector stores. This README will guide you through the setup and usage of the AyurParvani.

## Table of Contents

- [Introduction](#AyurParvani)
- [Table of Contents](#table-of-contents)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Usage](#usage)

## Prerequisites

Before you can start using the AyurParvani, make sure you have the following prerequisites installed on your system:

- Python 3.6 or higher
- Required Python packages (you can install them using pip):
    - langchain
    - Streamlit
    - sentence-transformers
    - faiss
    - PyPDF2 (for PDF document loading)

## Installation

1. Clone this repository to your local machine.

    ```bash
    git clone https://github.com/your-username/Ayurparvani.git
    cd AyurParvani
    ```

2. Create a Python virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use: venv\Scripts\activate
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Download the required language models and data. Please refer to the Langchain documentation for specific instructions on how to download and set up the language model and vector store.

5. Set up the necessary paths and configurations in your project, including the `DB_FAISS_PATH` variable and other configurations as per your needs.

## Getting Started

To get started with the AyurParvani, you need to:

1. Set up your environment and install the required packages as described in the Installation section.

2. Configure your project by updating the `DB_FAISS_PATH` variable and any other custom configurations in the code.

3. Prepare the language model and data as per the Langchain documentation.

4. Start the bot by running the provided Python script or integrating it into your application.

## Usage

The AyurParvani can be used for answering ayurveda-related queries. To use the bot, you can follow these steps:

1. Start the bot by running your application or using the provided Python script.

2. Send a ayurveda-related query to the bot.

3. The bot will provide a response based on the information available in its database.

4. If sources are found, they will be provided alongside the answer.

5. The bot can be customized to return specific information based on the query and context provided.

![Screenshot 2024-06-08 142342](https://github.com/AJ-JAISWAL/AyurParvani/assets/108292938/129e553c-055d-4ade-b86e-a3fce6b4d5d5)
