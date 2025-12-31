##  Project Overview

**HireVerify** is a **job post verification system** designed to help **job seekers identify whether a job posting is real or fake**.
With the increasing number of fraudulent job postings, this project aims to **analyze job details and provide verification results**, improving trust and safety for candidates.

The system focuses on **job authenticity verification**, not job posting or recruitment.

##  Objective

* Detect fake or scam job postings
* Protect job seekers from fraud
* Provide quick verification based on job post details
* Increase awareness of suspicious job patterns

##  Technologies Used

* **Backend / Logic:** Python
* **Frontend:** HTML, CSS
* **ML / Logic (if used):** Rule-based or ML-based classification
* **IDE:** VS Code
* **Version Control:** Git & GitHub

##  Project Structure (Typical)

```
hireverify
│
├── static/
│   └── css/
│
├── templates/
│   └── index.html
│
├── app.py
├── model.py   (if ML logic exists)
├── requirements.txt
└── README.md
```

##  How It Works

1. User enters **job post details** (company name, description, email, etc.)
2. The system analyzes the input using:

   * Predefined rules or
   * Machine learning logic (if implemented)
3. Job post is classified as:

   *  **Real Job**
   *  **Fake Job**
4. Result is displayed to the user

##  Key Features
* Fake job detection
* Simple and user-friendly UI
* Fast verification results
* Helps prevent job scams
* Focused on job seeker safety

##  How to Run the Project

### 1️ Clone Repository

```bash
git clone https://github.com/Y-Harika/hireverify.git
```

### 2️ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️ Run Application

```bash
python app.py
```

Open browser:

```
http://localhost:5000
```

##  Future Enhancements

* Improve accuracy using **ML models (NLP)**
* Add job post source verification
* Provide confidence score
* Deploy application online
* Add warning indicators for suspicious fields



##  Conclusion

HireVerify demonstrates a **practical approach to detecting fake job postings** using Python and web technologies. The project addresses a real-world problem faced by job seekers and emphasizes **security, trust, and usability**. It strengthened my understanding of **data analysis, validation logic, and end-to-end application development**, making it highly relevant for **software development and AI/ML roles**.

