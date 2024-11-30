Usage Guide
==========

Starting the Application
----------------------

1. Start Ollama Server
~~~~~~~~~~~~~~~~~~~~

.. code-block:: bash

   ollama serve

2. Launch Streamlit Application
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: bash

   streamlit run app.py

Using the RAG System
------------------

Document Upload
~~~~~~~~~~~~~
1. Navigate to the upload section
2. Select your document(s)
3. Supported formats: PDF, TXT, DOCX
4. Wait for processing confirmation

Querying
~~~~~~~~
1. Enter your query in the text input field
2. Select the model you want to use
3. Adjust any relevant parameters
4. Click "Submit" to generate response

Advanced Features
---------------

Model Selection
~~~~~~~~~~~~~
* Choose from available models in the dropdown
* Configure model parameters
* View model performance metrics

RAG Configuration
~~~~~~~~~~~~~~~
* Adjust chunk size
* Modify similarity thresholds
* Configure vector store settings

Troubleshooting
-------------
Common issues and their solutions:

1. Model Loading Issues
   * Ensure Ollama is running
   * Check model availability
   * Verify system resources

2. Document Processing Errors
   * Check file format compatibility
   * Verify file permissions
   * Check file size limits