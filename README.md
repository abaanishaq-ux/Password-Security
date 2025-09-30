# Password-Security
Strengthening digital security by understanding passwords, attacks, and defenses.
# 🔐 Task 6: Password Security & Strength Evaluation

## 📌 Objective
The goal of this task is to **understand what makes a password strong**, evaluate different types of passwords using online strength checkers, and summarize best practices to protect against common password attacks.

---

## 🛠️ Tools Used
- [Password Meter](https://passwordmeter.com)  
- [Security.org – How Secure Is My Password](https://www.security.org/how-secure-is-my-password/)
- 
---

## 🔑 Passwords Tested
| Password Example           | Strength Result | Tool Feedback |
|----------------------------|-----------------|---------------|
| `hello123`                 | Weak ❌         | Too short, common word, easy to guess |
| `Hello@1234`               | Medium ⚠️       | Better, has mix of cases + numbers |
| `P@ssW0rd!2025_Secure`     | Strong ✅       | Long, complex, hard to brute-force |
| `Sunshine$Is@Better2025`   | Very Strong 🔥  | Passphrase style, highly resistant |

---

## 📸 Screenshots
*(Added in the Repo `)*  

---

## 🔍 Password Hacking Techniques (Brief)
Below are common techniques attackers use to obtain or crack passwords, with short explanations and quick mitigations.

1. **Brute Force Attack**  
   - **What:** Try every possible combination until the right one is found.  
   - **Mitigation:** Use long passwords (12+ chars), account lockouts/rate-limiting, and MFA.

2. **Dictionary Attack**  
   - **What:** Try lists of common words, phrases, or leaked passwords.  
   - **Mitigation:** Avoid dictionary words; use unpredictable passphrases and symbols.

3. **Credential Stuffing**  
   - **What:** Use credentials leaked from one service to try login on others.  
   - **Mitigation:** Never reuse passwords; monitor for breaches; enable MFA.

4. **Password Spraying**  
   - **What:** Try a small set of common passwords across many accounts to avoid lockouts.  
   - **Mitigation:** Enforce strong password policies, MFA, and anomaly detection.

5. **Rainbow Table / Hash Cracking**  
   - **What:** Use precomputed tables to reverse hashed passwords quickly.  
   - **Mitigation:** Use unique salts for stored hashes, strong hash functions (bcrypt, Argon2).

6. **Phishing**  
   - **What:** Trick users into revealing passwords via fake pages or messages.  
   - **Mitigation:** Train users, validate URLs, use phishing-resistant MFA (hardware keys).

7. **Keylogging / Malware**  
   - **What:** Malicious software records keystrokes or steals stored credentials.  
   - **Mitigation:** Keep systems patched, use reputable antivirus/EDR, avoid unknown downloads.

8. **Social Engineering**  
   - **What:** Manipulate people (calls, messages) to disclose credentials or reset info.  
   - **Mitigation:** Verify identity requests, limit info shared publicly, use strict reset procedures.

9. **Shoulder Surfing / Physical Observation**  
   - **What:** Watch someone enter a password in person.  
   - **Mitigation:** Shield inputs, use biometric/MFA options, be mindful in public spaces.

10. **Man-in-the-Middle (MITM)**  
    - **What:** Intercept communications to capture credentials entered over insecure connections.  
    - **Mitigation:** Use HTTPS/TLS, avoid public Wi-Fi or use a trusted VPN, enable HSTS.

---

## 📚 Key Learnings
- ✅ **Length matters** – longer passwords are harder to crack.  
- ✅ **Mix of characters** – use uppercase, lowercase, numbers, and symbols.  
- ✅ **Avoid dictionary words** – attackers use common wordlists.  
- ✅ **Use passphrases** – easy to remember, but hard to crack.  
- ✅ **Unique per account** – never reuse the same password.  

---

## 🛡️ Best Practices
1. Use **12+ characters** in every password.  
2. Combine **letters, numbers, symbols, uppercase & lowercase**.  
3. Avoid personal info (birthdays, names, phone numbers).  
4. Prefer **passphrases** (e.g., `Coffee$Is@Strong2025`).  
5. Enable **Multi-Factor Authentication (MFA)** wherever possible.  
6. Use a **Password Manager** for secure storage and unique passwords.

---

## ⚔️ Common Password Attacks (Summary)
- **Brute Force Attack**: exhaustive guessing.  
- **Dictionary Attack**: using wordlists.  
- **Credential Stuffing**: reusing leaked combos across sites.  
- **Phishing**: tricking users to disclose secrets.  
- **Rainbow Table / Hash Cracking**: reversing hashed passwords.
