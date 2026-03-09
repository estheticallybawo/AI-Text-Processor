# **AI-Powered Text Processor**

An intelligent text processing application built with Next.js that leverages Chrome's built-in AI APIs for real-time language detection, summarization, and translation - all running locally in the browser without external API calls.

##  **Features**

- **Language Detection** - Automatically detects the language of input text with confidence scores
- **Text Summarization** - Generates concise summaries of English text longer than 150 characters
- **Translation** - Translates text between multiple languages using on-device AI
- **Chat Interface** - Clean, responsive chat UI for processing multiple messages
- **Confidence Indicators** - Displays detection confidence percentages for transparency

##  **Tech Stack**

- **Framework:** Next.js 14 (App Router)
- **Language:** TypeScript
- **Styling:** CSS Modules
- **UI Components:** Custom shadcn/ui components
- **AI Integration:** Chrome Built-in AI APIs (Summarizer, Language Detector, Translator)
- **State Management:** React Context API + Hooks

##  **How It Works**

The application uses Chrome's experimental on-device AI APIs:
- **Language Detection:** `window.ai.languageDetector` identifies the input language
- **Summarization:** `window.ai.summarizer` creates concise summaries
- **Translation:** `window.ai.translator` provides real-time translation

All processing happens locally in the browser - no data leaves your device!

##  **Screenshot**

<img width="1359" height="599" alt="image" src="https://github.com/user-attachments/assets/f7b9363a-6f41-4f9c-97b3-dd8f8f3c6073" />


## 🚦 **Getting Started**

1. **Clone the repository**
```bash
git clone https://github.com/estheticallybawo/ai-text-processor.git
```

2. **Install dependencies**
```bash
npm install
```

3. **Run the development server**
```bash
npm run dev
```

4. **Open [http://localhost:3000](http://localhost:3000)**

##  **Requirements**

- Chrome browser (Canary or Dev channel recommended)
- Enable Chrome's built-in AI features at `chrome://flags/#optimization-guide-on-device-model.`

##  **Use Cases**

- Content creators checking multilingual text
- Students summarizing long articles
- Language learners translating phrases
- Quick language identification for international communication

##  **Future Enhancements**

- Support for more languages in translation
- Export chat history
- Dark/light theme toggle
- Voice input integration

##  **Contributing**

Contributions are welcome! Feel free to open issues or submit PRs.

##  **License**

MIT

##  **Author**

**Esther Bawo Tsotso**
- GitHub: [@estheticallybawo](https://github.com/estheticallybawo)
- Built for [HNG Tech Internship](https://hng.tech)

---

*This project demonstrates practical implementation of on-device AI capabilities in modern web applications, showcasing real-time language processing without compromising user privacy.*
