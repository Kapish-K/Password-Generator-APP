Password Generator App 🔐

A minimalist, high-security, client-side password generator built with modern web standards and a sleek dark-mode liquid glass UI. Designed for maximum privacy, mathematical randomness, and seamless user experience.

Developed by Kapish Kumar.

🚀 Features

🔐 Cryptographically Secure (CSPRNG): Uses window.crypto.getRandomValues() instead of standard pseudo-random generators (Math.random()) for mathematically unpredictable passwords.

🛡️ 100% Client-Side Privacy: Zero server calls or network requests. Your generated passwords never leave your browser.

🎛️ Variable Length Control: Generate passwords from 1 to 128 characters.

🔤 Flexible Character Pools: Toggle uppercase letters, lowercase letters, numbers, and special symbols on demand.

👁️ UX Safety Controls:

Exclude Ambiguous Characters: Filters out easily confused characters like 1, l, I, |, 0, O, o, and Q.

Exclude Repeat Characters: Guarantees unique character selection per password.

👁️ Mask / Unmask Toggle: Hide sensitive output from shoulder surfers with a single click.

📋 Auto-Clear Clipboard Timer: Automatically wipes copied passwords from your clipboard after 45 seconds to prevent accidental pasting.

📊 Real-Time Strength Meter: 4-bar visual strength calculator evaluating password entropy and structure.

✨ Liquid Glass UI: Modern dark aesthetic inspired by Apple and Linear design systems.

🛠️ Technology Stack

HTML5: Semantic layout structure.

CSS3 & Tailwind CSS: Clean utility styling with frosted glass overlay effects (backdrop-filter).

Vanilla JavaScript (ES6+): Standard browser APIs for DOM updates, logic, and state management without heavy frameworks.

Web Crypto API: Native OS-level entropy for secure random character generation.

Lucide Icons: Clean vector icon set.

📂 Project Structure

├── app.html         # Main web application file
└── README.md        # Project documentation


⚡ Quick Start

Clone or Download the Repository:

git clone https://github.com/your-username/password-generator-app.git


Run the Application:
Simply open app.html directly in any modern web browser (Chrome, Firefox, Safari, Edge, Brave). No build step, Node.js, or server installation required!

🛡️ Security Assurance

This app operates strictly within your local browser context.

No Analytics / No Tracking

No External Database Storage

No API Server Communication


Created with ❤️ by Kapish Kumar.