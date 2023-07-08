# DocGenie: Converse with Documentations

Welcome to the DocGenie GitHub repository! DocGenie is a powerful documentation helper that allows you to interact with documentation in a convenient and conversational manner. With DocGenie, you can query documentation, ask questions about how to use a certain package, explore examples, and much more.
<div>
  <img style="align:center;" src="https://github.com/Adarshdgr8/DocGenie/assets/89144373/92adf8ee-e002-44c4-9cbb-d70fd132e14c" alt="DocGenie Logo" width="160">
</div>

## Project Overview
The goal of this project is to build an end-to-end solution for interacting with documentation. This involves running a chain that processes the documentation and provides relevant information, as well as developing a user-friendly front end and user interface for seamless interaction. We will cover various topics such as vector databases, retrieval similarity, search memory inside a chat, and Streamlit, a package that simplifies front-end development. Additionally, we will explore the Lang chain source code to understand the underlying mechanisms.

## Project Phases
The project consists of the following phases:

### Documentation Chain: 
In this phase, we will select a documentation chain (taking Langchain documentation as an example) and download it. We will then process the documentation by converting each page into chunks and embedding them as vectors. These vectors will be stored in a vector store.

### Chain Implementation: 
The second phase involves writing a chain that utilizes the vector database to retrieve the relevant chunks needed to answer user queries. This chain will be responsible for providing accurate and context-aware responses based on the documentation.

### User Interface: 
In the third phase, we will implement a user interface using Streamlit, a user-friendly package for building interactive web applications. The interface will enable users to interact with the documentation by asking questions, exploring examples, and receiving informative responses.

### Memory Integration: 
The final phase focuses on integrating memory into the chat functionality. This enhancement will enable the chat to remember previous interactions and refer back to them when needed, enhancing the conversational experience.

## Team Members
The DocGenie project is developed by a dedicated team of individuals with a passion for technology and a drive for excellence. Meet our team members:

* #### [Adarsh Singh](https://www.linkedin.com/in/adarsh-singh-b17640202/)
* #### [Vishal Singh](https://www.linkedin.com/in/vishal-singh-vsks/)
* #### [Nidhi Rajani](https://www.linkedin.com/in/nidhi-rajani-b13005217/)
* #### [Muskan Bansal](https://www.linkedin.com/in/muskan-bansal-102101232/)
* #### [Arpit Awasthi](https://www.linkedin.com/in/arpit-awasthi-275890203/)


We are students from MANIT Bhopal, Batch of 24, and we are excited to collaborate on this innovative project.

## Contributions and Feedback
We welcome contributions to enhance the functionality and usability of DocGenie. If you encounter any issues, have suggestions for improvements, or want to provide general feedback, please open an issue. We appreciate your input!


Thank you for your interest in DocGenie! We hope this documentation helper enhances your experience with package documentation and provides a seamless and informative interaction. Happy exploring and coding!
