# Customer Feedback Classification using Machine Learning
## Project Overview

This project focuses on classifying customer feedback into different categories using Machine Learning and Natural Language Processing (NLP). The system takes a customer's feedback message as input and predicts the appropriate category automatically.

The project uses a customer feedback dataset containing two main columns:

- Feedback – The customer's written feedback or complaint.
- Category – The category assigned to the feedback.

The feedback is classified into the following five categories:

- Billing
- General Inquiry
- Technical Support
- Delivery
- Product

---

## Objective

The main objective of this project is to build a text classification model that can automatically understand customer feedback and categorize it into the correct support department.

This can help organizations:

- Automatically organize customer complaints.
- Reduce manual classification work.
- Improve customer support response time.
- Route customer queries to the appropriate department.
- Analyze common customer issues.

---

## Dataset

The dataset contains customer feedback messages along with their corresponding categories.

### Dataset Columns

Column	          Description
Feedback	Text-based customer feedback
Category	Category assigned to the feedback

---

## Categories

- Product – Issues related to damaged products, wrong sizes, wrong colors, defective products, etc.
- General Inquiry – General questions about orders, discounts, cancellation, address changes, gift wrapping, etc.
- Technical Support – Login issues, password problems, application errors, checkout issues, search problems, etc.
- Delivery – Problems related to delivery, missing packages, incorrect delivery addresses, and order tracking.
- Billing – Payment issues, incorrect invoices, duplicate charges, and refund-related problems.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Machine Learning
- Matplotlib
- Seaborn

---

## Machine Learning Workflow

The project follows these major steps:

- Load the customer feedback dataset.
- Explore and understand the dataset.
- Check the distribution of feedback categories.
- Preprocess the text data.
- Convert text into numerical features using TF-IDF.
- Split the dataset into training and testing data.
- Train a Machine Learning classification model.
- Predict categories for unseen feedback.
- Evaluate model performance.
- Test the model with new customer feedback.

---

## Text Vectorization

Since Machine Learning models cannot directly process raw text, the customer feedback is converted into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency).

TF-IDF helps identify important words in customer feedback and represents the text in a numerical format that can be processed by the Machine Learning model.

---

## Model Training

The processed dataset is divided into:

- Training Dataset – Used to train the Machine Learning model.
- Testing Dataset – Used to evaluate the model's performance on unseen data.

The model learns patterns from the training feedback and predicts the appropriate category for new feedback messages.

---

## Model Evaluation

The trained model is evaluated using performance metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

These metrics help measure how accurately the model classifies customer feedback into the correct categories.

---

## Sample Feedback

### Product

- Wrong color received and I need help.
- Wrong size received for the last two days.
- Product arrived broken.
- Button not working.
- Device overheats.

### General Inquiry

- Is gift wrapping available for my order?
- Can I change my address?
- Can I cancel my order?
- Do you offer discounts?
- How can I update my order?

### Technical Support

- Checkout page is not loading.
- Password reset is not working.
- Cannot log in to my account.
- Search feature is not working.
- Mobile app closes automatically.

### Delivery

- Package not received.
- Order is still in transit.
- Package has not arrived.
- Courier delivered to the wrong address.
- My order has not been delivered yet.

### Billing

- Refund is delayed.
- Invoice is incorrect.
- I was charged twice.
- Refund has not been received.
- I was charged twice for the same order.

---

## Applications

This project can be used in:

- E-commerce websites
- Online shopping platforms
- Customer support systems
- Helpdesk applications
- Complaint management systems
- Automated ticket classification
- Customer service automation

---

## Future Enhancements

The project can be improved by:

- Increasing the size of the dataset.
- Adding more customer feedback categories.
- Using advanced NLP techniques.
- Applying Deep Learning models.
- Using Transformer-based models such as BERT.
- Creating a web application for real-time prediction.
- Integrating the model with a customer support ticketing system.
- Deploying the Machine Learning model using Flask, FastAPI, or Streamlit.
