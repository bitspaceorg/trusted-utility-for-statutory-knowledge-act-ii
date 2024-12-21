<div align=center>
       <img src="https://github.com/bitspaceorg/.github/assets/119417646/577c8581-499e-4cbb-a2f8-e78c643204bc" width="150" alt="Logo"/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
       <img src="https://github.com/user-attachments/assets/359035d0-6a5b-403a-ac6a-35c82db8c5b1" width="120" alt="Logo" />
  <h1>Innovation Challenge December 2024</h1>
  <img src="https://img.shields.io/badge/:bitspace-%23121011?style=for-the-badge&logoColor=%23ffffff&color=%23000000">
  <img src="https://img.shields.io/badge/Genspark-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black">
  <img src="https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white">
  <img src="https://img.shields.io/badge/Microsoft-0078D4?style=for-the-badge&logo=microsoft&logoColor=white">

  <h1>TUSK: Trusted Utility for Statutory Knowledge ACT II </h1>
 <a href="https://1drv.ms/p/c/b7bb6097c40f3e7e/Eb5NlOnzfyBAjh_dxBXCbtMBVrGIYLxx8GSMBpwuhnSvtQ?e=qDWxfv"> <img src="https://github.com/user-attachments/assets/73d36b52-0529-40b4-b008-012eeca5df05" width=30 />
 </a>
  &nbsp;&nbsp;&nbsp;
<a href="https://youtu.be/sxh0NVZe1no">
       <img src="https://github.com/user-attachments/assets/bdbba9bb-e860-4eba-890f-268abdc81730" width=30 />
</a>
  &nbsp;&nbsp;&nbsp;

<a href="">
       <img src="https://github.com/user-attachments/assets/2676cd53-a2f7-4c37-abc4-1127f00fba86" width=30 />
</a>
</div>


Tusk Act 2 is a cutting-edge browser plugin designed to revolutionize how users interact with web data. Built on the robust Manifest V3 framework, it provides an intelligent sidebar that enhances productivity by leveraging AI-driven tools and domain-specific insights. With a focus on privacy, efficiency, and adaptability, Tusk Act 2 is tailored to meet the demands of education, development, and research use cases.

