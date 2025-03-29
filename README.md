# Semantic Book Recommender

A semantic book recommendation system that utilizes large language models (LLMs) and semantic search to suggest books based on user preferences, reading history, and contextual understanding. This project integrates modern AI techniques and interactive tools to deliver highly personalized recommendations.

## Features
- **Semantic Search**: Leverages LLMs to understand user queries and provide context-aware book recommendations.
- **Interactive Interface**: Built with Gradio for an intuitive and responsive user experience.

## Technologies Used
- Python
- Large Language Models (HuggingFace)
- Gradio for the user interface
- Vector databases (ChromaDB)
- Dataset: https://www.kaggle.com/datasets/dylanjcastillo/7k-books-with-metadata

## Getting Started
1. Clone the repository:
    ```bash
    git clone https://github.com/raflyritonga/book-recommender.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Set up environment variables for API keys:
    ```bash
    export HUGGINGFACEHUB_API_KEY=your_api_key
    ```
4. Run the application:
    ```bash
    cd /programs
    python gradio-dashboard.py
    ```

## Contributing
Contributions are welcome! Please fork the repository, explore the `programs` folder for the core logic, and submit a pull request with your improvements.

## License
This project is licensed under the MIT License.