# 🧠 UKM FAQ Chatbot

A **rule-based chatbot** built using **spaCy** to assist users with frequently asked questions related to **Universiti Kebangsaan Malaysia (UKM)**. The chatbot can handle common inquiries such as admissions, courses, tuition fees, library hours, and contact information — all in real-time through simple keyword-based intent recognition and lemmatization.

## ✨ Features

- Rule-based intent detection using **spaCy's** NLP model (`en_core_web_sm`)
- Handles common intents: Greeting, Admission, Courses, Fees, Library, Contact, and Farewell
- Preprocessing with lemmatization and stopword removal
- Real-time feedback collection from users
- Evaluation metrics tracking: total queries, correct responses, unknown intents, response time
- Command support for `exit` and `help` prompts

## 📚 Example Intents

| Intent       | Sample Keywords       | Example Questions                                  |
|--------------|-----------------------|-----------------------------------------------------|
| Greeting     | hello, hi, hey        | "Hello there!"                                      |
| Admission    | admission, apply      | "How do I apply to UKM?"                            |
| Courses      | course, program       | "What postgraduate programs are available?"         |
| Fees         | tuition, cost         | "How much are the tuition fees?"                    |
| Library      | library, timing       | "What time does the library open?"                  |
| Contact      | phone, email          | "How can I contact UKM?"                            |
| Goodbye      | bye, later            | "Thanks, bye!"                                      |

## 📈 Evaluation Metrics
After the chat session, the bot provides:

Total queries

Correct response count

Unknown query rate

Average response time

User feedback (yes/no) is collected after each response to help assess chatbot effectiveness.

## 🔗 Useful Links
UKM Official Portal

UKM Admission Info

UKM Library

UKM Contact Directory

## 🛠 Technologies Used
Python

spaCy (Natural Language Processing)

## 🚀 Getting Started

### Prerequisites

- Python 3.6+
- [spaCy](https://spacy.io/)
- Download the English model:

```bash
pip install spacy
python -m spacy download en_core_web_sm



