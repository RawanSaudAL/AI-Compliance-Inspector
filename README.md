# AI-Compliance-Inspector
An AI-driven compliance verification system that leverages Retrieval-Augmented Generation (RAG) and LLaVA to automate compliance checks. This project combines text-based and visual data analysis to ensure accurate and efficient validation against standardized regulations.


# Project Overview
The I-Compliance-Inspector aims to streamline the compliance verification process by integrating RAG for dynamic text retrieval and LLaVA for visual data analysis. This hybrid approach enhances accuracy and reduces manual workload in compliance checking.

# Objective:
Automate compliance verification using a combination of text retrieval and image analysis.

Improve accuracy and efficiency in identifying compliance discrepancies.

# Features
Dynamic Text Retrieval: Uses RAG to extract relevant compliance information from large datasets.

Visual Data Analysis: Utilizes LLaVA to analyze scanned documents, forms, and other visual content.

Hybrid Assessment: Combines text and image data to provide comprehensive compliance reports.

Fast and Accurate: Significantly reduces manual verification time while maintaining high accuracy.

# Technologies Used
Python 3.9+

RAG (Retrieval-Augmented Generation)

LLaVA (Language and Vision Analysis)

PyTorch

Transformers

Tesseract OCR (for text extraction from images)

FAISS (for vector-based similarity search)

# Installation
Clone the repository:

git clone https://github.com/username/I-Compliance-Inspector.git
cd I-Compliance-Inspector
Create a virtual environment:

python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
Install required packages:

pip install -r requirements.txt
Install Tesseract OCR:

On Ubuntu:

sudo apt-get install tesseract-ocr
On Windows:
Download and install from Tesseract GitHub.

Usage
Run the compliance checker:

python main.py --input /path/to/document.pdf
Specify mode:

--text-only for text compliance

--image-only for visual compliance

--hybrid for both

Output:

Compliance status

Detailed report with identified discrepancies

Confidence scores for each compliance rule


# Results
The AI-Compliance-Inspector demonstrated:

High accuracy in detecting non-compliance by combining text and visual data.

Faster compliance checks compared to manual methods.

Effective handling of both structured and unstructured documents.

Sample Output:

Compliance Check Result:
- Status: Non-Compliant
- Reason: Missing mandatory document in section 4.1
- Confidence: 92.3%
Contributing
Fork the project.

Create your feature branch:


git checkout -b feature/YourFeature
Commit your changes:

git commit -m "Add your feature"
Push to the branch:


git push origin feature/YourFeature
Open a pull request.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.