- Check out -> [How To Use](https://github.com/bitspaceorg/trusted-utility-for-statutory-knowledge-act-ii/blob/main/HOWTOUSE.md)

## Table of Contents

1. [Working](#working)
   - [Browser Plugin](#browser-plugin)
       - [Manifest V3](#manifest-v3)
   - [Knowledge Base Creation](#knowledge-base-creation)
       - [Domain-Based Indexing](#domain-based-indexing)
       - [Quantization](#quantization)
   - [RAG-Based Q&A Chatbot](#rag-based-qa-chatbot)
2. [Use Cases](#use-cases)
3. [Technologies Used](#technologies-used)
4. [Azure](#azure)
5. [Architecture](#architecture)
   - [Browser Plugin Architecture](#browser-plugin-architecture)
   - [Backend Architecture](#backend-architecture)
6. [Team](#team)
7. [Contribution](#contribution)

# Working

## Browser Plugin
### Manifest V3
The Tusk Act 2 plugin is built using **Manifest V3**, the latest standard for developing browser extensions. This ensures:
- **Improved Performance**: Faster and more efficient resource utilization.
- **Enhanced Security**: Incorporates stringent security measures like isolated processes and restricted permissions.
- **Better Privacy Controls**: Reduces the risk of unauthorized access to sensitive user data.

## Knowledge Base Creation
### Domain-Based Indexing
- The plugin collects HTML data from websites visited by the user, ensuring user consent is obtained.
- Data is indexed using the **domain name** as one of the key, creating a structured knowledge base.
- This indexing approach enables:
  - Better contextual understanding of user browsing patterns.
  - Domain-specific data organization for precise insights.
  
![image](https://github.com/user-attachments/assets/3f5cc97d-dc08-4088-8f23-c777cef55ec5)

### Quantization
- Utilizes **Azure AI Search's** quantization methods, such as **Scalar Quantization**, **Binary Quantization**
- These methods ensure the knowledge base is efficient and scalable by compressing data while preserving critical information.  
- They reduce vector sizes to optimize memory usage.  
- Storage requirements are minimized without compromising the quality of the data.  

## RAG-Based Q&A Chatbot
- **Retrieval-Augmented Generation (RAG)** combines:
  - **Information Retrieval**: Extracts relevant data from the domain-indexed knowledge base.
  - **Large Language Models (LLMs)**: Processes and synthesizes the retrieved information to generate intelligent responses.
- The chatbot can:
  - Answer context-specific queries based on user browsing history.
  - Summarize and explain interconnected topics across multiple pages in a domain.
<div align=center>
<img src="https://github.com/user-attachments/assets/a0674c2e-04f2-4339-9964-9db60ee8f8ed" width=500 />
</div>

## Use Cases

1. **Education**  
   - Helps students and educators summarize and explain complex concepts.  
   - Assists in consolidating information from multiple sources for better understanding.

2. **Development**  
   - Bridges technical documentation across different platforms.  
   - Provides insights on integrating functionalities or solving specific coding challenges.

3. **Research**  
   - Organizes domain-specific data for in-depth analysis.  
   - Enhances productivity by summarizing large datasets and providing targeted insights.

4. **Productivity**  
   - Acts as an AI assistant to improve efficiency.  
   - Offers domain-specific guidance for tasks like report writing, content creation, or troubleshooting.

# Technologies Used

1. **Azure Cloud Services**  
   - Azure provides the foundation for TUSK’s infrastructure, offering secure storage and scalable hosting. This enables seamless integration, centralized management, and efficient handling of data and AI functionalities.

2. **Models**  
   - **Text-Embedding-3-Large**  
     - Used to generate embeddings for each document ingested into the Knowledge Base, enabling efficient and contextually aware search.  
   - **LLAMA-7B**  
     - LLAMA-7B is used to power the AI's natural language understanding and response generation. It enables nuanced interactions, making the chatbot contextually aware and capable of handling domain-specific queries effectively.

3. **Manifest V3**  
   - Manifest V3 is the latest specification for browser extensions, offering enhanced security, privacy, and performance. It provides the framework for TUSK’s browser plugin, ensuring compatibility with modern browsers and enabling efficient integration with the backend services.

4. **LangChain**  
   - LangChain enables the RAG chain and dynamic prompt construction, integrating document sections, contextual knowledge from the Knowledge Base, and previous validation results for nuanced compliance checks.

5. **Flask (Backend)**  
   - Flask serves as the backend framework, managing API endpoints, processing logic, and integration with Azure services for efficient handling of document processing and validation tasks.

6. **Azure SDK for Python**  
   - The Azure SDK allows seamless interaction between Flask and Azure services, enabling smooth data flow and integration across the platform.

7. **Python**  
   - Python powers the backend logic and supports integrations with LangChain, Azure SDK, and other modules for document processing and compliance analysis.

8. **Microsoft OAuth 2.0**  
   - Microsoft OAuth 2.0 is used to secure user authentication and authorization. It ensures that only authenticated users can access the plugin's features and safeguards against unauthorized usage.

# Azure

1. **Azure AI Search**  
   - Serves as the vector store, housing embeddings generated for the Knowledge Base. This service enables fast, contextually relevant retrieval, allowing the RAG process to locate the most pertinent information and generate accurate responses based on the user's queries.

2. **Azure OpenAI Labs**  
   - Provides access to the embedding model **Text-Embedding-3-Large**, used to create high-quality embeddings for textual data, which are then used in the RAG process to enhance content retrieval and response generation by leveraging deep learning models.

3. **Azure ML Studio**  
   - Hosts the **LLAMA 7B** model, providing a scalable and powerful environment to run the model and generate context-aware responses based on the ingested knowledge from the user's browsing activities.

4. **Azure Container Apps**  
   - Hosts and scales the backend Flask application, handling API requests and integrating processing logic. Azure Container Apps ensures that the backend remains responsive and adaptable to fluctuating demand, providing an efficient infrastructure for handling high volumes of requests while maintaining performance.

5. **Azure SDK for Python**  
   - Facilitates seamless integration between Flask and Azure services, streamlining data management and retrieval processes throughout the project. It simplifies the connection between the backend application and Azure's various AI and search tools, ensuring smooth data flow and enabling efficient query execution.
  
# Architecture

<img src="https://github.com/user-attachments/assets/3104b6dd-8f01-43ba-bb7c-f4a42163b2ce" alt="arch" />

### Browser Plugin Architecture
   - The browser plugin is built using Manifest V3, providing a sidebar that users can interact with. It extracts data from the websites visited by the user (with their permission) and sends it to the backend for processing. The plugin is designed to be lightweight, ensuring minimal impact on the user's browsing experience while enabling the extraction of relevant content from the pages visited.
   - **Data Flow:** When a user visits a site, the plugin captures the HTML data and sends it to the Flask backend server. The data is parsed, processed, and sent to Azure AI Search for indexing, ensuring efficient and relevant data retrieval for the Retrieval-Augmented Generation (RAG) process.

### Backend Architecture
   - The backend of the application is built using Flask and is hosted on **Azure Container Apps**, ensuring scalability and responsiveness to fluctuating demand. The Flask application is responsible for handling API requests, processing the data, and interacting with Azure services to manage embeddings, data retrieval, and LLM responses.
   - **Data Flow:** Once the data is received from the browser plugin, it is parsed and stored in **Azure AI Search** using custom indexing methods. This allows for fast and contextually relevant retrieval during the RAG process, where the data is passed to the **LLAMA 7B** model hosted in **Azure ML Studio**. The model generates context-aware responses, which are sent back to the plugin for display to the user.

# Team

### Team Name: Bitspace

#### Team Members:

- **Aswath T**: [GitHub Profile](https://github.com/t-aswath)
- **Naveen M P**: [GitHub Profile](https://github.com/navi-prem)
- **Rahul Navneeth**: [GitHub Profile](https://github.com/RahulNavneeth)
- **Surya Prakash**: [GitHub Profile](https://github.com/suryaaprakassh)
- **Valan Tamil Dasan**: [GitHub Profile](https://github.com/Valan-Tamil-Dasan)

# Contribution

We welcome contributions and feedback from the community to enhance our document validation solution. Your insights are invaluable in shaping the future of this project. 

- **Contributions**: We encourage developers to contribute code, documentation, and ideas to improve functionality and usability.
- **Feedback**: Please share your thoughts and experiences to help us identify areas for improvement and feature enhancements.
- **Issue Reporting**: If you encounter any issues, we invite you to raise them through our issue tracker, ensuring that we can address them promptly.

Together, we can create a more robust and effective solution for document validation within the Azure ecosystem.
