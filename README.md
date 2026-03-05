# ⚛️ Schrödinger Equation — Quantum Mechanics Interactive Guide

<div align="center">

[![🌐 Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-Open%20Interactive%20Guide-1565c0?style=for-the-badge&logoColor=white)](https://schdigner-equation-casestudy-quantum1.netlify.app/)&nbsp;&nbsp;
[![📄 Word Doc](https://img.shields.io/badge/📄%20Word%20Doc-Download%20Guide-2e7d32?style=for-the-badge)](./Schrodinger_Equation_Guide.docx)&nbsp;&nbsp;
[![📘 README](https://img.shields.io/badge/📘%20Docs-README-6a1b9a?style=for-the-badge)](./README.md)

</div>

---

> *"If quantum mechanics hasn't profoundly shocked you, you haven't understood it yet."*
> — Niels Bohr

A complete, self-contained educational resource on the Schrödinger Equation — from first principles to real-world applications. Available in two formats: an **interactive HTML experience** and a **professional Word document**.

---

## 🎮 Demo

| Type | Link | Description |
|---|---|---|
| 🌐 **Interactive Web Guide** | [🚀 Live on Netlify](https://schdigner-equation-casestudy-quantum1.netlify.app/) | Open in any browser — hosted live |
| 📄 **Word Document** | [`Schrodinger_Equation_Guide.docx`](./Schrodinger_Equation_Guide.docx) | Download and open in Word / LibreOffice |

### Demo Preview

```
┌─────────────────────────────────────────────────────────┐
│  ⚛️  The Schrödinger Equation                            │
│                                                         │
│          Ψ  (animated particle wave)                    │
│                                                         │
│  [Intro] [Wave Fn] [Equation] [TISE] [Box] [Visualizer] │
│                ↓                                        │
│  ┌──────────────────────────────────────────────────┐   │
│  │  🌊 Wave Function Visualizer                      │   │
│  │  ψ₃(x) = √(2/L) · sin(3πx/L)   n = [1──●──6]   │   │
│  │  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~             │   │
│  │  ⚡ Energy Levels  [n=1] [n=2] [n=3] ...          │   │
│  └──────────────────────────────────────────────────┘   │
│                                                         │
│  🧠 Quiz  ·  🏆 Hydrogen Atom  ·  🔬 Applications       │
└─────────────────────────────────────────────────────────┘
```

> **To run the demo:** Open the folder and double-click `index.html`. No setup needed.

---

## 📁 Project Structure

```
Schrödinger Equation/
├── index.html                        # Interactive web guide (open in any browser)
├── Schrodinger_Equation_Guide.docx   # Full Word document reference
└── README.md                         # This file
```

---

## 🚀 Quick Start

### Option 1 — Interactive HTML (Recommended)
Open `index.html` in any modern web browser. No installation, no server, no dependencies required.

```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html

# Or simply double-click the file in your file explorer
```

Works fully offline. Tested in Chrome, Firefox, Edge, and Safari.

### Option 2 — Word Document
Open `Schrodinger_Equation_Guide.docx` in Microsoft Word or any compatible editor (LibreOffice, Google Docs).

### Option 3 — Host Online (GitHub Pages)
To share the demo publicly:

```bash
# 1. Push to a GitHub repository
git init
git add .
git commit -m "Add Schrödinger Equation interactive guide"
git remote add origin https://github.com/YOUR_USERNAME/schrodinger-equation.git
git push -u origin main

# 2. Enable GitHub Pages in Settings → Pages → Deploy from: main branch
# 3. Your demo will be live at:
#    https://YOUR_USERNAME.github.io/schrodinger-equation/
```

---

## 📖 What's Inside

### Interactive HTML Guide (`index.html`)

| Feature | Description |
|---|---|
| 🌊 **Hero Animation** | Live particle wave simulation on load |
| 📍 **Sticky Navigation** | Jump to any section instantly |
| 📊 **Reading Progress Bar** | Visual indicator of how far you've read |
| 🎛️ **Wave Function Visualizer** | Live canvas — adjust quantum number n (1–6) |
| ⚡ **Energy Level Diagram** | Clickable levels that update the visualizer |
| 📑 **Tabbed Content** | Separation of variables explained step by step |
| 🧠 **Interactive Quiz** | 5 questions with instant feedback and explanations |
| 📱 **Fully Responsive** | Works on desktop, tablet, and mobile |

### Word Document (`Schrodinger_Equation_Guide.docx`)

Covers all 11 sections with formatted formulas, tables, callout boxes, headers, and footers.

---

## 🧪 Content Coverage

### Sections

1. **Introduction to Quantum Mechanics** — why classical physics fails at the atomic scale
2. **The Wave Function Ψ(x, t)** — Born's Rule, normalization, and properties
3. **The Schrödinger Equation** — every symbol explained; TDSE in full
4. **Time-Independent Schrödinger Equation (TISE)** — separation of variables, eigenvalue equation
5. **Particle in a Box** — full 5-step worked solution; quantization derived from scratch
6. **Energy Level Summary** — zero-point energy, quantum number comparison
7. **Extension to 3D and Hydrogen Atom** — quantum numbers n, l, mₗ; the −13.6 eV/n² result
8. **Physical Interpretation** — Copenhagen interpretation, wave function collapse, Schrödinger's Cat
9. **Operators and Observables** — expectation values, commutators, uncertainty principle
10. **Real-World Applications** — transistors, lasers, MRI, quantum computers, drug design
11. **Key Takeaways** — all major equations in one reference table

### Key Equations Covered

```
Time-Dependent:      iℏ (∂Ψ/∂t) = ĤΨ
Time-Independent:    Ĥψ = Eψ
Born's Rule:         P(x,t) = |Ψ(x,t)|²
Normalization:       ∫|Ψ|² dx = 1
Particle in a Box:   Eₙ = n²π²ℏ²/(2mL²)
Hydrogen Atom:       Eₙ = −13.6 eV / n²
Uncertainty:         Δx · Δp ≥ ℏ/2
```

---

## 🎯 Who Is This For?

| Audience | How to Use It |
|---|---|
| **High school students** | Start with Sections 1–3; use the visualizer to build intuition |
| **University students (introductory physics)** | Work through all sections; focus on Sections 4–6 for problem-solving |
| **Self-learners** | Follow the HTML guide end-to-end; take the quiz to test understanding |
| **Educators / lecturers** | Use as a lecture supplement or assign as pre-reading material |
| **Developers / researchers** | Reference the Word document for formatted equations and tables |

---

## 🛡️ Self-Defence Clause (Academic Integrity)

This project is a **teaching resource**, not a shortcut. It is designed to build genuine understanding, not to be copied as coursework.

- All content is original and written from first principles.
- Mathematical derivations are shown step by step so readers can verify every result independently.
- The quiz is designed to expose gaps in understanding, not to provide answers to memorize.
- Readers are encouraged to work through derivations on paper, not just read them passively.

> ⚠️ If you are a student: use this resource to *understand* the material. Your exam will ask you to derive and apply — not to recall what a website said.

---

## 🖥️ Technical Notes

### HTML File
- **Zero dependencies** — pure HTML, CSS, and vanilla JavaScript
- **No internet required** — works completely offline
- **No build step** — open directly in a browser
- **Canvas-based visualizer** — uses the HTML5 `<canvas>` API for wave function rendering
- **Responsive layout** — CSS Grid and Flexbox; tested at widths from 320px to 2560px

### Browser Compatibility

| Browser | Support |
|---|---|
| Chrome 90+ | ✅ Full support |
| Firefox 88+ | ✅ Full support |
| Edge 90+ | ✅ Full support |
| Safari 14+ | ✅ Full support |
| Internet Explorer | ❌ Not supported |

### Word Document
- Created with `docx.js` — standard Open XML format
- Compatible with Microsoft Word 2016+, LibreOffice 7+, Google Docs
- All equations are typeset in monospace for clarity and copy-paste compatibility

---

## 📐 Physics Accuracy Statement

All physics content in this resource is:

- Consistent with standard university-level quantum mechanics curricula (Griffiths, Shankar, Cohen-Tannoudji)
- Mathematically verified — derivations checked against known results
- Pedagogically simplified where necessary, but **never incorrect**
- Focused on the non-relativistic Schrödinger Equation (the Dirac equation for relativistic QM is out of scope)

If you find an error, discrepancy, or ambiguity, please flag it — accuracy matters in physics.

---

## 📚 Further Reading

To go deeper after this guide:

- **"Introduction to Quantum Mechanics"** — David J. Griffiths *(the standard undergraduate textbook)*
- **"Principles of Quantum Mechanics"** — R. Shankar *(more rigorous, graduate level)*
- **"The Feynman Lectures on Physics, Vol. III"** — Feynman, Leighton, Sands *(freely available online)*
- **MIT OpenCourseWare 8.04** — Quantum Physics I *(free full course with problem sets)*
- **PhET Interactive Simulations** — University of Colorado *(browser-based quantum simulations)*

---

## 🏷️ Version

| Field | Value |
|---|---|
| Version | 1.0.0 |
| Created | March 2026 |
| Format | HTML + DOCX |
| Physics scope | Non-relativistic quantum mechanics |
| License | Educational use — freely shareable with attribution |

---

<div align="center">

Made with ❤️ for curious minds everywhere.

**The universe, at its deepest level, is quantum mechanical.**

---

[![🌐 Open Demo](https://img.shields.io/badge/🌐%20Open%20Demo-index.html-1565c0?style=for-the-badge)](./index.html)

</div>
