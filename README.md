# Medik - Your Personal AI Doctor 🏥

A sophisticated AI medical assistant powered by Retrieval-Augmented Generation (RAG). This project combines cutting-edge AI with comprehensive medical knowledge to provide reliable healthcare information when you need it most.

## 💡 The Inspiration

Medik was born out of a real need. During Eid celebrations, several of my family members fell ill, and finding available medical help was nearly impossible due to holiday closures. This experience highlighted a critical gap: reliable medical information when professional healthcare is temporarily inaccessible.

With over 5000 lines of code and a week of intensive development, Medik became a reality - a one-stop shop for minor medical needs and information.

## 🌟 Features

- **Multiple Retrieval Methods**: 
  - BM25 (keyword-based) for precise matching
  - Dense embedding (semantic) for contextual understanding
  - Hybrid approach combining both for optimal results

- **Intelligent Response Generation**:
  - Evidence-based medical information
  - Contextual understanding of symptoms and conditions
  - Clear, accessible explanations of medical concepts

- **Knowledge Integration**:
  - Incorporates diagnostic knowledge graphs
  - Processes clinical notes effectively
  - Maintains medical context throughout

- **User-Friendly Interface**:
  - Intuitive Streamlit interface
  - Structured symptom assessment
  - General medical query support
  - Visual result presentation

## 🚀 Quick Start

### Prerequisites

- Python 3.8+
- Medical dataset (included)
- GPU (recommended) with 8GB+ VRAM

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SultanArfeen/medik.git
   cd medik
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the dataset:
   ```bash
   python setup_data.py
   ```

### Running the System

#### Web Interface
```bash
cd frontend
streamlit run app.py
```

#### Command Line
```bash
python main.py --prepare  # Prepare data
python main.py --query "What are the symptoms of diabetes?"  # Run a query
python main.py --interactive  # Run in interactive mode
```

## 🏗️ System Architecture

Medik consists of several key components:

### Data Processor
- Handles medical datasets
- Processes clinical notes and knowledge graphs
- Extracts and formats diagnostic information

### Retriever
- BM25: Traditional keyword-based retrieval
- Embedding: Semantic search using sentence transformers
- Hybrid: Combines both approaches for better results

### Generator
- Converts retrieved medical information into helpful responses
- Handles medical terminology appropriately
- Ensures responses are clear and accessible

## 📊 Performance

- **Retrieval Accuracy**: 85%+ on test queries
- **Response Quality**: Evidence-based medical responses
- **Processing Speed**: Optimized for quick responses with caching

## ⚠️ Medical Disclaimer

Medik is for informational purposes only and does not provide medical advice, diagnosis, or treatment. Always consult with a qualified healthcare provider for medical concerns.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

Feel free to reach out:
- GitHub: [@SultanArfeen](https://github.com/SultanArfeen)
- LinkedIn: [Sultan Ul Arfeen](https://www.linkedin.com/in/sultan-arfeen-560a24353/)
- Medium: [@sultanularfeen](https://medium.com/@sultanularfeen)
- Hugging Face: [@ArfeenSKD](https://huggingface.co/ArfeenSKD) 
