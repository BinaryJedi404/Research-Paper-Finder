# Research Paper Finder
With the overwhelming number of scholarly articles and research papers published daily, it becomes challenging for researchers, students, and academics to stay updated with the latest advancements in their field and locate the most pertinent papers for their research. The task of finding relevant literature is time-consuming and frequently involves manual searches, which can result in missed opportunities and knowledge gaps. Hence, there is a demand for a recommender system to help researchers efficiently and effectively discover relevant research papers.

# Dataset Used
## Arxiv Dataset 
https://www.kaggle.com/datasets/Cornell-University/arxiv

# Approach
- Combined all the preprocessed text and calculated the Term Frequency-Inverse Document Frequency (TF-IDF) vector for each research paper.
- Used the TF-IDF matrix to calculate cosine similarity between research papers.
- Used cosine similarity score to recommend similar research papers for a given research paper.

# Use
* Download and keep the dataset in the same folder.
* First run will take time to generate the matrix and then save the progress as a pickle file to speed up the process from next search.
* Run the python file using "streamlit run web_ui.py"
* Type your topic of interest and number of results you want.
* Hit "Get Recommendations".
  
# Web Application
Used streamlit to develop a web interface for the Application.
