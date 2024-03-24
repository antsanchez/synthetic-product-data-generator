# Synthetic Product Data Generation Notebook
This project houses a Jupyter Notebook designed to leverage the capabilities of Large Language Models (LLMs) via the [LangChain framework](https://python.langchain.com/docs/get_started/introduction) for the generation of synthetic product data. It aims to provide a versatile tool for generating realistic product listings, which can be customized and used across various domains, particularly e-commerce.

## Example
You can find an example of a dataset generated with this code. Its a synthetic dataset for a fishing eCommerce shop that can be found on Kaggle: [Synthetic Fishing Products Dataset](https://www.kaggle.com/datasets/asanchezdev/synthetic-fishing-products) and was generated using Mistral 7B locally.

## Author
This project is developed by Antonio Sánchez. For more details about his work and projects, visit [asanchez.dev](https://asanchez.dev).

## Motivation
The primary motivations behind this project include:

- **Exploration of LangChain**: Diving into the LangChain framework to understand its potential and how it can be leveraged with different LLMs.
- **Prompt Engineering**: Experimenting with diverse prompts to see their impact on the data generated by LLMs.
- **Synthetic Data Generation**: Creating synthetic data for e-commerce and other projects, which can be particularly useful for testing, development, and analysis purposes.

This notebook serves as a practical exploration of these areas, showcasing how custom prompts and different LLMs can be utilized to generate data that is both varied and relevant to specific use cases.

## About the Notebook
The Jupyter Notebook included in this repository is a comprehensive tool that guides users through the process of generating synthetic product data. It allows for extensive customization, enabling users to specify details such as the type of shop, the number of categories, vendors, and products to generate, along with the maximum attempts for LLMs to generate each product detail.

### Key Features:

- Generation of vendor names and product categories.
- Creation of random combinations of categories and vendors based on user-specified parameters.
- Detailed generation of product information, including titles, descriptions, and prices.

For detailed instructions on how to run the notebook, customize the generation parameters, and understand the complete workflow, please refer directly to the notebook included in this repository.

## Installation
Before running the notebook, ensure you have Python installed on your system. The project relies on several third-party libraries, which can be installed using pip:

```bash
pip install pandas tqdm langchain langchain_core
```

Alternatively, if you have a requirements.txt file in your repository:

```bash
pip install -r requirements.txt
```

### Running the Notebook in Google Colab
If you prefer not to set up a local environment, you can run the notebook directly in your browser using Google Colab. Click the badge below to open the notebook in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/antsanchez/synthetic-product-data-generator/blob/main/Generator.ipynb)

## Contributing
Contributions to improve the notebook or explore new data generation avenues are welcome. If you have ideas for improvement or new features, feel free to open an issue to discuss them or directly fork the project and create a pull request with your changes.