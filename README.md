Enhanced Dictionary App
A modern, interactive English dictionary web app built with HTML, Tailwind CSS, and Vanilla JavaScript, featuring dark mode, custom fonts, audio support, and a persistent search history for an elevated vocabulary-learning experience.

🌟 Features
Real-time Word Search:
Instantly search for any English word. Get accurate definitions, part-of-speech labels, phonetic transcriptions, example usages, and synonyms, powered by DictionaryAPI.dev.

Audio Pronunciation:
Hear the correct pronunciation of most words with an intuitive audio play button.

Theme Toggle:
Effortlessly switch between light and dark themes with a single click — your choice is remembered for future visits.

Font Selector:
Easily change between Sans-Serif, Serif, or Monospace (Mono) fonts to suit your reading preference, also saved for next time.

Search History:
See your last 5 search queries as clickable buttons for one-tap re-search and easy revision. History is stored locally and avoids duplicates.

Word of the Day:
Each time you load the app, it automatically displays the definition of a random, interesting English word to expand your vocabulary.

Responsive, Accessible Design:
Built with Tailwind CSS, the layout adapts perfectly from mobile to desktop, with accessible color choices and keyboard-friendly controls.

🚀 Getting Started
Clone or Download the repository.

Open index.html directly in your preferred web browser—no setup or server required.

Start Searching:

Enter a word and hit Enter or click the search icon.

Click the audio button to hear pronunciations.

Switch modes or fonts using the toolbar.

Click on a history word to view it again instantly.

💡 How It Works
API Usage:
Fetches definitions and data from the public DictionaryAPI.dev endpoint.

Theme/Font Persistence:
User preferences for light/dark mode and font family are stored in your browser’s localStorage for seamless UX.

History Management:
Keeps a simple, easy-to-use history (up to 5 words). Newest searches appear first; duplicates are removed automatically.

🗂️ Structure
text
enhanced-dictionary-app/
│
├── index.html    # All code (HTML, Tailwind, JS) in one file
├── README.md     # (this file)
🛠️ Customization
Add favorite words to the wordOfTheDayList array for diverse “word of the day” results.

Tweak maximum history size by editing the updateHistory function in JS.

Personalize styles by editing Tailwind utility classes in the markup.
