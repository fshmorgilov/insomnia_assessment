# Insomnia assessment task

Here's a **Markdown guide** on how to render the **FinanceBuddy presentation** using **Marp Online**, **Marp CLI**, and **VSCode Extension**.

---

### **Rendering FinanceBuddy Presentation with Marp**
---

## **1. Using Marp Online (https://demo.marpeditor.com/)**
### **Steps:**
1. Open [Marp Online Editor](https://demo.marpeditor.com/).
2. Copy and paste the **FinanceBuddy presentation Markdown file** into the editor.
3. Click the **Preview icon** (🖼️) to see the slide format.
4. To export as a PDF or PPTX:
   - Click on the **three-dot menu (⋮)** in the top-right.
   - Choose **Download as PDF** or **Download as PPTX**.

---

## **2. Rendering Locally using Marp CLI**
### **Setup Marp CLI:**
1. Install **Node.js** (if not already installed) from [nodejs.org](https://nodejs.org/).
2. Install **Marp CLI** globally:
   ```sh
   npm install -g @marp-team/marp-cli
   ```

---
### **Rendering the Presentation**
#### **To preview slides locally:**
```sh
marp financebuddy-presentation.md --preview
```
This opens the **Marp preview mode** in your browser.

#### **To export as a PDF:**
```sh
marp financebuddy-presentation.md --pdf
```
#### **To export as a PPTX:**
```sh
marp financebuddy-presentation.md --pptx
```

---

## **3. Viewing and Editing in VSCode**
### **Installing the Marp for VSCode Extension**
1. Open **VSCode**.
2. Go to **Extensions** (Ctrl+Shift+X).
3. Search for **Marp for VS Code** and install it.

---
### **Rendering Slides in VSCode**
1. Open the Markdown file (`financebuddy-presentation.md`) in VSCode.
2. Click on the **Preview button** (top right) or use:
   ```
   Ctrl+Shift+V
   ```
3. To export the slides:
   - Open **Command Palette** (Ctrl+Shift+P).
   - Search for **Marp: Export Slide Deck**.
   - Choose **PDF, PNG, or PPTX**.

