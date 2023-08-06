
# GPT-BASED-CUSTOM-DATA-QUERYING-SYSTEM

This Python program enables you to upload a PDF document and interactively inquire about its content. The program employs a Language Model to produce relevant responses based on the PDF content, restricting its responses to questions pertinent to the document.

## How it works
The application reads the PDF and splits the text into smaller chunks that can be then fed into a LLM. It uses OpenAI embeddings to create vector representations of the chunks. The application then finds the chunks that are semantically similar to the question that the user asked and feeds those chunks to the LLM to generate a response.The application uses Streamlit to create the GUI and Langchain to deal with the LLM.

![alt text](https://github.com/[rohithsiddi]/[GPT-BASED-CUSTOM-DATA-QUERYING-SYSTEM]/blob/[main]/Flowchart.png?raw=true)

## Screenshots


![alt text](https://github.com/[rohithsiddi]/[GPT-BASED-CUSTOM-DATA-QUERYING-SYSTEM]/blob/[main]/Interface1.png?raw=true)




![alt text](https://github.com/[rohithsiddi]/[GPT-BASED-CUSTOM-DATA-QUERYING-SYSTEM]/blob/[main]/Interface2.png?raw=true)




