# AI-Resume-Optimiser-Generator
An AI-powered tool that takes a candidate’s resume (PDF/DOC) and a target job description (text), then produces:

A tailored, ATS-friendly optimised resume

A summary of changes including keyword insertions, formatting tweaks, and ATS optimisations

This project is ideal for job seekers who want to quickly adapt their resumes for different job roles.

🚀 Features
Resume Parsing – Reads resumes from PDF or DOC formats

Job Description Analysis – Extracts skills and keywords from JD text

AI Optimisation – Rewrites and updates resume to align with the target role

ATS Compliance – Ensures formatting and keyword usage are ATS-friendly

Change Report – Summarises edits and optimisations applied to the resume

🛠 Tech Stack
Python – Core programming language

ReportLab – PDF generation

python-docx – DOCX reading and editing

PyPDF2 / pdfplumber – PDF parsing

spaCy / NLTK – NLP keyword extraction

OpenAI API – AI-powered rewriting and optimisation

📂 Project Structure
bash
Copy
Edit
.
├── data/                   # Sample resumes and job descriptions
├── scripts/                # Resume parsing, keyword extraction, AI optimisation
├── outputs/                # Optimised resumes and change reports
├── requirements.txt        # Python dependencies
├── main.py                  # Entry point script
└── README.md               # Project documentation
📥 Installation
bash
Copy
Edit
# Clone repository
git clone https://github.com/your-username/ai-resume-optimiser.git
cd ai-resume-optimiser

# Install dependencies
pip install -r requirements.txt
▶️ Usage
bash
Copy
Edit
python main.py --resume "candidate_resume.pdf" --jd "job_description.txt"
Arguments:

--resume : Path to candidate resume (PDF/DOC)

--jd : Path to job description text file

📌 Example
Input:

Candidate Resume: Priya_Sharma_Resume.pdf

Job Description: Full Stack Developer - Fintech Solutions

Output:

Priya_Sharma_Resume_Optimised.pdf (ATS-friendly, tailored resume)

change_report.txt (summary of modifications)

📄 Sample Change Report
Change Type	Description
Keyword Added	Added “Spring Boot” and “AWS” under Skills section
Formatting	Updated section headings for ATS parsing
Role Alignment	Rephrased “internal web applications” to “fintech web applications”

🤝 Contributing
Pull requests are welcome!
For major changes, please open an issue first to discuss your ideas.

📜 License
This project is licensed under the MIT License.

