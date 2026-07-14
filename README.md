# AI Recommendation System

## Project Information

**Project Name:** AI Recommendation System

**Internship:** DecodeLabs Industrial Training Program 2026

**Project Number:** Project 3

**Domain:** Artificial Intelligence

**Author:** Muhammad Jawad

---

# Project Overview

The AI Recommendation System is a rule-based recommendation application developed in Python. The system recommends movies based on user preferences using content-based similarity matching. It compares user input with movie attributes stored in a dataset and returns the most relevant recommendations.

This project demonstrates the core concepts of recommendation systems without using machine learning algorithms.

---

# Objectives

- Develop a logic-based recommendation system.
- Understand content-based filtering.
- Learn similarity matching techniques.
- Work with structured datasets.
- Build a professional AI portfolio project.

---

# Features

- User preference input
- Movie recommendation using similarity logic
- CSV dataset integration
- Genre filtering
- Language filtering
- Rating filtering
- Recommendation score calculation
- Top five recommendations
- Input validation
- Clean and modular Python code

---

# Technologies Used

- Python 3.x
- Pandas
- CSV
- Visual Studio Code
- Git
- GitHub

---

# Project Structure

```text
AI-Recommendation-System/
│
├── main.py
├── movies.csv
├── requirements.txt
├── README.md
├── LICENSE
│
├── screenshots/
│
└── assets/
```

---

# Dataset Structure

The application uses a CSV dataset with the following fields.

| Column | Description |
|----------|-------------|
| Movie | Movie Name |
| Genre | Movie Category |
| Language | Movie Language |
| Rating | IMDb Rating |
| Year | Release Year |

Example

| Movie | Genre | Language | Rating | Year |
|---------|---------|-----------|---------|------|
| Interstellar | Sci-Fi | English | 8.7 | 2014 |
| Avengers: Endgame | Action | English | 8.4 | 2019 |

---

# Recommendation Algorithm

The recommendation score is calculated using a rule-based similarity approach.

| Criteria | Weight |
|-----------|--------|
| Genre Match | 50 |
| Language Match | 20 |
| Rating Match | 20 |
| Recent Movie Bonus | 10 |

Maximum Score = 100

---

# System Workflow

```text
Start

↓

Load Dataset

↓

Read User Preferences

↓

Compare User Preferences with Dataset

↓

Calculate Recommendation Score

↓

Sort Results

↓

Display Top Five Recommendations

↓

Exit
```

---

# Installation

Clone the repository.

```bash
git clone https://github.com/your-username/AI-Recommendation-System.git
```

Move into the project directory.

```bash
cd AI-Recommendation-System
```

Install dependencies.

```bash
pip install -r requirements.txt
```

---

# Running the Project

```bash
python main.py
```

---

# Example Output

```text
AI RECOMMENDATION SYSTEM

Available Genres

Action
Drama
Comedy
Sci-Fi
Romance

Enter Genre:
Action

Enter Language:
English

Minimum Rating:
8

Top Recommendations

1. Avengers: Endgame
Score : 90

2. John Wick 4
Score : 90

3. The Dark Knight
Score : 90

4. Mission Impossible
Score : 80

5. Mad Max Fury Road
Score : 75
```

---

# Future Improvements

- Web-based interface using Streamlit
- Flask implementation
- Search by actor
- Search by director
- Search by year
- Search by country
- Movie poster integration
- Recommendation history
- User authentication
- Machine learning recommendation engine
- Cosine similarity
- TF-IDF based recommendation

---

# Learning Outcomes

This project demonstrates practical knowledge of:

- Recommendation Systems
- Content-Based Filtering
- Rule-Based Artificial Intelligence
- Similarity Matching
- Data Processing
- Python Programming
- Pandas Library

---

# Internship Details

Organization: DecodeLabs

Program: Artificial Intelligence Industrial Training Program 2026

Project: Project 3 – AI Recommendation Logic

---

# Author

Muhammad Jawad

Bachelor of Science in Artificial Intelligence

FAST – National University of Computer and Emerging Sciences

AI Engineering Intern

---

# License

This project is released under the MIT License.

---

# Acknowledgement

This project was developed as part of the DecodeLabs Artificial Intelligence Industrial Training Program 2026 to strengthen practical understanding of recommendation systems and similarity-based artificial intelligence techniques.
