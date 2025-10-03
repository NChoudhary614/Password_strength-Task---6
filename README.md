# 🔐 Cyber Security Internship – Task 6

## 📌 Task
**Create a Strong Password and Evaluate Its Strength**

- **Objective:** Understand what makes a password strong and test it against password strength tools.  
- **Tools Used:** [passwordmeter.com](https://passwordmeter.com), [howsecureismypassword.net](https://howsecureismypassword.net), manual entropy calculation.  
- **Deliverable:** Report showing password strength results and explanation.

---

## 🛠️ Steps Followed
1. Created multiple test passwords with varying complexity:
   - Simple lowercase
   - Mixed case with numbers
   - Mixed case with numbers & symbols
   - Random strong password
   - Passphrase (multi-word)

2. Tested each password using **online strength checkers**.  
3. Calculated entropy using the formula:  
4. Compared estimated crack times at different guess rates (10k/sec and 1B/sec).  
5. Summarized results and noted best practices.

---

## 📊 Results Summary

| Password Example       | Length      | Charset Used       | Entropy (bits)  | Crack Time            | Strength |
|------------------------|-------------|--------------------|-----------------|-----------------------|---------------|
| `Crack987`             | 8           | 5l, 1u, 3d         | 37.6            | ~11m.18sec            | Very Weak |
| `Crack@192`            | 8           | 62                 | 47.6            | ~31.07 min            | Weak |
| `Crack@45.`            | 11          | 62                 | 65.5            | ~7 hours              | Medium |
| `Crack@45.&the`        | 11          | 94                 | 72.1            | ~4 months             | Strong |
| `Crack@45.&the!mn`     | 12          | 94                 | 78.7            | ~1thou. years         | Very Strong |
| `correct horse battery staple` | 28 | Diceware words | 51.7 | Extremely long | Extremely long | Strong & Memorable 

---

## ✅ Key Learnings
- **Length matters more than complexity**: Adding more characters increases entropy significantly.  
- **Random > Predictable**: Randomly generated passwords are much stronger than clever substitutions (like `Pa55w0rd`).  
- **Passphrases work**: Long, random word combinations are secure and easier to remember.  
- **Password manager recommended**: To handle strong, unique passwords for every account.  
- **MFA is essential**: Passwords alone are not enough.

---

## 📌 Best Practices
- Use at least **12+ characters** (longer is better).  
- Combine **uppercase, lowercase, digits, and symbols**.  
- Avoid dictionary words or personal info.  
- Use a **password manager** to generate/store unique passwords.  
- Always enable **Multi-Factor Authentication (MFA)**.  

---

## 🧾 Outcome
- Understood how password complexity affects security.  
- Learned to measure password strength using entropy and online tools.  
- Documented best practices for creating strong passwords.  

---


## 🚀 Conclusion
Password strength depends heavily on **length and randomness**.  
The strongest strategy is to use **long, random passwords or passphrases**, store them in a **password manager**, and always enable **MFA** for additional protection.
