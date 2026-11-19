# CTF Challenge Tracker & Technical Write-Ups

A structured log of **62 completed cybersecurity challenges** across **picoCTF** and **TryHackMe**, covering Web Exploitation, Digital Forensics, Cryptography, OSINT, and General Skills.

> 🔗 **Related Repository:** Check out my hardware-accelerated offline cracking labs in [password_cracking_labs](https://github.com/triallifeglitcher/password_cracking_labs).

---

## 📊 Completion Summary

| Category | Platform | Solved |
| :--- | :--- | :---: |
| **Web Exploitation** | picoCTF | 20 |
| **General Skills** | picoCTF | 19 |
| **Forensics** | picoCTF | 15 |
| **Cryptography** | picoCTF | 7 |
| **OSINT** | TryHackMe | 1 |
| **Total** | | **62** |

---

## 🌐 Web Exploitation (20 Solved)

| # | Challenge | Core Concept / Vulnerability |
| :---: | :--- | :--- |
| 1 | **Inspect Elements** | Client-side HTML/CSS/JS source inspection |
| 2 | **Local Authority** | Client-side JavaScript credential validation bypass |
| 3 | **Cookies** | HTTP session cookie enumeration & manipulation |
| 4 | **Scavenger Hunt** | Source comments, `robots.txt`, `.htaccess`, and `.DS_Store` discovery |
| 5 | **dont-use-client-side** | Reconstructing split JavaScript string checks |
| 6 | **SQLiLite** | Basic SQL Injection authentication bypass |
| 7 | **more SQLi** | Union-based SQL Injection database extraction |
| 8 | **Forbidden Paths** | Directory traversal (`../`) filter bypass |
| 9 | **GET aHEAD** | HTTP `HEAD` request method header inspection |
| 10 | **logon** | Forging boolean admin session cookies |
| 11 | **Insp3ct0r** | Multi-file web source inspection (HTML, CSS, JS) |
| 12 | **Irish-Name-Repo 1** | SQL Injection login bypass |
| 13 | **Irish-Name-Repo 2** | SQL Injection bypassing input sanitization |
| 14 | **Irish-Name-Repo 3** | SQL Injection bypassing custom query encoding/filters |
| 15 | **caas** | Command Injection via Cowsay web wrapper |
| 16 | **secrets** | Nested hidden directory traversal in web assets |
| 17 | **webDecode** | Base64 decoding hidden in HTML attributes |
| 18 | **where are the robots** | Enumerating disallowed paths in `robots.txt` |
| 19 | **power cookie** | Modifying guest-to-admin cookie parameters |
| 20 | **Super Serial** | PHP object deserialization & magic method exploitation |

---

## 🛠️ General Skills (19 Solved)

| # | Challenge | Core Concept / Tool Used |
| :---: | :--- | :--- |
| 1 | **Magikarp Ground Mission** | Linux filesystem navigation (`ls`, `cd`, `cat`) |
| 2 | **Wave a flag** | Linux file permissions (`chmod +x`) & CLI help flags (`-h`) |
| 3 | **Obedient Cat** | Basic terminal file inspection |
| 4 | **Tab, Tab, Attack** | Shell tab-completion & binary execution |
| 5 | **First Find** | Recursive file searching with `find` |
| 6 | **First Grep** | Pattern searching inside text files with `grep` |
| 7 | **Bases** | Base64 decoding |
| 8 | **Convertme.py** | Decimal-to-binary conversion & Python script execution |
| 9 | **Strings it** | Extracting readable ASCII text from binaries with `strings` |
| 10 | **Glitch Cat** | Evaluating Python `chr()` ASCII character concatenation |
| 11 | **Undo** | Text reversal and string manipulation |
| 12 | **Bytemancy 0** | Raw byte and hex representation analysis |
| 13 | **FANTASY CTF** | Interactive CLI logic & prompt navigation |
| 14 | **MultiCode** | Multi-layer encoding identification & decoding |
| 15 | **PW Crack 1** | Python static analysis & hardcoded password discovery |
| 16 | **PW Crack 2** | Evaluating hexadecimal ASCII character expressions (`chr(0x...)`) |
| 17 | **PW Crack 3** | Automating MD5 hash checks across candidate lists in Python |
| 18 | **PW Crack 4** | Modifying Python control flow to brute-force 100 candidates |
| 19 | **PW Crack 5** | Converting `.hash.bin` bytes to hex & cracking with Hashcat (`-m 0`) |

---

## 🔍 Digital Forensics (15 Solved)

| # | Challenge | Core Concept / Tool Used |
| :---: | :--- | :--- |
| 1 | **Disko 1** | Disk image inspection & string extraction |
| 2 | **Glory of the garden** | Trailing ASCII strings appended to image files |
| 3 | **Riddle Registry** | PDF metadata inspection (`exiftool` / raw properties) |
| 4 | **Hidden in plainsight** | Image steganography & metadata extraction |
| 5 | **RED** | PNG color channel (LSB) steganography |
| 6 | **MSB** | Most Significant Bit image steganography extraction |
| 7 | **Information** | EXIF metadata & Base64 decoding |
| 8 | **Extension** | Fixing corrupted file signatures / magic bytes |
| 9 | **Packets Primer** | Basic PCAP network traffic inspection in Wireshark |
| 10 | **shark on wire 1** | Following UDP streams in Wireshark |
| 11 | **Shark on Wire 2** | Extracting covert data from UDP source ports in PCAP |
| 12 | **Lookey here** | Regex / `grep` filtering across large log dumps |
| 13 | **MacroHard WeakEdge** | Inspecting embedded XML inside `.pptm` Office archives |
| 14 | **Trivial Flag Transfer Protocol** | Exporting TFTP objects in Wireshark & `steghide` extraction |
| 15 | **credstuff** | Correlating leaked username/password dumps & ROT13 decoding |

---

## 🔐 Cryptography (7 Solved)

| # | Challenge | Core Concept / Cipher |
| :---: | :--- | :--- |
| 1 | **ROT13** | Caesar cipher rotation by 13 places |
| 2 | **MOD 26** | Modular arithmetic alphabet rotation |
| 3 | **Caesar** | Brute-forcing rotational shift ciphers |
| 4 | **easy1** | One-time pad / Vigenère table lookup |
| 5 | **Vigenere** | Polyalphabetic substitution cipher decryption |
| 6 | **transpositional-trial** | Block transposition & character reordering |
| 7 | **the numbers** | A1Z26 numeric-to-alphabet cipher decoding |

---

## 🕵️ OSINT (1 Solved)

| # | Challenge | Core Concept / Tool Used |
| :---: | :--- | :--- |
| 1 | **OhSINT** *(TryHackMe)* | EXIF metadata, Wi-Fi BSSID lookup (WiGLE), & GitHub/Twitter OSINT |

