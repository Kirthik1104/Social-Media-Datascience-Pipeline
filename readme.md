## Project: Interactive Dashboard and Analysis for Gun Culture and Hate Speech on Social Media

## Project Introduction
This project aims to provide insightful analysis and interactive visualizations of social media data, focusing on gun culture and hate speech. Utilizing datasets from platforms like 4Chan and Reddit, the project leverages Python and its robust libraries to process, analyze, and visualize trends and patterns. The centerpiece of the project is a Streamlit-based dashboard that allows users to interactively explore the data, complemented by a Jupyter Notebook for in-depth analysis.

## Code Explanation
- **Dashboard.py (Streamlit Script):** This script creates an interactive web dashboard using Streamlit. It loads optimized datasets from 4Chan and Reddit, processes them, and then displays various visualizations like sentiment analysis, keyword frequency, and word clouds. Users can filter data based on dates and platforms.
  
- **Full Analysis.ipynb (Jupyter Notebook):** This notebook contains a detailed analysis of the datasets. It involves data cleaning, sentiment analysis, keyword frequency analysis, and time series visualization. The notebook uses libraries like Pandas, NLTK, and Matplotlib for data processing and visualization.

## How to Run This Project
### Dashboard.py
1. **Setup:**
   - Ensure Python is installed on your system.
   - Install required libraries: `streamlit`, `pandas`, `matplotlib`, `wordcloud`, `plotly`, `nltk`.
   - Use `pip install -r requirements.txt` to install these dependencies easily.
2. **Running the Dashboard:**
   - Navigate to the project directory in the terminal.
   - Run the command: `streamlit run Dashboard.py`.
   - The dashboard should now be accessible in your web browser.

### Full Analysis.ipynb
1. **Setup:**
   - Ensure Jupyter Notebook is installed, or use JupyterLab or Google Colab.
   - Ensure all required libraries are installed as mentioned above.
2. **Running the Analysis:**
   - Open `Full Analysis.ipynb` in your Jupyter environment.
   - Run each cell in the notebook to see the analysis and visualizations.

## How to Deploy Streamlit
1. **Local Deployment:**
   - Run `streamlit run Dashboard.py` as described above. This will host the dashboard locally on your machine.

2. **Remote Deployment:**
   - For remote deployment, you can use services like Streamlit Sharing
   - **Streamlit Sharing:**
     - Push your code to a public GitHub repository.
     - Sign up for Streamlit Sharing and link your GitHub.
     - Deploy your app by selecting your repository and branch.