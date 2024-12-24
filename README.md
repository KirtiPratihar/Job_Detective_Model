# Job_Detective_Model

JobDetective is a machine learning project designed to detect fake job postings. Using natural language processing (NLP) and classification models, this project helps identify fraudulent job advertisements and protect job seekers from scams.

## Features
- Preprocessing of job descriptions using NLP techniques
- Feature extraction with TF-IDF and metadata analysis
- Machine learning models for classification, including Logistic Regression, Random Forest, and SVM
- Performance evaluation using accuracy, precision, recall, and F1-score

## Dataset
We use the **Real or Fake Job Posting Prediction** dataset from Kaggle, which contains:
- **18,000 job postings**
- Labels indicating whether a posting is real or fake

[Download Dataset from Kaggle](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)

## Project Structure
```
JobDetective/
├── data/
│   ├── train.csv
│   ├── test.csv
├── notebooks/
│   ├── EDA.ipynb           # Exploratory Data Analysis
│   ├── Model_Building.ipynb
├── src/
│   ├── preprocess.py       # Data preprocessing scripts
│   ├── feature_engineer.py # Feature extraction scripts
│   ├── train_model.py      # Model training scripts
│   ├── evaluate.py         # Model evaluation scripts
├── app/
│   ├── app.py              # Deployment script using Flask
├── README.md
├── requirements.txt        # Dependencies
├── .gitignore
```

## Requirements
To run the project, install the following dependencies:

```bash
pip install -r requirements.txt
```

Key libraries:
- `pandas`
- `numpy`
- `scikit-learn`
- `nltk`
- `flask`

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/KirtiPratihar/Job_Detective_Model.git
   ```

2. Navigate to the project directory:
   ```bash
   cd JobDetective
   ```

3. Preprocess the data:
   ```bash
   python src/preprocess.py
   ```

4. Train the model:
   ```bash
   python src/train_model.py
   ```

5. Evaluate the model:
   ```bash
   python src/evaluate.py
   ```


## Future Enhancements
- Integrate real-time job posting scraping
- Add advanced NLP techniques like BERT embeddings
- Deploy as a web app with user authentication

## Contribution
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
### Author
**[Your Name](https://www.linkedin.com/in/kirti-pratihar-426072279)**
