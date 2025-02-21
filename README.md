# 🎉 Event Planner RAG Model

📌 _**Overview:**_</br>
    The Event Planner RAG (Retrieval-Augmented Generation) Model is an AI-powered chatbot designed to assist with event planning. It integrates LangChain, OpenAI GPT, and ChromaDB to provide intelligent event planning        recommendations based on user queries. Whether you're organizing a wedding, corporate event, or a birthday party, this model helps streamline planning by retrieving relevant information and generating insights. Use       the training model to further upgrade your model to understand your data better.
***
🔹 _**Usage:**_</br>
    **Event_Planner_RAG.ipynb** file has the main code of deploying the model.</br>
    **Training_data.ipynb** file has the further training your data for spefic type of questions. feel free to edit the question according to your use case. </br>
    **database** folder has subfolder for respective data. (Note: Unzip the file and Save the folder in the save location as notebook or update the file path otherwise).</br>
***
🚀 _**Features:**_</br>
        Event Planning Assistance – Get AI-driven suggestions for venue selection, catering, and more.</br>
        RAG-Based Search – Combines retrieval and generation for accurate responses.</br>
        Memory-Powered Conversations – Maintains context using LangChain's memory components.</br>
        Interactive Visualization – Uses t-SNE and Plotly to visualize event data.</br>
        Continuous Learning – Update and fine-tune the knowledge base dynamically.</br>
***
🛠 _**Installation**_

1️⃣ Clone the repository:

git clone https://github.com/Shruti7110/event-planner-rag.git
cd event-planner-rag

2️⃣ Install dependencies:

pip install langchain langchain-openai langchain-chroma matplotlib scikit-learn numpy plotly python-dotenv openai

3️⃣ Set up API Keys:

Create a .env file and add your OpenAI API key:

OPENAI_API_KEY=your_api_key_here
***

🤝 **_Contributing_**

Want to improve this project? Feel free to fork and submit pull requests!
