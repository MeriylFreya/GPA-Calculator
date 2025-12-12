# GPA-Calculator
This is a simple, all-in-one GPA Calculator that works on any device. It helps students calculate their **SGPA** (Semester Grade Point Average) and **CGPA** (Cumulative Grade Point Average).

The entire project is built inside **one single file** (`index.html`). You do not need to install anything or download extra files.

## Project Structure
*   **`index.html`** - This file contains everything: the layout (HTML), the design (CSS), and the calculator logic (JavaScript).

**No servers. No databases**

---

## Why is this BETTER than other calculators?

Most GPA calculators found on Google are rigid. If your university changes the passing marks or grading logic, those calculators become useless.

Here is why this project is smarter:

### 1. You Make the Rules (Flexible Settings)
Other calculators force you to use their grading system (e.g., "90+ is an O grade").
*   **This Calculator:** Includes a **Settings Panel**.
*   Does your college give an 'A' grade at 80 marks? Or 85? **You can change it easily.**
*   You can edit the marks range and grade points to match **any** university or college.

### 2. Calculates from Raw Marks
Other calculators ask you to enter the Grade directly (like "A" or "B"). This means you have to sit with a calculator and figure out your grade first!
*   **This Calculator:** You just type your **Exam Marks** (CIE and SEE).
*   It does the math: `Internal Marks + (Final Exam / 2)` automatically.

### 3. Zero Installation
*   It is just **one file**. You can email it to a friend, keep it on a USB stick, or run it without Wi-Fi after download.

---

## How to Use

### Step 1: Open the App
Simply double-click the `index.html` file. It will open in your web browser (Chrome, Edge, Safari, Firefox).

### Step 2: Check the Grading Scale (Important!)
Look at the top section named **"Grading Scale"**.
*   This shows how marks are converted to points (e.g., 90-100 marks = 10 points).
*   If your college follows a different rule, just type over the numbers to change them.

### Step 3: Calculate SGPA
1.  Click the **"SGPA Calculator"** tab.
2.  Click **"+ Add Subject"** to add rows.
3.  Enter your **CIE** (Internal marks out of 50).
4.  Enter your **SEE** (Final exam marks out of 100).
5.  Enter the **Credits** for that subject.
6.  Click **Calculate SGPA**.

### Step 4: Calculate CGPA
1.  Click the **"CGPA Calculator"** tab at the top.
2.  Add your semesters.
3.  Enter the SGPA for each semester.
4.  Click **Calculate CGPA**.

---

## Tech Stack

*   **HTML5:** For the structure.
*   **CSS3:** For the colors and card design (written inside the HTML file).
*   **JavaScript:** For the math and logic (written inside the HTML file).

**Total Files:** 1 (`index.html`)
