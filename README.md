# Medik - Your Personal AI Doctor

An advanced medical diagnostic assistant that helps assess symptoms and provides evidence-based health information using AI.

## 🌟 Features

This interactive medical assistant offers:

- **Comprehensive Symptom Assessment**: Answer questions about your symptoms to receive a personalized health assessment
- **Multiple Medical Specialties**: Support for cardiovascular, respiratory, gastrointestinal, neurological, and more conditions
- **Personalized Analysis**: Takes into account age, gender, symptom duration, pain level, and medical history
- **Evidence-Based Information**: Retrieves relevant medical knowledge from clinical resources

## 🚀 Live Demo

Try out Medik on Hugging Face Spaces: [Medik App]([https://huggingface.co/spaces/[your-username]/medik](https://huggingface.co/spaces/ArfeenSKD/Medik))

## 🔧 Installation

### Prerequisites
- Python 3.9+
- pip

### Setup

1. Clone the repository:
```bash
git clone https://github.com/[your-username]/medik.git
cd medik
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On MacOS/Linux
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
cd direct_rag
streamlit run frontend/app.py
```

## 📊 System Architecture

Medik employs a Direct Retrieval-Augmented Generation (RAG) system that:
1. Processes user queries about medical symptoms
2. Retrieves relevant medical information from a knowledge base
3. Generates personalized, evidence-based responses
4. Provides structured assessments with possible diagnoses, tests, and treatments

## 📝 Usage Guide

1. **Start with Your Symptoms**: Select what brings you to the doctor today
2. **Share Your Information**: Enter basic details like age, gender, and symptom duration
3. **Answer Follow-up Questions**: The system will ask specific questions about your condition
4. **Review Your Assessment**: Receive a personalized health assessment with possible conditions and recommendations

## ⚠️ Medical Disclaimer

Medik provides medical information for educational purposes only. It should not replace professional medical advice, diagnosis, or treatment. Always consult with a qualified healthcare provider for medical concerns.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Contributors

-Sultan Ul Arfeen

## 🙏 Acknowledgements

- MIMIC-IV medical dataset
- Streamlit for web interface
- HuggingFace for model hosting 
