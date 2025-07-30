# jwt_cracker
A web-based tool to analyze and crack HS256 JSON Web Tokens (JWTs) using a wordlist. Built for educational purposes to explore JWT vulnerabilities, it decodes tokens, checks for the "none" algorithm, and attempts to brute-force the secret with a sleek cyberpunk interface (#000000, #3533cd).
# Features

**Token Analysis: Decodes JWT header and payload without signature verification**.

**Algorithm Check: Warns if the token uses the vulnerable "none" algorithm.**

**HS256 Cracking: Attempts to brute-force the HS256 secret using an uploaded wordlist.**

**Cyberpunk Design: Responsive UI with a black and blue gradient theme, glassmorphism, and smooth animations.**

**Browser-Based: Runs Python (via Pyodide) entirely in the browser, no server required.**
# Demo
Try it live on GitHub Pages 
# How to Use

Open jwt_cracker.html in a modern web browser.

Enter a JWT token in the input field (e.g., from jwt.io).

Upload a wordlist file (e.g., rockyou.txt).

Click "Analyze & Crack" to see:

Decoded header and payload.

Algorithm check (with "none" algorithm warning).

HS256 secret cracking result (if applicable).



# Tech Stack

**HTML/CSS: Structure and styling with a cyberpunk theme.
JavaScript: Handles file input and Pyodide integration.
Python (Pyodide): Runs JWT analysis and cracking logic in the browser.
PyJWT: Library for JWT decoding.**

# Installation
No dependencies required! Simply open jwt_cracker.html in a browser. Pyodide and PyJWT are loaded automatically via CDN.
# Screenshots
<img width="1919" height="1148" alt="Screenshot 2025-07-30 103225" src="https://github.com/user-attachments/assets/565a76e7-c99a-4364-a983-926d90b74c8d" />

# Contributing

Fork the repository.

Create a new branch (git checkout -b feature-branch).

Make changes and commit (git commit -m "Add feature").

Push to the branch (git push origin feature-branch).

Open a Pull Request.

# License
This project is licensed under the MIT License. See the LICENSE file for details.
# Warning
This tool is for educational purposes only. Unauthorized use on real systems is illegal and unethical. Use responsibly.
# Acknowledgments
Built as a cybersecurity project to demonstrate JWT vulnerabilities.
# Daniel Yewenu
