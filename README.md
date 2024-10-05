# Multi Language Invoice Extractor Application

![image_alt](https://github.com/jerryjohn1995/Multi-Language-Invoice-Extractor/blob/0f3eac2d3f357b6997946f1efe021b15c4df2ef2/Img%201.png)

## Overview
Welcome to the Multi-Language Invoice Extractor Application repository! This project is designed to automate the extraction of data from various types of invoices, including handwritten and printed invoices, in multiple languages. Using Google Gemini as the primary Large Language Model (LLM) for data extraction and query handling, the application provides a seamless experience to upload invoices, extract critical information, and receive responses to user queries in real-time.

## Features
The Multi-Language Invoice Extractor is built to streamline the process of managing and analyzing invoice data. Key features include:

**1.Multi-format Invoice Support:**
- Extract data from handwritten or printed invoices in various languages.

**2.Intuitive User Interface Built with Streamlit:**

- Allows users to easily upload invoices.
- Displays uploaded invoices for visual confirmation.
- Provides a prompt input field for users to ask specific questions about the invoice.
  
**3. Deployed on Hugging Face:**
- The application is hosted on Hugging Face, making it accessible from anywhere and ensuring smooth and scalable deployments.

**4.Intelligent Query Handling:**
- Using Google Gemini as the LLM, users can ask complex, context-aware queries such as:

“Give a summary about the invoice.”

“Show only the item numbers.”

“List the food items in the invoice.”

“What is the total amount due?”

**5.Real-time Data Extraction and Responses:**
- The extracted information is processed and displayed immediately on the interface, making it easy for users to understand invoice details and get answers to their queries.

## Technologies Used

**1.Python**
Primary language for backend development and API integration.

**2.Google Gemini API**
Used for both data extraction from invoices and LLM-based query processing, providing a unified solution for reading and understanding invoice data.

**3.Streamlit**
Used for creating a responsive, user-friendly front-end interface. 

**4.Hugging Face**
Platform used for deploying the application, providing easy access and hosting. 

## Getting Started
To get started with the Custom Invoice Extractor application, follow these steps:

**1. Clone the Repository:**

```python
git clone https://github.com/YourUsername/Custom-Invoice-Extractor.git
cd Custom-Invoice-Extractor

```
**2. Install the Required Dependencies:** Make sure you have `pip` installed. Then run:
```python
pip install -r requirements.txt
```
**3. Set Up the Google Gemini API Key:** Create a `.env` file in the root directory and add your Google Gemini API key as follows:
```python
GEMINI_API_KEY=your_gemini_api_key_here

```
**4. Run the Application:** Use the following command to start the `Streamlit` application:
```python
streamlit run app.py
```
The application will start running locally, and you can access it by opening the URL provided by Streamlit.

**5. Access the Application on Hugging Face:**  Alternatively, you can access the deployed version of the application on Hugging Face using the following link:
 [Deployed Application on Hugging Face](https://huggingface.co/spaces/jerryjohn1995/Multi_Language_Invoice_Extractor)


## How to Use
**1. Upload an Invoice:** 
Drag and drop an invoice (in any supported format) onto the upload section or use the "Browse" button to select a file.

**2. View the Invoice:** 
Once uploaded, the invoice will be displayed on the interface for visual confirmation.

**3. Ask a Query:** 
Enter a specific query related to the invoice in the prompt input field, such as:

"What is the due date on this invoice?"
"Show me the list of purchased items."
**4. Submit and Get Results:** 
Click on the “Submit” button. The system will process the query using Google Gemini and display the results in the response section.

## File Structure
```python
Custom-Invoice-Extractor/
│
├── app.py                    # Main application file (Streamlit interface)
├── requirements.txt          # Project dependencies
├── .env                      # Environment file for storing API key
└── README.md                 # Project documentation

```
## Future Enhancements
The project is designed to be scalable and adaptable. Some potential future enhancements include:

- Support for Additional Document Types:
Extend functionality to support other document types such as receipts, purchase orders, and financial statements.

- Multi-Document Comparison:
Enable comparison between multiple invoices for identifying patterns or discrepancies.

- Integration with Accounting Software:
Connect to popular accounting systems like QuickBooks or Xero for streamlined financial data management.

## Contributing
Contributions are welcome! Please feel free to submit issues or pull requests if you have any suggestions or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For any questions or feedback, please feel free to reach out or connect on LinkedIn.

🔗 Follow me on LinkedIn: [LinkedIn Profile Link](https://www.linkedin.com/in/jerryjohn1995/)

🔗 Check out the project on GitHub: [GitHub Repository Link](https://github.com/jerryjohn1995/Multi-Language-Invoice-Extractor)

🔗 Access the Deployed Application on Hugging Face: [Hugging Face Link](https://huggingface.co/spaces/jerryjohn1995/Multi_Language_Invoice_Extractor)









