Installation Guide
==================

Prerequisites
-------------
- Python 3.8+
- Ollama
- Streamlit

System Requirements
-------------------
- Minimum 8GB RAM
- At least 10GB disk space
- Local GPU recommended for better performance

Installation Steps
------------------
1. Clone the repository
2. Install dependencies
3. Set up Ollama
4. Run the application

.. code-block:: bash

   # Clone repository
   git clone https://github.com/Asmae00010/RAG-application-

   # Create virtual environment
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

   # Install dependencies
   pip install -r requirements.txt

   # Run the application
   streamlit run app.py