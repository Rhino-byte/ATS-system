
![image](https://github.com/user-attachments/assets/5c59e5dd-7dc6-4b88-9875-9ce6d937b6e0)




# ATS (Applicant Tracking System) with Generative AI


## 📄 Project Overview
This project demonstrates the creation of an **Applicant Tracking System (ATS)** powered by **Generative AI (GenAI)** models. The system leverages AI capabilities to streamline recruitment processes by:

- Matching candidates to job roles.
- Automating candidate communication.
- Advising on the chances that the resume provided fits the job description.
- Provides strengths and weakness of a resume in relation to a job description. 

By integrating GenAI, the ATS provides smarter, faster, and more accurate talent acquisition workflows.

---

## 🎯 Key Features
- **Resume Parsing:** Extracts key details such as name, skills, work history, and education from resumes in PDF or DOCX format.
- **Job Description Generation:** Leverages Generative AI to craft precise and engaging job descriptions for any role.
                                 Candidate Matching: Analyzes candidate profiles and job descriptions to compute compatibility scores.
- **Fit Assessment:** Provides a detailed analysis of how well a resume matches a job description and advises on overall fit chances.
                      Strengths and Weaknesses Analysis: Highlights the strengths and areas for improvement in a candidate's resume relative to a job description.
- **Automated Communication:** Drafts customized emails for candidate updates, interview invitations, or feedback.

---

## ⚙️ Tech Stack
- **Programming Language**: Python
- **Framework**: Streamlit (for the UI)
- **AI Models**: GenAI GPT models (e.g., gemini-1.5)
- **Libraries**:
  - `pandas` - Data manipulation.
  - `streamlit` - User interface.
  - `genai` - API integration for GenAI.
  - `pdf2image` - Load in a pdf and convert to image

---

## 🚀 Setup Instructions

### Prerequisites
- Python 3.10+
- GenAI API key (for GPT model usage)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ATS-GenAI.git
   cd ATS-GenAI
   ```
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up the GenAI API key:
   - Create a `.env` file in the project directory.
   - Add your API key:
     ```
     OPENAI_API_KEY=your_openai_api_key
     ```

---

## 🖥️ Usage
1. Run the application:
   ```bash
   streamlit run app.py
   ```
2. Navigate to the URL provided by Streamlit (usually `http://localhost:8501`).
3. Use the following features:
   - Upload resumes in PDF or DOCX format for parsing.
   - Input job titles to generate descriptions.
   - View candidate-job matches based on AI scores.

---

## 📚 Project Structure
```plaintext
ATS-GenAI/
│
├── app.py                # Streamlit app
├── resume_parser.py      # Resume parsing logic
├── job_description.py    # Job description generator
├── candidate_matcher.py  # Candidate ranking and matching
├── .env                  # API key file
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── data/
    ├── sample_resumes/   # Sample resumes for testing
    ├── output/           # Parsed and matched results
```

---

![image](https://github.com/user-attachments/assets/a27968cb-5bb5-4fef-a047-79a7e7ac4a2e)

## 🧪 Example Scenarios
### Scenario 1: Job Description Generation
- Input: `"Software Engineer"`
- Output: A detailed job description including roles, responsibilities, and qualifications.

### Scenario 2: Resume Parsing and Matching
- Input: A resume file and a job description.
- Output: Fit score (e.g., "85% match").
          Strengths and weaknesses analysis.
---

## 🛠️ Future Enhancements
- Integration with LinkedIn for candidate sourcing.
- Advanced analytics dashboard for recruiters.
- Support for multi-language parsing and matching.
- Integration with third-party email platforms for automated scheduling.

---

## 👨‍💻 Author
- **Nanyaemuny Savins** - [GitHub Profile](https://github.com/Rhino-byte)

---

## 📄 License
This project is licensed under the MIT License. See `LICENSE` for more details.

---

## 🙌 Acknowledgments
- **GenAI** for providing the Generative AI models.
- **Streamlit** for the interactive UI framework.
- Community contributors for testing and feedback.

---


