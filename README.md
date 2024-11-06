

---

# Email Department Classification Using NLP and Deep Learning

## Project Overview

In today's business environment, the reliance on email as a primary communication channel has grown significantly. Companies are inundated with a vast volume of emails daily, making effective email management a critical challenge. This project proposes an email classification approach using natural language processing (NLP) and deep learning techniques to automate the categorization of emails into three relevant departments: 

- **Customer Service**
- **Information Technology (IT)**
- **Human Resources (HR)**

## Objective

The primary aim of this project is to develop an automated system that classifies and redistributes emails based on their content, thus optimizing the email management process within organizations. By doing so, it enhances data-driven decision-making and improves the efficiency of the reply process.

## Dataset

The dataset utilized for this project was specifically collected and preprocessed using various NLP techniques. The dataset consists of three columns:

- **Subject**: The subject line of the email.
- **Email**: The body content of the email.
- **Department**: The target department to which the email belongs (Customer Service, Information Technology (IT), or Human Resources (HR)).

The preprocessing phase involved the following:

- **Word Embedding**: The word2vec method was employed for word embedding, allowing for the transformation of textual data into a numerical format suitable for deep learning models.

## Methodology

### Deep Learning Models

Two deep learning architectures were trained and evaluated in this project:

1. **Bidirectional Gated Recurrent Unit (BiGRU)**
2. **Bidirectional Long Short-Term Memory (BiLSTM)**

The models were designed to classify emails into the predefined categories based on their content.

## Results

The results of the study indicated that the BiLSTM model outperformed the BiGRU model in terms of classification accuracy:

- **BiLSTM Accuracy**: 85.24%
- **BiGRU Accuracy**: 83.61%

These findings highlight the effectiveness of the BiLSTM model for email classification tasks.

## Conclusion

This project addresses the gap in existing email filtering solutions, which typically focus on spam detection rather than content-based classification. By implementing the proposed model, businesses can automate the email management process, leading to improved operational efficiency and more timely responses to customer inquiries.

## Installation and Usage

To replicate this project, follow these steps:

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


