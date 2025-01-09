# ChatBridge: Interactive Document Query System

ChatBridge is a notebook-based system designed for document analysis and conversational queries. It allows users to upload files, process their content, and interact with the extracted information using OpenAI embeddings. This notebook leverages Gradio to provide a simple and interactive interface.

---

## Features

- **File Upload**: Analyze PDF and text files by uploading them.
- **OpenAI-Powered QA**: Ask questions about your document's content through AI-driven embeddings.
- **Chat Interface**: Engage in conversations while maintaining chat history.
- **Error Handling**: Informs users about issues like unsupported formats or password-protected PDFs.

---

## Functionality Overview

### Key Functions

- **`load_document`**:
  - Loads and processes a PDF or text document.
  - Handles errors like unsupported formats or password-protected PDFs.

- **`create_vectorstore`**:
  - Embeds the document content using OpenAI embeddings.
  - Stores embeddings in a FAISS vector store for efficient querying.

- **`upload_and_process`**:
  - Handles document uploads and initializes the QA chain.

- **`chat_with_document`**:
  - Processes user queries by interacting with the document's content.

### Gradio UI

- Provides a user-friendly interface for:
  - Uploading documents.
  - Analyzing and querying document content interactively.

---

## Error Handling

- **No Document Uploaded**:
  - The app gracefully informs users if no file is provided during analysis.
  
- **Unsupported File Formats**:
  - Displays a clear message when the file format is unsupported.

- **Password-Protected PDFs**:
  - Alerts users about password-protection issues and skips processing.

---

## Usage

1. Open the `.ipynb` notebook file in Jupyter Notebook or a compatible IDE.
2. Run all cells to initialize the app.
3. Use the Gradio interface to:
   - Drag and drop files for analysis.
   - Ask questions and receive responses based on the document content.

---

## Deployment

This notebook is designed for experimentation and development. To deploy the solution:

1. Refactor relevant code into a `.py` script or module.
2. Deploy the Gradio app on platforms like:
   - **Streamlit Cloud**
   - **AWS, GCP, or Azure**
   - **Dockerized containers for scalability**

---

## Notes

- The notebook includes functions for loading documents, creating embeddings, and processing user queries.
- For production environments, consider implementing persistent storage for the FAISS vector store.

---

## Screenshot

![Screenshot of ChatBridge Interface](![ChatBridge](https://github.com/user-attachments/assets/0ea7dc3c-b55b-46bb-82ac-5a1d15675fc4)
)
![ChatBridge](https://github.com/user-attachments/assets/96e2e373-1336-4303-9c05-7dfb3e56ed55)


---

## Customization

Feel free to modify the notebook for your specific use case, such as extending functionality or customizing the interface.

---

## License

This project is open-source and available for modification under the MIT License.

---

## Contributors

- **Prithvi Seshadri**: Creator and Developer
- Powered by OpenAI and Gradio tools.
