# Vent Calc

**VentCalc.cc** is a simple, focused calculator for healthcare professionals, designed to assist in ventilator-related calculations and assessments at the bedside.

## 🌐 Live Site

Visit: [https://ventcalc.cc](https://ventcalc.cc)

Or via GitHub Pages (if hosted there): [https://clephos.github.io/ventcalc](https://clephos.github.io/ventcalc)

---

## ⚙️ Features

- ✅ Calculate Ideal Body Weight (IBW)
- ✅ Tidal Volume (TV) & Minute Ventilation (V̇)
- ✅ Respiratory Rate (RR)
- ✅ Winter’s Formula for metabolic acidosis
- ✅ PaCO₂ Correction Tool
- ✅ Reference and Terms of Service pages
- ✅ Responsive and mobile-friendly design
- ✅ Built with React and Material UI

---

## 🚀 Getting Started

To run locally:

```bash
git clone https://github.com/<your-username>/ventcalc.git
cd ventcalc
npm install
npm start
```

Then open [http://localhost:3000](http://localhost:3000)

---

## 🛠 Tech Stack

- [React](https://reactjs.org/)
- [Material UI](https://mui.com/)
- [React Router DOM](https://reactrouter.com/)
- [gh-pages](https://github.com/tschaub/gh-pages) (optional for deployment)

---

## 📦 Deployment (GitHub Pages)

1. Add this to `package.json`:

```json
"homepage": "https://<your-username>.github.io/ventcalc"
```

2. Add deploy scripts:

```json
"predeploy": "npm run build",
"deploy": "gh-pages -d build"
```

3. Run:

```bash
npm run deploy
```

---

## ⚠️ Disclaimer

VentCalc is provided as an **informational tool only** and does not replace clinical judgment. It is not approved by the FDA and should not be used for critical medical decision-making without verification.

---

## 📬 Contact

For feedback, suggestions, or contributions:

**Email:** [hello@m31lab.com](mailto:hello@m31lab.com)  
**Developer:** [M31Lab LLC](https://m31lab.io)

---

## 📄 License

This project is licensed under the MIT License.
