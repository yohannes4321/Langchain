

Langchain Pdf upload and reader using LangChain

This projects allows multiple pdf  and process them using langchain embed the contents into vectors using FAISS vector database and perform similirity searches and to retieve relevant answer from the files 

in pdf extractiona and document loading text embedding and store embedding query vector database and answer the solution i have used langchain  


This projects develope by Yohannes Alemu 

Steps to Run the Project
Step 1: Clone the Repository
```
git clone  https://github.com/yohannes4321/Langchain
cd langchain```
Step 2: Set up Virtual Environment
Create a Python virtual environment using Python 3.10:

 
```python3.10 -m venv venv```
Step 3: Activate the Virtual Environment
Activate the virtual environment using the following command:

On Linux/Mac:
 
```source venv/bin/activate```
On Windows:

 
```.\venv\Scripts\activate```
Step 4: Install Dependencies
Install the required dependencies listed in the requirements.txt file:

 
```pip install -r requirements.txt```
Step 5: Set up Environment Variables
Create a .env file in the root directory of the project and add the following API key:

makefile
 
```GOOGLE_API_KEY="<your-google-api-key>"```
You can get your Google API key from the Google Cloud Console.

Step 6: Run the Application
To start the application and launch the Streamlit interface, run:

 
```streamlit run app.py```
This will open the application in your browser.