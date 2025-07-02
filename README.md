# 🎮 NumberQuest-Unity

**NumberQuest** is a 2D educational math game template built in Unity Engine. It is designed to help learners master fundamental arithmetic skills—addition, subtraction, multiplication, division, and number patterns—through interactive quizzes with multiple-choice options and explanations.

---

## 🧠 Features

- 🧩 **Interactive Questions**: Each quiz presents a question with 4 answer options.
- ✅ **Correct Answer Checking**: Players get instant feedback with explanations.
- 📚 **Supports Multiple Topics**:
  - Addition
  - Subtraction
  - Multiplication
  - Division
  - Skipping Numbers (Patterns)
- 🔁 **Looping Quiz System**: Automatically moves to the next question.
- 🎨 **Simple UI**: Easy to customize for classrooms or educational apps.
- 🧩 **Expandable Template**: Add your own questions, levels, or categories.

---

## 🛠️ Project Structure

NumberQuest-Unity/
├── Assets/
│ ├── Scripts/
│ │ ├── Question.cs # Question data model
│ │ └── QuestionManager.cs # Manages question loading and answer checking
│ ├── Scenes/
│ │ └── MainMenu.unity # Game scene with UI and logic
│ ├── Prefabs/ # (Optional) Reusable UI prefabs
│ ├── Sprites/ # (Optional) Icons or backgrounds
│ └── Data/ # (Optional) JSON question files
├── ProjectSettings/
├── README.md


---

## 🚀 How to Use This Template

1. **Clone or Download the Repository:**
   ```bash
   git clone https://github.com/your-username/NumberQuest-Unity.git
Open the Project in Unity:

Open Unity Hub

Click "Add" and select the cloned project folder

Setup Your Questions:

In the Unity Editor, select the QuestionManager GameObject

In the Inspector, add your list of Question objects manually

Enter:

questionText

options[]

correctOptionIndex

explanation

category

Run the Game:

Press Play

Answer questions and see feedback instantly

| Field         | Value                     |
| ------------- | ------------------------- |
| Question Text | What is 6 × 7?            |
| Options       | \["42", "36", "48", "40"] |
| Correct Index | 0                         |
| Explanation   | 6 times 7 equals 42.      |
| Category      | Multiplication            |


📈 Future Enhancements
Load questions from external JSON/CSV files

Add difficulty levels and timed challenges

Add scoring and XP system

Create themed levels (space, jungle, castle)

Export for Android/iOS/WebGL

📄 License
This project is licensed under the MIT License.
Feel free to use, modify, and distribute this template for educational or commercial use.

🤝 Contributing
Pull requests and contributions are welcome. If you have question packs, UI enhancements, or performance fixes, feel free to fork and submit a PR.

🙌 Credits
Built by FatmiedAcademy
Using Unity 2D Engine & C#
Created to help learners improve their arithmetic skills through play.


