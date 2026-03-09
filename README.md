# 🎓 University of Pennsylvania Insider Quiz

![University of Pennsylvania Campus](https://drive.google.com/uc?export=view&id=1v_C4zOJMkCWQ_vvRNRD8MOXP4SwcsYOQ)

## About This Quiz

Think you know University of Pennsylvania? This insider quiz tests your knowledge of campus traditions, history, famous alumni, hidden gems, and little-known facts that only true insiders would know.

**10 questions • 5 choices each • How well do you really know University of Pennsylvania?**

## How to Use

### Questions
Check out [`questions.js`](./questions.js) for the full quiz with all 10 questions and their multiple-choice options.

### Answers
The answer key with explanations is in [`answers.js`](./answers.js) — no peeking until you're done! 👀

## Quick Start

```javascript
const { questions } = require('./questions');
const { answers } = require('./answers');

// Display a question
console.log(questions[0].question);
Object.entries(questions[0].choices).forEach(([key, val]) => {
  console.log(`  ${key}: ${val}`);
});

// Check answer
console.log(`Correct: ${answers[0].correct} - ${answers[0].explanation}`);
```

## Sample Question

> **During football games at Franklin Field, what exact lyric prompts the student "toast throwing" tradition?**
> - **A.** Fight on, Pennsylvania!
> - **B.** Drink a highball and be jolly
> - **C.** Here's a toast to dear old Penn
> - **D.** Hurrah for the Red and Blue
> - **E.** One more river to cross

<details>
<summary>🔍 Click to reveal answer</summary>

**C** — Students hurl toast when the band hits “Here’s a toast to dear old Penn.”

</details>

## Quiz Topics Covered

- 🏛️ Campus traditions & rituals
- 📜 University history & founding stories
- 🌟 Famous alumni & their connections
- 🗺️ Hidden spots & insider knowledge
- 🎯 Little-known facts & surprising trivia

---

<div align="center">

*Generated with 💜 by [Papersaurus](https://github.com/farmrecipes67) 🦕*

*Quiz content created using AI • Campus image generated with AI*

</div>

<!-- Open Graph Tags for Social Sharing -->
<!-- og:title: University of Pennsylvania Insider Quiz -->
<!-- og:description: Think you know University of Pennsylvania? Take this 10-question insider quiz covering campus traditions, history, famous alumni, and little-known facts! -->
<!-- og:image: https://drive.google.com/uc?export=view&id=1v_C4zOJMkCWQ_vvRNRD8MOXP4SwcsYOQ -->
<!-- og:type: website -->
