# 🚀 Episcan – AI-Powered Skin Health Scanner

> ✨ Your face, decoded by AI.  
> 🧠 Deep Learning meets Clean Design.  
> 🖥️ Built with React, TailwindCSS & PyTorch YOLOv8.

---

## 🧬 What is Episcan?

**Episcan** is a fully responsive, single-page React application designed to analyze facial skin health using **custom-trained YOLOv8 AI models**. It detects **acne** and **dark circles** from images and recommends skincare products — all packed in a sexy, animated UI that runs entirely on the client side.

Whether you're showcasing AI skills or frontend finesse, this project proves that **machine learning can look damn good.**

---

## 🎯 Features

- 🔍 AI-powered detection of **acne** and **dark circles**
- 📸 Upload or capture a photo with webcam
- 🧠 YOLOv8 models served via PyTorch (in `src/assets`)
- ⚡ Animated, smooth, mobile-first interface
- 🎨 Stunning responsive UI built with **React + TailwindCSS + Framer Motion**
- 🔥 Zero database – no data is stored, everything is live and lightweight

---

## 🖼️ Website Flow

1. **Loading Page** – Animated splash screen while everything loads
2. **Home Page** – Hero section with call to action + in-depth product description
3. **Test Page** – Upload or click a picture → image goes to local PyTorch model
4. **Results Page** – AI-detected output with highlights and options
5. **Products Page** – Smart product recommendations based on your results

---

## 🛠️ Tech Stack

| Layer           | Tools                                                           |
| --------------- | --------------------------------------------------------------- |
| **Frontend**    | React, Vite, Tailwind CSS, Framer Motion                        |
| **AI Models**   | PyTorch YOLOv8 (`acne.pt`, `darkcircle.pt`)                     |
| **Image Input** | Webcam / File Upload (`react-webcam`)                           |
| **Deployment**  | Vercel / GitHub Pages (Frontend), Localhost for model inference |

## Python backend (pseudo-code)
Exposes POST /predict that accepts an image and returns output

📸 Screenshots
| Upload Page       | Result Page       | Product Page      |
| ----------------- | ----------------- | ----------------- |
| ![](your_ss1.png) | ![](your_ss2.png) | ![](your_ss3.png) |

## 👨‍💻 Made With ❤️ by Aman Rajani
Portfolio: aman-rajani.vercel.app
LinkedIn: Aman Rajani (linkedin.com/in/aman-rajani)

## 📄 License
This project is for educational and portfolio use only. All AI models are trained by the author and are not for commercial redistribution.
---

Let me know if you want:
- Live demo badge section
- Python API starter code for model inference
- GitHub Actions for deployment to Vercel or GitHub Pages

## 📂 Project Structure

```bash
episcan/
│
├── public/
├── src/
│   ├── assets/          # Includes acne.pt & darkcircle.pt YOLOv8 models
│   ├── components/      # Navbar, Hero, Footer, Loader, etc.
│   ├── pages/           # Home.jsx, Test.jsx, Results.jsx, Products.jsx
│   ├── styles/          # Global styles (if any)
│   ├── App.jsx
│   └── main.jsx
├── tailwind.config.js
├── README.md
└── package.json

