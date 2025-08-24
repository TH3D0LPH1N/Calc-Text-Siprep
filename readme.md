# Calc-Text-Siprep

Hello!! My name is Wilson Chen, SI class of '25. This is a fun side project that I've been working on for the past couple of months, where I practice LaTeX by doing some edits on the current Calc BC textbook.

Hope you find this useful :)

The full text lies within the file called **`MainText.pdf`**.

The `.tex` files and PDFs for each chapter are in their respective `Chapter#` folders.

The preamble and other commands/settings are in `Support/Settings.tex`. The `Support/` folder also contains image files used in the chapters.

Links to all videos are here: [Google Drive Folder](https://drive.google.com/drive/folders/1Zf4oZXG6ctf94wPKOlyKIBbZ_X-aIGTz?usp=sharing).

Thanks for viewing :)


---

## 🚀 Getting Started

If you'd like to build the textbook yourself, here’s how you can set it up.

### 1. Clone the Repository

Open your terminal (Mac/Linux) or PowerShell (Windows) and run:

```bash
git clone https://github.com/TH3D0LPH1N/Calc-Text-Siprep.git
cd Calc-Text-Siprep
```

---

### 2. Install LaTeX

You’ll need a LaTeX distribution to compile the files:

- **Mac (MacTeX):**  
Download from [https://tug.org/mactex/](https://tug.org/mactex/) and follow the installer.  
After installation, make sure `pdflatex` or `xelatex` runs in your terminal.

- **Windows (MiKTeX):**  
Download from [https://miktex.org/download](https://miktex.org/download).  
During setup, allow MiKTeX to install missing packages on the fly.

- **Linux (TeX Live):**  
Install via your package manager, e.g.:  
```bash
sudo apt-get install texlive-full
```

---

### 3. Compile the Textbook

- To compile the **full textbook**, run:
```bash
pdflatex MainText.tex
```
(Run twice to update references.)

- To compile a **single chapter**, run:
```bash
pdflatex Chapter1/Chapter1.tex
```

The compiled PDF will appear in the same folder as the `.tex` file.

---

### 4. Recommended Editors

While you can use any text editor, these are popular for LaTeX:

- **Mac/Windows/Linux:** [TeXShop (MacTeX default)], [TeXworks], or [VS Code with LaTeX Workshop extension].
- **Online:** [Overleaf](https://overleaf.com) (import the repo for easy compiling in the cloud).

---

## 📂 Project Structure

```
Calc-Text-Siprep/
│
├── MainText.tex         # Main LaTeX file for the entire textbook
├── MainText.pdf         # Precompiled full PDF
│
├── Chapter1/            # Chapter 1 source + PDF
├── Chapter2/            # Chapter 2 source + PDF
│   ...
│
├── Support/             # Settings, images, preamble, macros
│   └── Settings.tex
```

---

## 🤝 Contributing

If you’d like to suggest edits, feel free to fork the repo and submit a pull request!