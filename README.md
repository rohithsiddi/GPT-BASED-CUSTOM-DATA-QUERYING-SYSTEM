
# GPT-BASED-CUSTOM-DATA-QUERYING-SYSTEM

This Python program enables you to upload a PDF document and interactively inquire about its content. The program employs a Language Model to produce relevant responses based on the PDF content, restricting its responses to questions pertinent to the document.

## How it works
The application reads the PDF and splits the text into smaller chunks that can be then fed into a LLM. It uses OpenAI embeddings to create vector representations of the chunks. The application then finds the chunks that are semantically similar to the question that the user asked and feeds those chunks to the LLM to generate a response.The application uses Streamlit to create the GUI and Langchain to deal with the LLM.

![Flowchart](https://github.com/rohithsiddi/GPT-BASED-CUSTOM-DATA-QUERYING-SYSTEM/assets/89602799/ae2692e6-7086-4c53-b251-c97cce6e176a)

## Screenshots

<img width="1508" alt="Interface1" src="https://github.com/rohithsiddi/GPT-BASED-CUSTOM-DATA-QUERYING-SYSTEM/assets/89602799/5fdfd601-32dc-419a-820b-d45f7e01e84d">

<img width="1512" alt="Interface2" src="https://github.com/rohithsiddi/GPT-BASED-CUSTOM-DATA-QUERYING-SYSTEM/assets/89602799/799985a5-70bd-4e27-8f55-9af7ffe9534d">




