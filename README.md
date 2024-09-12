# Aspect-Based Sentiment Analysis with Streamlit
## Overview
This project provides an interactive web application for Aspect-Based Sentiment Analysis (ABSA) using Streamlit. The application allows users to input sentences and analyze them to extract aspects and their corresponding sentiments. The underlying model is powered by the pyabsa library, which supports various pre-trained checkpoints for aspect extraction and sentiment inference.

## Features
- **Aspect-Based Sentiment Analysis**: Extracts aspects and sentiments from user-provided sentences.
- **Interactive Interface**: Built with Streamlit for a user-friendly experience.

## Requirements
To run this project, you need the following Python packages:

- `streamlit`
- `pyabsa`
- `pandas`
  
You can install these dependencies using pip:

```bash
pip install streamlit pyabsa pandas
```

## Setup and Usage
### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/mshaadk/Aspect-Based-Sentiment-Analysis.git
cd Aspect-Based-Sentiment-Analysis
```

### 2. Install Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App

Launch the Streamlit app using the following command:

```bash
streamlit run ABSA.py
```

### 4. Interact with the App

Open your web browser and navigate to `http://localhost:8501` to use the app. Enter a sentence in the input box and click the "Analyze" button to see the aspect-based sentiment analysis results.

## Code Explanation
- **Aspect Extraction**: The `pyabsa` library is used to load pre-trained models and perform aspect extraction and sentiment analysis.
- **Streamlit Interface**: The Streamlit app is designed to be simple and interactive, with an input field for user text and a button to trigger the analysis.

## Example
Here’s an example of how the app works:

1. **Input**: "The service was excellent, but the food was terrible."

2. **Output**:

| Aspect | Term | Sentiment | Confidence (%) |
| --- | --- | --- | --- |
| Aspect 1 | service | Positive | 87.50% |
| Aspect 2 | food | Negative | 92.75% |

## Contributing
Contributions are welcome! If you have any improvements or bug fixes, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.

## Contact
For questions or feedback, please contact [Mohamed Shaad](https://www.linkedin.com/in/mohamedshaad/).
