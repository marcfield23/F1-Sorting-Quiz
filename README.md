# 🏎️ F1 Team Principal Sorting Quiz

> "The Paddock chooses the wizard, Mr. Potter."

A logic-based personality quiz that sorts you into your matching **Formula 1 Team Principal** identity based on your management style, risk tolerance, and political cunning.

### 🔴 **[Play the Live Quiz Here](https://marcfield23.github.io/F1-Sorting-Quiz/)** 🔴

---

## ⚙️ How It Works
This is a Single Page Application (SPA) built with:
* **Frontend:** HTML5, CSS3, Vanilla JavaScript.
* **Logic:** A "closest-match" algorithm that compares your 8 answers against the psychological profiles of 11 real-world F1 Principals.
* **Backend:** Integration with [Formsubmit](formsubmit.co) to capture and log user results anonymously.

---

## 🔐 The Master Key (Permutations)
Want to know how to unlock a specific character? The algorithm looks for the **exact sequence** of traits below.

*SPOILER WARNING: The table below reveals the exact answers needed for each result.*

| Team Principal | Team | The "Perfect Run" Sequence (Q1–Q8) |
| :--- | :--- | :--- |
| **Christian Horner** | Red Bull Racing | `A - B - B - A - A - A - A - A` |
| **Toto Wolff** | Mercedes | `B - C - B - B - A - A - B - A` |
| **Frédéric Vasseur** | Ferrari | `C - A - D - B - D - A - D - D` |
| **Andrea Stella** | McLaren | `C - D - C - C - D - B - C - D` |
| **James Vowles** | Williams | `D - B - C - D - B - B - C - B` |
| **Flavio Briatore** | Alpine | `A - B - B - A - C - D - A - A` |
| **Jonathan Wheatley** | Sauber / Audi | `B - A - A - B - B - C - C - B` |
| **Laurent Mekies** | RB (VCARB) | `B - A - A - B - B - B - C - A` |
| **Alan Permane** | RB (VCARB) | `B - A - A - B - D - C - A - B` |
| **Ayao Komatsu** | Haas | `B - B - C - C - D - C - C - B` |
| **Andy Cowell** | Aston Martin | `D - A - C - C - D - A - C - C` |

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
If you want to host your own version:

1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/marcfield23/F1-Sorting-Quiz.git](https://github.com/marcfield23/F1-Sorting-Quiz.git)
    ```
2.  **Update the Backend:**
    * Create a free account at [Formspree](https://formspree.io).
    * Create a new form and copy your `https://formspree.io/f/xv...` URL.
    * Open `index.html` and replace the fetch URL in the `showResult()` function.
3.  **Host it:**
    * Upload to GitHub Pages or Netlify Drop.

---

**Created by Marc Field**
