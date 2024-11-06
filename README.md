---
# Email Department Classification Using NLP and Deep Learning
## Project Overview

With the growing volume of emails in today’s business environment, managing and categorizing them effectively has become a significant challenge. This project aims to automate email classification using Natural Language Processing (NLP) and deep learning techniques, sorting emails into three key departments:

- **Customer Service**
- **Human Resources (HR)**
- **Information Technology (IT)**

By leveraging deep learning models, the goal is to streamline email management and improve efficiency.

## Objective

The project’s primary objective is to develop an automated system that classifies and routes incoming emails to the appropriate departments based on their content. This system will improve operational efficiency, enhance data-driven decision-making, and speed up response times.

## Dataset

The dataset used in this project consists of emails, each labeled with its corresponding department. The dataset includes three columns:

- **Subject**: The subject line of the email.
- **Email**: The body content of the email.
- **Department**: The target department (Customer Service, IT, or HR).

### Preprocessing

The dataset underwent several preprocessing steps using NLP techniques, including:

- **Word Embedding**: The word2vec method was used to convert text into numerical representations, enabling the model to better understand the textual data.

## Methodology

Two deep learning models were trained and evaluated for this project:

1. **Bidirectional Gated Recurrent Unit (BiGRU)**
2. **Bidirectional Long Short-Term Memory (BiLSTM)**

Both models were designed to classify emails based on the content of their subject and body.

## Results

The BiLSTM model outperformed the BiGRU model in terms of accuracy:

- **BiLSTM Accuracy**: 85.24%
- **BiGRU Accuracy**: 83.61%

These results indicate that the BiLSTM model is particularly effective for classifying emails.

## Conclusion

This project fills a gap in existing email classification solutions, which often focus on spam detection rather than content-based sorting. By automating email routing, businesses can optimize email management, leading to faster responses and better customer service.

## Installation and Usage

To replicate the project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd email-classification
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the script**:
   ```bash
   python classify_emails.py
   ```

---
