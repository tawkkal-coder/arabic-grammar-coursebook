# Arabic Grammar for Beginners (Nahw - Syntax)
> **A Digital Course Book & Interactive Grammatical Reference**  
> Based on the renowned treatise by **Shaykh Mufti Saiful Islām** (JKN Publications)

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Book-emerald?style=for-the-badge&logo=github)](https://username.github.io/arabic-grammar-coursebook/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Status: Complete](https://img.shields.io/badge/Status-16%20Chapters%20Indexed-teal?style=for-the-badge)]()

---

## 📖 About the Course Book

*Arabic Grammar for Beginners (Nahw - Syntax)* is a classical introductory curriculum on Arabic syntax, authored by **Shaykh Mufti Saiful Islām** (Founder of Jamiah Khatamun Nabiyeen, UK; authorized in the Six Canonical Books of Hadith under Shaykh Muhammad Yusuf Motala).

This repository converts the complete printed textbook into an elegant, modern, responsive online course book designed for self-paced study, madrasah curricula, and university students.

### ✨ Key Features

- **Interactive Chapter Indexing:** Complete coverage of all 16 Lessons, Foreword, Introduction, and Colophon.
- **Course Book Reader Layout:** GitBook / Docusaurus-inspired UI with collapsible sidebar navigation, module grouping, and smooth hash routing.
- **Reading Progress Tracker:** Check off completed lessons with visual percentage tracking persisted in browser `localStorage`.
- **Global Instant Search (`Ctrl + K`):** Real-time client-side search across all lesson titles, definitions, grammatical roles, and Arabic terminology.
- **Multi-Theme Support:** Toggle between **Light** (crisp editorial), **Sepia** (warm classical manuscript), and **Dark** (night reading).
- **Font Size Scaler:** Adjust typography scale on the fly for comfortable reading of Arabic tashkeel (diacritics).
- **Interactive Exercise Self-Check:** Every lesson includes collapsible exercise cards with revealable model answers and grammatical parsing.
- **Complete Reference Hubs:**
  - **70 Pronouns Matrix:** Comprehensive interactive chart of all 70 classical pronouns across Nominative, Accusative, and Genitive states.
  - **16 Declinable Nouns Table:** Comparative reference for markers of Raf'a, Nasb, and Jarr.
  - **17 Prepositions Explorer:** Full catalog of *Hurūf al-Jarr* with Qur'anic citations.

---

## 📚 Curriculum Structure

```
Arabic Grammar for Beginners (Nahw - Syntax)
├── Front Matter
│   ├── Preface & Foreword (Mufti Abdul Waheed, JKN)
│   └── Definition (تعريف), Subject Matter (موضوع), & Purpose (غرض)
├── Module 1: Foundations of Speech
│   ├── Lesson 1: The Word & Meaningful Expression (اللفظ الموضوع والكلمة)
│   ├── Lesson 2: Compounds & Sentences (المركب والكلام)
│   ├── Lesson 3: The Informative Sentence (الجملة الخبرية: الاسمية والفعلية)
│   ├── Lesson 4: Creative / Non-Informative Sentences (الجملة الإنشائية - 10 Types)
│   └── Lesson 5: Incomplete Sentences / Phrases (المركب الناقص - 5 Types)
├── Module 2: Parts of Speech & Identifiers
│   ├── Lesson 6: Signs of Nouns, Verbs, & Particles (علامات الاسم والفعل والحرف)
│   ├── Lesson 7: Definite & Indefinite Nouns (المعرفة والنكرة - 7 Types of Ma'rifah)
│   ├── Lesson 8: Particles of Definition (حروف التعريف والتنكير: الشمسية والقمرية)
│   └── Lesson 9: Masculine & Feminine Gender (المذكر والمؤنث: القياسي والسماعي)
├── Module 3: Inflexion & Declension
│   ├── Lesson 10: Declinable & Indeclinable Words (المعرب والمبني)
│   ├── Lesson 11: The 8 Types of Indeclinable Words (أنواع المبني الثمانية)
│   └── Lesson 12: The 16 Categories of Declinable Nouns (الأسماء المعربة)
├── Module 4: The Three Grammatical Cases
│   ├── Lesson 13: The Nominative Case (الأسماء المرفوعة - 8 Positions)
│   ├── Lesson 14: The Accusative Case (الأسماء المنصوبة - 12 Positions)
│   └── Lesson 15: The Genitive Case (الأسماء المجرورة - 17 Prepositions & Idafah)
├── Module 5: Dependent Words & Author Profile
│   ├── Lesson 16: The Grammatical Followers (التوابع الخمسة: نعت، تأكيد، بدل، عطف)
│   └── Biography of Shaykh Mufti Saiful Islām
└── Reference Hub
    ├── The 70 Pronoun Reference Matrix
    └── 16 Declinable Noun Types Comparative Lookup
```

---

## 🚀 How to Host on GitHub Pages (In 3 Minutes)

This course book is built as a zero-dependency, self-contained single-page web app. You can deploy it to **GitHub Pages** immediately:

### Option A: Via GitHub Web Interface
1. Create a new repository on GitHub (e.g., `arabic-grammar-coursebook`).
2. Upload the contents of this repository (or extract `arabic-grammar-coursebook-github-repo.zip`).
3. Navigate to your repository's **Settings** ➔ **Pages** (in the left sidebar).
4. Under **Branch**, select `main` (or `master`) and directory `/ (root)`, then click **Save**.
5. Your course book is instantly live at:
   ```
   https://<your-username>.github.io/arabic-grammar-coursebook/
   ```

### Option B: Via Git Command Line
```bash
# 1. Clone or extract the repo folder
cd coursebook-repo

# 2. Add your GitHub remote URL
git remote add origin https://github.com/<your-username>/arabic-grammar-coursebook.git

# 3. Rename branch to main if needed and push
git branch -M main
git push -u origin main
```
Then enable GitHub Pages from repository settings!

---

## 💻 Running Locally

No server or compilation step is needed. Simply clone and open `index.html` in any web browser:

```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

---

## 📁 Repository Directory Structure

```
.
├── index.html                  # Standalone interactive course book application
├── README.md                   # Project documentation & deployment guide
├── _config.yml                 # GitHub Pages configuration
├── LICENSE                     # MIT License
└── .github/
    └── workflows/
        └── deploy.yml          # Optional GitHub Actions deployment workflow
```

---

## 📜 Credits & Citation

- **Original Work:** *Arabic Grammar for Beginners (Nahw - Syntax)*
- **Author:** Shaykh Mufti Saiful Islām
- **Publisher:** Jāmiah Khātamun Nabiyyeen (JKN Publications), Bradford, UK
- **Web App Engineering:** Digital course book conversion with indexed chapter navigation, search indexing, and interactive exercises.

Distributed for educational purposes under the MIT License.
