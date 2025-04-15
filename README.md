# 🔤 Sentence Analyzer Algorithm

This repository contains an algorithm designed to analyze a sentence provided by the user and output key statistics.

## 📌 Objective

Write an algorithm that processes a sentence (ending with a period `.`) **character by character** and determines:

- 📏 The **length** of the sentence (number of characters)
- ✍️ The **number of words** in the sentence (assuming words are separated by a single space)
- 🔠 The **number of vowels** in the sentence

## 💡 Approach

- Each character is read individually.
- A set of vowels (`a, e, i, o, u` in both lowercase and uppercase) is used for counting.
- A simple loop increments counters based on character conditions.

## 📂 Features

- Checks that the sentence ends with a period.
- Counts:
  - Total characters (including spaces and punctuation)
  - Words based on spaces and final period
  - Vowels from a defined vowel set


## 🛠 Technologies Used
- Pseudocode / Algorithmic Thinking
- Basic string and character manipulation

## License

This project is licensed under the [MIT License](LICENSE).
