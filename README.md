# 🧠 Daily Phrases Anki Deck

A structured **Anki deck generator** for learning everyday English through **phrases, examples, and audio**.

Built with Python 🐍 using `genanki` + `gTTS`.

---

## ✨ Features


### 📚  1. Основная колода — `Daily_Phrases.apkg`
-  🧩 **23 тематических субдека**
- Более 2600 карточек
- Фразы + переводы + примеры употребления
- Аудио для каждой фразы и примеров 

###  🗣 2. Колода диалогов — `Daily_Phrases_small_talk.apkg`
- **Новый субдек**: `Small Talk Flow 💬`
- **500 карточек** — короткие естественные диалоги
- **Два голоса**:
  - 👧 Женский голос (`JennyNeural`)
  - 👦 Мужской голос (`GuyNeural`)
- Реалистичные паузы между репликами
- Идеально подходит для тренировки разговорной речи и listening

---

## 📊 Deck Overview

* 📁 Subdecks: **23**
* 🧠 Total cards: **2684**
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
├── dependent prepositions 🎯
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
|
├── Daily_Phrases_small_talk
└── Small Talk Flow 💬  500 dialogues with two voices
```
## 📊 Общая статистика

| Колода                       | Субдеков | Карточек | Аудио         | Особенности                    |
|------------------------------|----------|----------|---------------|--------------------------------|
| **Daily_Phrases**            | 23       | ~2684    | да            | Фразы + примеры                |
| **Daily_Phrases_small_talk** | 1        | 500      | да (2 голоса) | Диалоги с чередованием голосов |
| **Итого**                    | 24       | ~3184    | —             | —                              |

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
* gTTS 💉
* JSON datasets 📊

---

## 💡 Idea

The goal is to help you **think in English**, not just translate:

* short phrases → fast recall
* examples → real usage
* audio → pronunciation

## 🎯 Идея проекта

- Научиться **думать на английском**, а не только переводить
- Тренировать **произношение** и **слушание**
- Получить естественные **короткие диалоги** для повседневного общения
- Разделить изучение: фразы → для словарного запаса, диалоги → для разговорной практики
---

 ## ⚙️ При желании попробовать необходимо скачивать только колоды 

- Daily_Phrases.apkg
- Daily_Phrases_small_talk.apkg
- Далее импортируете в программы Anki Desk или мобильные версии программы Anki
- Аудио скачивать не нужно.
---


- *если нравится идея поставь звезду ⭐ Star on GitHub*

- *if you like the idea, put a star ⭐ Star on GitHub*