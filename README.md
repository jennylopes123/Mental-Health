TheraBot: Question and Answer System Based on Google Palm LLM and Langchain.  We are building a Q&A system for mental health chatbot using a streamlit interface called TheraBot.

You will learn following, Langchain + Google Palm: LLM based Q&A Streamlit: UI Huggingface instructor embeddings: Text embeddings FAISS: Vector databse.

Installation : 
1. Clone this repository to your local machine using: git clone https://github.com/codebasics/langchain.git 
2. Navigate to the project directory:
cd Thera_Bot 
3. Install the required dependencies using pip: pip install -r requirements.txt 
4. Acquire an api key through makersuite.google.com and put it in .env file
GOOGLE_API_KEY="your_api_key_here"
Run the Streamlit app by executing: streamlit run main.py .The web app will open in your browser.

To create a knowledebase of FAQs, click on Create Knolwedge Base button. It will take some time before knowledgebase is created so please wait.

Once knowledge base is created you will see a directory called faiss_index in your current folder.

Now you are ready to ask questions. Type your question in Question box and hit Enter.

Sample Questions:
I suffer from social anxity. How can I cope with it??
My college studies are making me stressed? How can I deal with it?? 
I don't feel confident about my body? What should I do? 
How do I cope with work related stress? 
Project Structure 
main.py: The main Streamlit application script. 
langchain_helper.py: This has all the langchain code 
requirements.txt: A list of required Python packages for the project. 
.env: Configuration file for storing your Google API key.
