# 🧬 GroupDNA – WhatsApp Group Chat Analyzer

**Discover the hidden patterns, personalities, and activity inside your WhatsApp group!**

GroupDNA is a Python-based WhatsApp Group Chat Analyzer that processes exported WhatsApp conversations and transforms raw chat data into meaningful insights.

The project uses Python and NumPy to explore group participation, messaging behaviour, communication patterns, and individual chat habits.

## 🚀 Features

- **Participant Analysis:** Identifies group members and calculates their message contributions.
- **Activity Analysis:** Finds the busiest days and hours of the group.
- **Hourly Activity:** Examines messaging patterns throughout the day.
- **Word Analysis:** Identifies frequently used words in conversations.
- **Response Analysis:** Estimates response speeds between participants.
- **Silent Streak Detection:** Identifies periods of inactivity.
- **Personality Classification:** Categorizes participants into eight fun, heuristic-based archetypes:
  - Spammer
  - Group Mom
  - Night Owl
  - Storyteller
  - Drama Queen
  - Ghost
  - Comedian
  - Question Master

## 🛠️ Technologies Used

- Python
- NumPy
- Google Colab
- Jupyter Notebook
- Python Datetime Module

## 📂 Project Structure

```text
GroupDNA/
│
├── GroupDNA_project.ipynb
├── hostel_bois.txt
└── README.md
```

| File | Description |
|---|---|
| `GroupDNA_project.ipynb` | Main Python analysis notebook |
| `hostel_bois.txt` | WhatsApp chat dataset |
| `README.md` | Project documentation |

## ⚙️ How to Run

1. Clone or download this repository.
2. Open Google Colab.
3. Upload `GroupDNA_project.ipynb`.
4. Upload `hostel_bois.txt` when required.
5. Run all notebook cells sequentially.
6. Explore the generated chat analysis and insights.

## 📊 Dataset

The project uses an exported WhatsApp group conversation stored in `hostel_bois.txt`.

The dataset contains messages from multiple participants and is used to analyse:

- Message frequency
- Participant contributions
- Communication timing
- Frequently used words
- Response patterns

System events and unsupported message types are excluded from the analysis.

## 🎯 Project Objective

The main objective of GroupDNA is to demonstrate how basic programming concepts and numerical computing can be used to extract meaningful information from everyday conversations.

It combines data processing, logical analysis, and statistical calculations to understand how a WhatsApp group communicates.

## 🔮 Future Improvements

- Interactive data visualizations.
- More advanced behavioural analysis.
- Improved response-time calculations.
- Machine learning-based chat pattern classification.
- Support for multiple WhatsApp chat datasets.

## 👨‍💻 Project

**GroupDNA – WhatsApp Group Chat Analyzer**

Developed as a Python-based data analysis project using NumPy.

---

⭐ If you find this project interesting, feel free to explore the repository!
