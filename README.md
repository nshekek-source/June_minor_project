# 📊 GroupDNA - WhatsApp Chat Analyzer

![Python](https://img.shields.io/badge/Python-3.10-blue)
![NumPy](https://img.shields.io/badge/NumPy-2.x-orange)
![Google Colab](https://img.shields.io/badge/Google-Colab-yellow)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## Overview

GroupDNA is a WhatsApp Group Chat Analyzer built using **Python Fundamentals** and **NumPy**.

The application reads exported WhatsApp chats and generates a detailed analytics report describing user activity, communication behavior, favourite words, activity patterns, and personality archetypes.

The project focuses on solving a real-world text analytics problem without using advanced data analysis libraries such as Pandas or Matplotlib.

---

## Features

- Parse WhatsApp exported chat
- Detect participants
- Count total messages
- Detect media messages
- Detect deleted messages
- Skip system messages
- Hour-wise activity analysis
- Weekday activity
- Daily activity
- Monthly activity
- Top active users
- Ghost user detection
- Word frequency analysis
- NumPy 24×7 Activity Heatmap
- Personality Archetypes
- Console Report Generation

---

## Technologies Used

- Python
- NumPy
- Regular Expressions
- Collections
- Datetime
- Google Colab

---

## Folder Structure

```text
GroupDNA/
│
├── GroupDNA.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── hostel_bois.txt
├── GroupDNA_Report.txt
├── screenshots/
└── assets/
```

---

## Dataset

Input format

```text
DD/MM/YY, HH:MM - Sender: Message
```

Example

```text
01/04/24, 09:15 - Rahul: Good Morning
01/04/24, 09:16 - Priya: Have breakfast
01/04/24, 09:20 - Aman: <Media omitted>
```

---

## Analytics Performed

✔ Messages Per User

✔ Active Days

✔ Hour-wise Activity

✔ Daily Activity

✔ Weekly Activity

✔ Monthly Activity

✔ Media Analysis

✔ Deleted Messages

✔ Word Frequency

✔ Activity Heatmap

✔ Personality Detection

✔ Group Statistics

---

## Personality Types

- 🌙 Night Owl
- 🔥 Spammer
- 👻 Ghost
- 📚 Story Teller
- 📷 Meme Lord
- ⚡ One Liner
- 😊 Balanced User

---

## Sample Output

```text
GROUPDNA REPORT

3174 Messages
6 Members

Rahul     ████████████████████ 953

Priya     ████████████████ 718

Neha      █████████████ 635

Aman      ██████████ 490

Karan     ████████ 354

Vikas     █ 24
```

---

## How to Run

Clone Repository

```bash
git clone https://github.com/yourusername/GroupDNA.git
```

Install Requirements

```bash
pip install -r requirements.txt
```

Run the notebook inside Google Colab.

Upload hostel_bois.txt

Run all cells.

---

## Future Improvements

- Emoji Detection
- Sentiment Analysis
- PDF Report Generation
- Interactive Dashboard
- Better Personality Detection
- Response Time Analysis

---

## Learning Outcomes

- Python Fundamentals
- File Handling
- Dictionaries
- Lists
- Sets
- Functions
- NumPy
- Regular Expressions
- Data Analysis
- Console Formatting

---

## Author

**Navin Kumar**

B.Tech CSE (Data Science)

SRM Institute of Science and Technology

---

## License

This project is licensed under the MIT License.
