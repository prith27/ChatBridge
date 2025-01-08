# ChatBridge: Interactive Document Query System

ChatBridge is a notebook-based system designed for document analysis and conversational queries. It allows users to upload files, process their content, and interact with the extracted information using OpenAI embeddings. This notebook leverages Gradio to provide a simple and interactive interface.

---

## Features

- **File Upload**: Analyze PDF and text files by uploading them.
- **OpenAI-Powered QA**: Ask questions about your document's content through AI-driven embeddings.
- **Chat Interface**: Engage in conversations while maintaining chat history.
- **Error Handling**: Informs users about issues like unsupported formats or password-protected PDFs.

---

## Usage

1. Open the `.ipynb` notebook file in Jupyter Notebook or any compatible IDE like JupyterLab.
2. Run all the cells sequentially to initialize the app.
3. Use the Gradio interface to:
   - Upload a file.
   - Analyze the document.
   - Ask questions about the document content.

---

## Deployment

This notebook is designed for experimentation and development purposes. To deploy the solution:

1. Extract relevant functions and code into a `.py` script or module.
2. Set up the Gradio app in a production environment.
3. Host the application on platforms like:
   - **Streamlit Cloud**
   - **AWS, GCP, or Azure**
   - **Dockerized containers for scalability**

---

## Notes

- The notebook includes functions for loading documents, creating embeddings, and processing user queries.
- For persistent deployments, implement long-term storage for the FAISS vector store.

---

## Error Handling

- **No File Uploaded**: Prompts users to upload a file before proceeding.
- **Password-Protected PDFs**: Alerts users and skips unsupported files.
- **Unsupported Formats**: Handles and informs users of unsupported file types.

---

## Customization

Feel free to customize the notebook for your use case, whether it's extending functionality or adapting the UI.

---

## License

This project is open-source and available for modification under the MIT License.

---

## Contributors

- **Prithvi Seshadri**: Creator and Developer
- Powered by OpenAI and Gradio tools.
