# 🧠 Uncertainty Engine

Uncertainty Engine Pro is a web-based AI analysis tool that evaluates responses based on confidence levels. Instead of giving a single answer, it breaks down *how certain each claim is* using color-coded tagging.

---

## 🚀 Features

### ⚡ Analyze Mode

* Ask any question
* AI response is tagged with:

  * **Memorized** (high confidence)
  * **Inferred** (logical reasoning)
  * **Extrapolated** (educated guess)
  * **Unknown** (uncertain)

### ⇄ Compare Mode

* Compare two questions or viewpoints
* Side-by-side confidence analysis
* Shows which answer is more reliable

### 🔬 Research Mode

* Breaks down claims into smaller sub-claims
* Each claim gets:

  * Confidence type
  * Reasoning
  * Verification status

### 💊 Medical Mode

* Applies stricter uncertainty rules
* Flags risky or unclear medical advice
* Encourages professional consultation

### ⚖ Debate Mode

* Shows both sides of an argument
* Evaluates strength of each claim

---

## 🎨 UI Highlights

* Dark modern interface
* Real-time confidence visualization
* Interactive tooltips explaining each tag
* Session history tracking
* Export options (JSON, HTML, Text)

---

## 🛠️ Tech Stack

* HTML5
* CSS3 (custom UI styling)
* Vanilla JavaScript
* Anthropic Claude API

---

## ⚙️ Setup

1. Clone or download the project
2. Open `index.html` in your browser

> ⚠️ Note: You must connect your own API key for the Claude API to make it functional.

---

## 📦 API Configuration

Replace the API request in the JavaScript section with your own key:

```js
headers: {
  "Content-Type": "application/json",
  "x-api-key": "YOUR_API_KEY_HERE"
}
```

---

## 📤 Export Options

* JSON (structured data)
* HTML report (visual)
* Plain text (simple format)

---

## 💡 Use Cases

* Fact-checking AI responses
* Research validation
* Learning tool for critical thinking
* Comparing arguments or claims

---

## ⚠️ Disclaimer

This tool provides AI-generated analysis and should not be used as a sole source of truth, especially for medical or critical decisions.

---

## 📄 License

Open for personal and educational use.
