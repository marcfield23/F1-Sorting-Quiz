# 🏎️ F1 Team Principal Sorting Hat

> "The Paddock chooses the wizard, Mr. Potter."

A logic-based personality quiz that sorts you into your matching **Formula 1 Team Principal** identity based on your management style, risk tolerance, and political cunning.

### 🔴 **[Play the Live Quiz Here](https://marcfield23.github.io/F1-Sorting-Quiz/)** 🔴

![Project Status](https://img.shields.io/badge/Status-Live-success) ![License](https://img.shields.io/badge/License-MIT-blue)

---

## 📊 Community Stats (N=50)
*Updated: Dec 15, 2025*

Based on the first wave of submissions, the F1 fan community is surprisingly intellectual!
* 🥇 **Most Common Result:** **Andrea Stella** (22%) – *The Professor*
* 🥈 **Second Place:** **James Vowles** (20%) – *The Architect*
* 👻 **Rarest Result:** **Flavio Briatore** (0%) – *The Maverick* (Nobody has been chaotic enough to unlock him yet!)

---

## ⚙️ How It Works
This is a Single Page Application (SPA) built with:
* **Frontend:** HTML5, CSS3, Vanilla JavaScript.
* **Logic:** A "closest-match" algorithm that compares your 8 answers against the psychological profiles of 11 real-world F1 Principals.
* **Backend:** Integration with **FormSubmit.co** (via secure Token) to capture results anonymously without a backend server.
* **Privacy:** No personal data is stored. User email addresses are not required.

---

## 🔐 The Master Key (Permutations)
Want to know how the algorithm decides? It looks for specific trait sequences.

*SPOILER WARNING: The table below reveals the exact answers needed for each result.*

| Team Principal | Archetype | The "Perfect Run" Sequence (Q1–Q8) |
| :--- | :--- | :--- |
| **Christian Horner** | The Provocateur | `A - B - B - A - A - A - A - A` |
| **Toto Wolff** | The Commander | `B - C - B - B - A - A - B - A` |
| **Frédéric Vasseur** | The Pragmatist | `C - A - D - B - D - A - D - D` |
| **Andrea Stella** | The Professor | `C - D - C - C - D - B - C - D` |
| **James Vowles** | The Architect | `D - B - C - D - B - B - C - B` |
| **Flavio Briatore** | The Maverick | `A - B - B - A - C - D - A - A` |
| **Jonathan Wheatley** | The Rule Master | `B - A - A - B - B - C - C - B` |
| **Laurent Mekies** | The Successor | `B - A - A - B - B - B - C - A` |
| **Alan Permane** | The Enforcer | `B - A - A - B - D - C - A - B` |
| **Ayao Komatsu** | The Realist | `B - B - C - C - D - C - C - B` |
| **Andy Cowell** | The Engineer | `D - A - C - C - D - A - C - C` |

### **The Question Key:**
* **Q1:** Focus (ROI vs Efficiency vs Culture vs Leapfrog)
* **Q2:** Fear (Pit Errors vs Bankruptcy vs Betrayal vs Correlation)
* **Q3:** Weapon (Loophole vs Lawyer vs Spreadsheet vs Coffee)
* **Q4:** Crash Conflict (Spin It vs Punish vs Calculate vs Coach)
* **Q5:** Scandal (Grenade vs Protest vs Copy vs Ignore)
* **Q6:** Recruitment (Superstar vs Rookie vs Veteran vs Maverick)
* **Q7:** Mistake (No Apology vs Public Shield vs Protocol vs Emotional)
* **Q8:** Legacy (Winner vs Builder vs Genius vs Father Figure)

---

## 🛠️ Installation / Forking
If you want to host your own version of this quiz:

1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/marcfield23/F1-Sorting-Quiz.git](https://github.com/marcfield23/F1-Sorting-Quiz.git)
    ```
2.  **Update the Backend:**
    * This project uses [FormSubmit.co](https://formsubmit.co) for the backend.
    * Go to their site, enter your email, and get your **Random Token** (e.g., `98d24b...`).
    * *Do not put your raw email in the code!*
    * Open `index.html` and replace the fetch URL in the `showResult()` function:
    ```javascript
    fetch("[https://formsubmit.co/ajax/YOUR_TOKEN_HERE](https://formsubmit.co/ajax/YOUR_TOKEN_HERE)", ...
    ```
3.  **Host it:**
    * Upload to GitHub Pages or Netlify.

---

**Created by Marcfield23**
