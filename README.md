# 🧠 Daily Phrases Anki Deck

A structured **Anki deck generator** for learning everyday English through **phrases, examples, and audio**.

Built with Python 🐍 using `genanki` + `gTTS`.

---

## ✨ Features

* 📚 **22 тематических субдека**
* 🧩 Фразы разбиты на логические категории (work, travel, emotions, etc.)
* 💬 Каждая фраза:

  * перевод 🇷🇺
  * пример использования
  * аудио 🔊
* 🎧 Автоматическая генерация аудио (gTTS)
* 🧱 Чистая структура Anki: `Daily_Phrases::Category`

---

## 📊 Deck Overview

* 📁 Subdecks: **22**
* 🧠 Total cards: **1652**
* 🔊 Audio included for:

  * phrases
  * examples (when present)

---

## 📂 Structure in Anki

```
Daily_Phrases
├── Work adverbs 💬
├── communication 💬
├── daily_habits_productivity ⚙️
├── evening_routine 🌙
├── feeling_words 🧠
├── future_forms ⏳
├── greetings 😊
├── happiness 😊
├── Answers to How are you? 🙂
├── IT & Engineering 💻
├── morning_routine 🌅
├── motivation_self_improvement 🔥
├── movement & getting around ▶️
├── nourishment 🍽
├── opinion_starters 💭
├── phrasal_verbs ⚡
├── presence_lack_addition_reduction 📉
├── preservation_position 🧍
├── shopping 🛍️
├── travel 🌍
├── Verbs of Perception & Work 🧠
├── work_phrases 💼
```

---

## 🧩 Content Design

All phrases are provided in a **structured format**:

* ✅ Each entry contains:

  * English phrase
  * Russian translation
* ➕ Additionally:

  * Example sentence *(if available)*
  * Audio for phrase
  * Audio for example *(optional)*

👉 This means:

* some cards are **standalone phrases**
* others are **context-enhanced with examples**

---

## ⚙️ How It Works

* JSON files → define topics and phrases
* Python script:

  * generates stable IDs (MD5-based)
  * creates Anki notes
  * generates audio files
* Output:

  ```id="out1"
  Daily_Phrases.apkg
  ```

---

## ⚠️ Notes

* Large `.apkg` file (~60MB) → GitHub warning expected
* Can be optimized via Git LFS if needed

---

## 🛠 Tech Stack

* Python 🐍
* genanki
* gTTS
* JSON datasets

---

## 💡 Idea

The goal is to help you **think in English**, not just translate:

* short phrases → fast recall
* examples → real usage
* audio → pronunciation

---


