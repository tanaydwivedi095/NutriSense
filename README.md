# NutriSense AI: Intelligent Nutrition Assistant

## Overview
NutriSense AI is an advanced **Intelligent Nutrition Assistant** designed to provide reliable and context-aware nutritional guidance by leveraging **Retrieval Augmented Generation (RAG)**. This AI-powered assistant enhances responses by integrating structured **nutrition textbook data** with state-of-the-art **large language models (LLMs)**, ensuring accurate and trustworthy dietary recommendations. 

With the rising need for **personalized nutrition guidance**, NutriSense AI helps users by retrieving relevant information from nutrition textbooks, analyzing queries intelligently, and generating informative, well-referenced responses.

## Features
### ✅ Chat with a Nutrition Textbook
- NutriSense AI allows users to interact with a virtual nutrition textbook, extracting information from structured sources to generate well-informed answers.

### ✅ Retrieval Augmented Generation (RAG)
- Enhances LLM-generated responses by incorporating contextual information retrieved from high-quality nutrition sources.

### ✅ Custom Data Integration
- Supports **nutrition-based PDFs** to provide **domain-specific** knowledge, ensuring responses are backed by credible sources.

### ✅ Vector Search Mechanism
- Utilizes **FAISS (Facebook AI Similarity Search)** to efficiently retrieve the most relevant text chunks based on user queries, improving accuracy.

### ✅ LLM-Based Response Generation
- Generates comprehensive and contextually accurate answers using cutting-edge **transformer-based language models** such as OpenAI’s GPT and Meta’s LLaMA.

## How It Works
NutriSense AI operates through a structured pipeline designed to extract, process, and retrieve relevant information efficiently. The system follows these key steps:

1. **PDF Processing**
   - Uploads nutrition-related PDFs.
   - Extracts and formats text into structured chunks.

2. **Embedding Creation**
   - Converts text chunks into vector representations using a **pre-trained embedding model**.
   - Stores these vectors in a high-performance **vector database** (FAISS).

3. **Vector Search & Retrieval**
   - Performs similarity-based searches to retrieve the most relevant text segments in response to user queries.

4. **Prompt Engineering**
   - Constructs **dynamic prompts** that combine retrieved text with user queries for **contextually accurate** response generation.

5. **LLM Response Generation**
   - Generates detailed, **AI-powered responses** by combining retrieved knowledge with powerful **large language models**.

## Technologies Used
NutriSense AI is built using modern AI and NLP technologies, ensuring efficiency and accuracy in generating nutrition-related responses.

- **Python** – Core programming language used for development.
- **PyTorch** – Deep learning framework used for model training and inference.
- **Hugging Face Transformers** – Provides state-of-the-art LLMs for response generation.
- **FAISS (Facebook AI Similarity Search)** – Enables fast and efficient **vector search** for text retrieval.
- **LangChain** – Simplifies LLM-based application development and **retrieval-augmented generation (RAG)**.
- **OpenAI API / LlamaIndex** – Supports integration with powerful **language models** to generate responses.

## Installation
To set up NutriSense AI, follow these steps:

### Step 1: Clone the Repository
```bash
git clone https://github.com/tanaydwivedi095/NutriSense.git
cd NutriSense
```

### Step 2: Install Dependencies
Ensure you have **Python 3.8+** installed, then run:
```bash
pip install torch transformers faiss-cpu langchain openai llama-index
```

### Step 3: Run the Application
To start NutriSense AI in a Jupyter Notebook environment, execute:
```bash
jupyter notebook
```
Open the `.ipynb` file and follow the instructions to upload nutrition PDFs and interact with the AI.

## Usage
NutriSense AI provides an **interactive, AI-powered experience** to assist users in understanding nutrition concepts and making informed dietary decisions.

1. **Upload a Nutrition Textbook (PDF format).**
2. **Ask questions** related to:
   - Macronutrients (Proteins, Carbohydrates, Fats).
   - Vitamins and minerals.
   - Personalized diet recommendations.
3. **Get reliable, well-referenced answers** based on the uploaded document.

### Example Query & Response
#### **User Query:**
*What are the benefits of omega-3 fatty acids?*
#### **NutriSense AI Response:**
Omega-3 fatty acids are essential polyunsaturated fats that provide numerous health benefits, including:
- Reducing inflammation and supporting cardiovascular health.
- Improving brain function and mental well-being.
- Enhancing eye health by supporting the retina.
These benefits are well-documented in nutrition science and found in sources such as fish oil, flaxseeds, and walnuts.

## Future Enhancements
To further improve NutriSense AI, we plan to introduce the following features:

- **Integration with real-time nutrition APIs** for up-to-date dietary recommendations.
- **Expansion of the nutrition database** to include scientific research papers, government dietary guidelines, and academic studies.
- **Advanced response explainability** with citation tracking and reference generation.
- **Multi-modal support** to analyze nutrition labels and food images for **AI-driven insights**.
- **Mobile and Web Interface** for broader accessibility and convenience.

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-branch`).
3. Commit your changes and push the branch (`git push origin feature-branch`).
4. Open a pull request for review.

## License
This project is licensed under the **MIT License**, allowing for open-source contributions and modifications.

---
NutriSense AI represents a **next-generation approach** to AI-driven **nutrition assistance**, ensuring users receive scientifically backed, reliable dietary information. 🚀

