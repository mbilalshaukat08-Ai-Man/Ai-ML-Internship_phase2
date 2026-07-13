# 🤖 Auto Tagging Support Tickets Using LLM

## Objective

The objective of this project is to automatically classify customer support tickets into relevant categories using a Large Language Model (LLM). The project compares zero-shot classification, few-shot prompting, and a fine-tuned model to evaluate their performance on support ticket categorization.

---

## Dataset

**Dataset:** Free-text Support Ticket Dataset

The dataset contains customer support tickets written in natural language along with their corresponding categories.

---

## Methodology

1. Load and explore the support ticket dataset.
2. Clean and preprocess the ticket text.
3. Perform zero-shot classification using a pre-trained Large Language Model.
4. Apply few-shot prompting with example tickets to improve prediction quality.
5. Fine-tune a transformer-based model for support ticket classification.
6. Compare the performance of zero-shot, few-shot, and fine-tuned approaches.
7. Output the top three most probable tags for each support ticket.
8. Evaluate the models using Accuracy and F1-score.

---

## Technologies Used

* Python
* Hugging Face Transformers
* PyTorch
* Pandas
* NumPy
* Scikit-learn
* Gradio (optional)
* Jupyter Notebook

---

## Project Files

* `Task5_Auto_Tagging_Support_Tickets.ipynb`
* `requirements.txt`
* `app.py` *(if deployment is included)*

---

## Results

The project demonstrates how Large Language Models can automatically categorize customer support tickets. Performance is compared across zero-shot, few-shot, and fine-tuned approaches, with the system returning the top three predicted tags for each ticket.

---

## Future Improvements

* Train on a larger support ticket dataset.
* Experiment with additional transformer models.
* Deploy the application using Gradio or Streamlit.
* Integrate the system into a real-time customer support workflow.

---

## Author

**Muhammad Bilal**

