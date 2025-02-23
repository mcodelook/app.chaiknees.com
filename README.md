# ⭐ Chaiknees is now available! ⭐ [Chaiknees](https://www.chaiknees.com/)
[User manual](https://github.com/mcodelook/app.chaiknees.com/blob/main/Chaiknees%20documentation-1.2.0.alpha.pdf) for version 1.2.0-alpha
I am excited to introduce **Chaiknees**, a learning tool for Chinese language learners! This alpha release includes core functionality, setting the foundation for future updates.

---

## 🔹 Core Features

### **User Account & Settings**

- Firebase authentication.
- Light and dark mode toggle.
- Backup every 3 days.
- Feedback after each answered question, displaying the correct answer.

### **Dictionary**

- Two dictionary modes:
  - **Normal:** Concise definitions.
  - **Difficult:** Extended definitions using CC-Cedict.
- Vocabulary learning based on **HSK 2.0 (1-6)** and **HSK 3.0 (1-9)** standards.
- Constantly evolving dictionary with cleaned definitions (removing uncommon names and places).
- Words and characters have a **popularity index** based on usage frequency.
- Users can **create and manage their own dictionary**.
- Tracking of known characters to enhance writing practice.
- Over 60.000 example sentences with audio

### **Learning & Review**

- **Question Types:**
  - Character recognition, audio, pinyin, and translation.
  - Answer formats: **Multiple choice (ABCD)** and **Typing**.
    - **ABCD questions:**
      - Character-based: Similar radicals or stroke numbers to improve recognition.
      - Single pinyin words: Focuses on tone variations.
    - **Typing:** Case insensitive and allows spaces.
    - **Pinyin typing:** Must use numerical tone marks (e.g., 的 = de5).
- **Spaced Repetition System (SRS)**:
  - 4 statistics per word: **Hanzi, Pinyin, Audio, Translation**.
  - Each statistic can reach **level 14**.
  - Levels **above 6** enter **review mode**, increasing intervals:
    - Level 6: 3 days, Level 7: 1 day, Level 8: 3 days, Level 9: 7 days, Level 10: 14 days
    - Level 11: 30 days, Level 12: 60 days, Level 13: 150 days, Level 14: 365 days
- **Review Mode**:
  - Words at level 6+ are reviewed.
  - Incorrect answers decrease the level until success.
- **Difficult Mode**: Focus on hard words with customized stat adjustments.
- **HSK Progression**: Completing all words in an HSK level unlocks the next level.

---

## 🔹 User Interface

### **Dashboard**

- **About You**: Tracks review time, HSK level, and difficult words.
- **Calendar**: Displays scheduled reviews.
- **HSK Learning Sections**: Shows active learning levels.

### **Words & Dictionary Management**

- **Filters**: Ignored, favorite, difficult, reviewing, brewing.
- **Word List**:
  - **HSK Sections**: Organized by proficiency levels.
  - **User Words**: Personal dictionary entries.
  - **Add New Words**:
    - Search by **known characters, word, or definition**.
    - Words **must be built from known characters**.
- **Word Cards**:
  - Shows definitions, pronunciation, and examples.
  - Statistics tracking (**Hanzi, Pinyin, Audio, Translation**).
  - Popularity ranking.
  - Interactive actions:
    - Play audio ▶️
    - Favorite ❤️
    - Ignore 🚫
    - Adjust learning level ⏩
    - Reset progress 🗑️
    - Remove user-added words ↺

### **Characters**

- Personal character set for word construction.
- Each character has a detailed card:
  - Popularity, radical, stroke count, and translation.
- **Hanzi Strokes**: Uses **Hanzi Writer**, a highly reliable tool.
- **Word Composition**:
  - **Head Words**: Words starting with a character.
  - **Tail Words**: Words ending with a character.
  - **Middle Words**: Words containing a character.

### **Learning Sessions**

- **New Word Introduction**:
  - Displayed when encountering an unfamiliar word.
  - Contains full word card details.
- **Progress Tracking**:
  - Each HSK level has 4 tracked statistics.
  - Decorative images enhance learning experience.
- **Answer System**:
  - Immediate feedback after each answer.
  - Simplified word card displayed post-answer.

---

## 🔹 Additional Features

- **HSK View & Dashboard**: When all words are either learned (level 6+), ignored, or reviewed, a **button will appear** to progress to the next level.
- **Error Handling**: Users receive clear error messages when something goes wrong.
- **Bug Reporting**: Bugs are logged for future fixes.
- **Keyboard Support**:
  - **Enter**: Proceed to next question.
  - **1-6 keys**: Select answers in multiple-choice questions.

---

Stay tuned for updates, and happy learning! 🎉

