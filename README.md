# **Fake News Detection - Social Media Analysis @ NAACL 2025**  

This repository contains our implementation for the **Fake News Detection Shared Task**, organized as part of **Social Media Analysis @ NAACL 2025**. The goal of this task is to classify social media posts as **Original** or **Fake**, leveraging NLP techniques to combat misinformation.  

## **Task Overview**  

With the rapid rise of social media, false or misleading information—commonly referred to as **fake news**—has become a growing concern. This shared task challenges participants to build robust machine learning models that can **detect and classify fake news** based on textual content from platforms like Twitter, Facebook, and YouTube.  

### **Subtasks**  

- **Task 1**: Classify a given social media post as **Original** or **Fake** based on its textual content.  
- **Task 2**: Given a YouTube comment, determine whether it contains **original** or **fake** news.  

### **Key Details**  

- **Data Sources**: Social media platforms (Twitter, Facebook, YouTube)  
- **Evaluation Metric**: Macro F1 Score  
- **Dataset**: Contains labeled text samples for training and evaluation  
- **Objective**: Develop a system that accurately classifies posts/comments as:  
  - **Fake News**  
  - **Original News**  

For dataset access and participation details, visit the **Participate** tab [here](#).  

## **Repository Structure**  

```
├── Images/
│   ├── Fake News Shared Task Methodology.png
│   ├── Qualitative_analysis.png
│   ├── confusion_matrix.png
├── Notebook/
│   ├── CUET-NLP_Big_O_Fake_News_Detection.ipynb
│   ├── Data_Analysis_&_Preprocessing.ipynb
│   ├── ML_DL_models.ipynb
├── requirements.txt          # Required Python libraries
├── README.md                 # Project documentation
```

## **Methodology**  

This section will be updated soon with details on the model architecture, data preprocessing techniques, and classification approaches used.  

## **Installation**  

Clone the repository:  

```bash
git clone https://github.com/Arghya-n/DravidianLangTech-FakeNews-2025.git
cd Fake-News-Detection-NAACL-2025
```

Install dependencies:  

```bash
pip install -r requirements.txt
```

## **Acknowledgments**  

We extend our gratitude to the organizers of **Social Media Analysis @ NAACL 2025** for providing the dataset and hosting this important shared task. We also acknowledge the open-source community for tools like **PyTorch, Hugging Face Transformers, and Scikit-learn**, which facilitate NLP research.  

---
