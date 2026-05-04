# Password Strength Analyzer

A lightweight, client-side password strength analyzer built with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies, no data sent anywhere.

![Password Strength Analyzer](https://img.shields.io/badge/HTML-CSS-JS-blue?style=flat-square) ![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## Live Demo

🔗 [https://Pavan26c.github.io/password-analyzer](https://Pavan26c.github.io/password-analyzer)

---

## Features

- **Real-time strength meter** — rates your password across 5 tiers: Very Weak → Very Strong
- **8 security checks** — length, uppercase, lowercase, digits, special characters, repeated characters, and keyboard patterns
- **Entropy display** — shows bits of entropy so you understand the math behind the score
- **Crack time estimate** — estimates how long a brute-force attack (10 billion guesses/sec) would take
- **3 strong password suggestions** — randomly generated 16–20 character passwords, click to copy
- **Reuse detection** — warns you if you enter a password you've already checked this session
- **Password history log** — masked log of all passwords checked in the current session
- **Dark mode support** — automatically adapts to your system preference
- **Fully offline** — all analysis happens locally in your browser, nothing is sent to any server

---

## How to Use

Since this is a single HTML file with zero dependencies, just:

1. Download `index.html`
2. Open it in any modern browser
3. Start typing a password

Or visit the live demo link above.

---

## Tech Stack

- HTML5
- CSS3 (CSS variables, dark mode via `prefers-color-scheme`)
- Vanilla JavaScript (no libraries or frameworks)

---

## Security Concepts Covered

- **Shannon entropy** — measures unpredictability of a password based on character set size and length
- **Brute-force estimation** — calculates crack time assuming a fast offline attack
- **Pattern detection** — flags common weak patterns like `qwerty`, `1234`, `password`
- **Password reuse** — demonstrates why reusing passwords is risky

---

## Project Structure

```
password-analyzer/
├── index.html      # Entire app — markup, styles, and logic
├── README.md       # This file
└── LICENSE         # MIT License
```

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

Made by [Pavan26c](https://github.com/Pavan26c)
