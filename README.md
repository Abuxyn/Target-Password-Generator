# 🔐 High-Probability Wordlist Generator

A powerful, fast, and privacy-focused client-side web utility designed to prioritize high-probability password combinations based on target profile details. This tool is built for cybersecurity professionals, penetration testers, and ethical hackers to assist in security auditing and credential strength validation.

🌐 **Live Demo:** [Launch the Wordlist Generator](https://github.io)

---

## 🚀 Features

- **Targeted Profiling:** Generates customized combinations using personal intelligence data (Full Name, Nickname, User ID, DOB, Parent/Partner names, and custom keywords).
- **Intelligent Permutations:** Prioritizes high-probability patterns, common modifications (leetspeak variations, casing tweaks), and common year/number appending.
- **Adjustable Thresholds:** Built-in safety limits (up to 5,000 words maximum output) to keep generation snappy and efficient.
- **Multi-Format Export:** Supports quick saving and exporting of generated results into standard `.txt`, `.csv`, and `.pdf` formats.
- **100% Client-Side & Secure:** No data is ever sent to a server. All combination logic runs locally in your web browser, ensuring complete privacy of target profile data.
- **Modern Dark UI:** Clean, responsive dashboard designed for readability during auditing workflows.

---

## 📁 Project Structure

```text
├── index.html       # Application layout and structural UI
├── style.css        # Custom dark-theme styling and responsive layout
└── script.js       # Wordlist generation logic and permutation algorithms
```

---

## 🛠️ Usage

1. Open the [Live Web Application](https://github.io).
2. Fill out the **Target Profile Details** form with known inputs (fields marked with `*` are required).
3. Set your maximum output list limits (default capped at 5000).
4. Click **Generate Wordlist**.
5. Review the combinations directly in the dashboard preview box.
6. Export the compiled list to your preferred format (`TXT`, `CSV`, or `PDF`) for integration into security tooling.

---

## ⚖️ Disclaimer

*This tool is intended exclusively for authorized security auditing, ethical hacking, and educational purposes. Generating wordlists against targets without explicit, prior written permission is illegal. The developer assumes no liability for misuse or damage caused by this utility.*

---

✨ *Created with 💻 by [Abuxyn](https://github.com)*
