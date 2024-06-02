# MultiLanguage-Invoice-Extractor
![Screenshot 2024-06-02 at 10 53 38 PM](https://github.com/manav-888/MultiLanguage-Invoice-Extractor/assets/28830098/f3d3af61-6662-4c1d-9a27-f33a0038b195)

# Building a Response from Image


## Setup Instructions

Follow these steps to set up the project on your local machine:

1. **Clone the Repository:**
   ```
   git clone https://github.com/manav-888/MultiLanguage-Invoice-Extractor.git

2. **Create a Virtual Environment:**

   Note: We used Python 3.10.11 to create the virtual environment. Please ensure that you use the same Python version to avoid potential conflicts and ensure compatibility with the project dependencies.
   ```
   python3 -m venv venv
   ```

4. **Activate the Virtual Environment:**
   ```
   . venv/bin/activate
   ```

5. **Install Requirements:**
   ```
   pip install -r requirements.txt
   ```
    **  or: ** 

   ```
   pip install streamlit transformers google-generativeai python-dotenv torch torchvision torchaudio

   ```

6. ** Create .env  file   in same directory   and Configure GOOGLE API KEY  then put all file in  .gitignore file :**
   ```
    GOOGLE_API_KEY=" Insert Your KEY "
   
   ```

   **  or: ** 

   ** To run without Google API key  then hit submit query button with Hugging face model **

8. **  Run a app.py file in terminal **
   ```
   streamlit run app.py
   
   ```


