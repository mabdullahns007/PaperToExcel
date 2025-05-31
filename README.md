# Paper to Excel 📊

An AI-powered OCR tool that extracts data from handwritten ledger pages and converts them into structured CSV files. Built with Langchain and powered by Google's Gemini 1.5 Flash for advanced image processing and text recognition.

## 🚀 Features

- **Handwritten Text Recognition**: Extract data from handwritten ledger pages with high accuracy
- **Intelligent Data Structuring**: Automatically organize extracted data into proper columns and rows
- **CSV Export**: Generate clean, structured CSV files ready for Excel or other spreadsheet applications
- **Image Processing**: Handle various image qualities and formats

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Langchain**: For interaction with LLM.
- **Google Gemini 1.5 Flash**: Advanced OCR and image processing
- **OpenCV**: Image preprocessing and enhancement
- **Pandas**: Data manipulation and CSV generation
- **Streamlit**: Web interface for demos and user interaction

## 📋 Prerequisites

Before running this application, make sure you have:

- Python 3.8 or higher
- Google Gemini API key
- Required Python packages (see requirements.txt)

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mabdullahns007/paper-to-excel.git
   cd paper-to-excel
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **replace st.secrets["google_api_key"] with your api Google Api Key**


## 🌐 Live Demo

![image](https://github.com/user-attachments/assets/4893a5dc-ff35-45e4-a8b0-3cab88a8a181)
![WhatsApp Image 2025-05-31 at 6 04 28 PM](https://github.com/user-attachments/assets/e5149c72-01e2-4061-9a47-f1e9aaca5c48)
![image](https://github.com/user-attachments/assets/71437533-4d48-4584-8234-1f3f8a3ff52c)




## 🎯 How It Works

1. **Image Preprocessing**: Enhances image quality, adjusts contrast, and removes noise
2. **OCR Processing**: Uses Google Gemini 1.5 Flash to extract text from the processed image
3. **Data Parsing**: Intelligently identifies table structures and data relationships
4. **Data Validation**: Checks for consistency and common ledger patterns
5. **CSV Generation**: Structures the data into clean CSV format


## 📈 Performance

- **Accuracy**: 85-95% depending on handwriting quality
- **Processing Speed**: ~2-5 seconds per image
- **Supported Formats**: JPG, PNG, TIFF, BMP
- **Max Image Size**: 10MB per image

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- [Google AI](https://ai.google.dev/) for Gemini 1.5 Flash API
- [OpenCV](https://opencv.org/) community for image processing tools
- [Pandas](https://pandas.pydata.org/) team for data manipulation capabilities
- [Streamlit](https://streamlit.io/) for the amazing web framework

## 📞 Contact

**M. Abdullah Naqshband Sani**
- Email: abdullahkhan14625@gmail.com
- GitHub: [@mabdullahns007](https://github.com/mabdullahns007)
- LinkedIn: [www.linkedin.com/in/abdullah-khan-43a135324]


⭐ **Found this helpful? Give it a star!** ⭐
