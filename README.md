# AI Multilingual Translation

## Overview
AI Multilingual Translation is a powerful translation tool that leverages machine learning to provide real-time, high-accuracy translations in multiple languages. The project utilizes **GoogleTranslator (DeepTranslator)** for speed and accuracy, with **langDetect** for language detection. The goal is to offer a fast and efficient translation system that meets high standards of accuracy.

## Features
- Supports **10 languages** for translation
- Real-time translation using **GoogleTranslator (DeepTranslator)**
- **Language detection** using langDetect
- **Formal vs Informal translation** (Planned)
- **Gesture-based translation for sign language** (Planned)
- Optimized for **speed and accuracy**
- Evaluation using **BLEU, METEOR, ROUGE-L**

## Installation
### Prerequisites
Ensure you have Python installed (version 3.8+ recommended). Install the required dependencies using:
```sh
pip install deep-translator langdetect
```

## Usage
Run the Jupyter Notebook to start the translation process:
```sh
jupyter notebook "AI Multilingual Translation.ipynb"
```

Alternatively, use the Python script (if available) to run translations directly.

## Evaluation Metrics
To ensure high accuracy, this project uses:
- **BLEU Score** (Bilingual Evaluation Understudy)
- **METEOR Score** (Metric for Evaluation of Translation with Explicit ORdering)
- **ROUGE-L Score** (Recall-Oriented Understudy for Gisting Evaluation)

## Future Enhancements
- **Fine-tune mBART/NLLB** for better translation accuracy
- **Implement context-aware translation** for better phrase meaning
- **Integrate gesture-based translation** for deaf and mute users
- **Optimize performance** to reduce translation time further

## Contributing
Feel free to contribute to this project by submitting pull requests or raising issues. All contributions are welcome!

## License
This project is licensed under the MIT License.

## Contact
For questions or suggestions, reach out via GitHub Issues.

