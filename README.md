# Resume Parser

![Last Commit](https://img.shields.io/github/last-commit/nisch-mhrzn/SmartResumeParser)  
![Repo Size](https://img.shields.io/github/repo-size/nisch-mhrzn/SmartResumeParser)  
![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue)  
![License](https://img.shields.io/badge/license-MIT-green)

## 📄 Project Overview
The **Resume Parser** project is designed to extract useful information from resumes such as skills, contact details, and email addresses using Python. It provides an efficient solution for recruiters and organizations to automate resume screening.

### Features:
- Extracts contact numbers, email addresses, and skills.
- Processes resumes in PDF format.
- Clean and preprocesses textual data for analysis.
- Skill matching with predefined skill sets.

---

## 🚀 Technologies Used
- **Python**: For script development.
- **Scikit-learn (sklearn)**: For handling data processing and potential model integration.
- **Seaborn (sns)**: For visualizing data insights.
- **Pandas**: For data manipulation and analysis.

---

## 📦 Installation
### Prerequisites:
- Python 3.8+
- pip package manager

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/nisch-mhrzn/SmartResumeParser.git
   cd SmartResumeParser
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🛠 Usage
1. Place resume PDFs in the designated folder (e.g., `resumes/`).
2. Run the main script to parse the resumes:
   ```bash
   python main.py
   ```
3. View extracted data in the terminal or the generated output file.

---

## 🧩 Key Functions
### `cleanResume(txt)`
Cleans the textual content by removing URLs, special characters, and unnecessary whitespace.

### `extract_skills_from_resume(text)`
Identifies and extracts skills from the text using a predefined skills list.

### `extract_contact_number_from_resume(text)`
Extracts a contact number using pandas for structured handling.

### `pdf_to_text(file)`
Converts a PDF file to plain text for parsing.

---

## 📂 Project Structure
```plaintext
resume-parser/
├── resumes/             # Folder containing input PDF resumes
├── skills_list.py       # Predefined skills list
├── main.py              # Main script
├── requirements.txt     # Dependencies
├── utils.py             # Utility functions
└── README.md            # Project documentation
```

---

## 👨‍💻 Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request.

---

## 📝 License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 🌟 Show Your Support
If you find this project useful, please star the repository and share it with others!

---

## 📧 Contact
For any inquiries, reach out to:
- Email: yourname@example.com
- GitHub: [yourusername](https://github.com/yourusername)

