<div align="center">

<img src="banner.svg" alt="APIC - Advanced Image Processing Center" width="100%">

<br>

### 🎨 A full photo studio that lives inside your browser tab.
**Edit · Convert · Compress · Remove Backgrounds · Resize** — with on-device AI.<br>
No uploads. No servers. No paywalls.

<br>

[![Live Demo](https://img.shields.io/badge/🚀_LIVE_DEMO-Launch_APIC-39ff9d?style=for-the-badge&labelColor=07070a)](https://akhouri-anmol-kumar.github.io/APIC-web/)
[![Desktop App](https://img.shields.io/badge/🖥️_APIC_FOR_PC-Windows-3ee0ff?style=for-the-badge&labelColor=07070a)](https://github.com/Akhouri-Anmol-Kumar/APIC/releases/download/APIC/APIC.zip)

![Price](https://img.shields.io/badge/price-FREE-39ff9d?style=flat-square&labelColor=07070a)
![Privacy](https://img.shields.io/badge/uploads-ZERO-ff37c9?style=flat-square&labelColor=07070a)
![AI](https://img.shields.io/badge/AI-on--device-3ee0ff?style=flat-square&labelColor=07070a)
![Runs on](https://img.shields.io/badge/runs_on-any_browser-fff23e?style=flat-square&labelColor=07070a)
![Status](https://img.shields.io/badge/status-live-39ff9d?style=flat-square&labelColor=07070a)
![License](https://img.shields.io/badge/license-All_Rights_Reserved-ff37c9?style=flat-square&labelColor=07070a)

<br>

[**✨ Features**](#-five-tools-zero-uploads) &nbsp;•&nbsp;
[**🧠 On-device AI**](#-on-device-ai) &nbsp;•&nbsp;
[**🔒 Privacy**](#-privacy-by-design) &nbsp;•&nbsp;
[**🖥️ Desktop**](#️-apic-for-pc) &nbsp;•&nbsp;
[**❓ FAQ**](#-faq) &nbsp;•&nbsp;
[**📄 License**](#-license)

</div>

<br>

---

## 👋 What is APIC?

**APIC** (*Advanced Image Processing Center*) is a free online photo editor that runs **entirely in your browser**. Open the page, drop in a picture, and get to work. Your image is processed on **your own device**, so nothing is sent to a server, there's no queue, and there's no watermark.

> 💡 **The idea:** most online image tools quietly upload your photos to someone else's computer. APIC flips that. The tools come to you, and your photos stay with you.

<br>

## ⚡ Five Tools. Zero Uploads.

<table>
  <tr>
    <td align="center" width="20%">
      <h3>🖌️<br>Edit</h3>
      <sub>Filters, brightness, contrast, saturation, blur, rotate and flip, <b>live on canvas</b>.</sub>
    </td>
    <td align="center" width="20%">
      <h3>🔁<br>Convert</h3>
      <sub>PNG, JPEG, WebP, BMP, ICO or PDF. <b>Six formats</b>, no round trips to a server.</sub>
    </td>
    <td align="center" width="20%">
      <h3>📦<br>Compress</h3>
      <sub>Smart <b>target-size search</b> finds the best quality that fits your file size limit.</sub>
    </td>
    <td align="center" width="20%">
      <h3>✂️<br>Remove BG</h3>
      <sub><b>On-device AI</b> cuts your subject out cleanly. No upload, no waiting in line.</sub>
    </td>
    <td align="center" width="20%">
      <h3>📐<br>Resize</h3>
      <sub>Exact <b>pixel or percent</b> dimensions with step-down resampling for crisp results.</sub>
    </td>
  </tr>
</table>

<br>

## 🎛️ Pro Colour Tools

Not just sliders. APIC ships with the kind of colour tools you'd expect from desktop editors:

| Tool | What it does |
|:--|:--|
| 📊 **Live Histogram** | See your tonal range update in real time as you edit |
| 📈 **RGB Curves** | Shape shadows, mids and highlights per channel |
| 🌈 **HSL Colour Mixer** | Fine-tune the hue, saturation and luminance of individual colours |
| 🎬 **3-Way Colour Grading** | Grade shadows, midtones and highlights separately |
| 🔍 **Clarity** | Add punch and local contrast |
| 🎞️ **Grain** | Add film-style texture |
| 🧊 **3D LUT Export** | Export your look as a `.cube` file for use in other tools |

<br>

## 🧠 On-Device AI

APIC runs real AI models **inside your browser** using **ONNX Runtime + WebAssembly**. The first time you use an AI tool, the model downloads once and is **cached on your device**. After that it starts fast and works without sending anything anywhere.

### ✂️ Background Remover

| Mode | Model size (first download) | Best for |
|:--|:--:|:--|
| 🟢 **Lite** | ~5 MB | Quick cutouts, slow connections, phones |
| 🔵 **Fast** | ~44 MB | Everyday photos with a good balance of speed and quality |
| 🟣 **Maximum** | ~176 MB | Hair, fine edges and tricky subjects (multi-pass, slower) |

### 🪄 Object Remover

Paint over something you want gone, such as a person, a sign or a blemish, and AI inpainting fills the area to match its surroundings.

| Engine | Model | Notes |
|:--|:--|:--|
| ⚡ **Fast** | MI-GAN (~44 MB) | Great for small objects and quick fixes |
| 💎 **Ultra** | LaMa (~208 MB) | Highest accuracy, offered on desktop-class devices |

> 🛟 If a model download stalls, APIC retries automatically and shows a **Retry** button if it still can't connect.

<br>

## 🔒 Privacy by Design

```mermaid
flowchart LR
    A["📷 Your photo"] --> B["🌐 Your browser<br/>edit · convert · compress<br/>resize · AI"]
    B --> C["💾 Your download"]
    B -. "❌ never" .-> D["☁️ Any server"]
    style A fill:#07070a,stroke:#39ff9d,color:#eef1f6
    style B fill:#07070a,stroke:#3ee0ff,color:#eef1f6
    style C fill:#07070a,stroke:#39ff9d,color:#eef1f6
    style D fill:#07070a,stroke:#ff37c9,color:#ff37c9,stroke-dasharray: 5 5
```

- 🛡️ **Your images never leave your device.** Every tool runs locally.
- 🙅 **No account needed to edit.** Use every tool freely.
- 🔑 **Sign in only to export**, with one tap using Google. This only uses your name, email and photo for your account.
- 🌗 **Light, dark or system theme**, remembered for next time.

<br>

## 🖥️ APIC for PC

Prefer it on your desk? **APIC for PC** is a Windows app that runs **fully offline** with the same edit, convert and compress tools. No account needed.

<div align="center">

[![Download APIC for PC](https://img.shields.io/badge/⬇️_DOWNLOAD-APIC_for_Windows-ff37c9?style=for-the-badge&labelColor=07070a)](https://github.com/Akhouri-Anmol-Kumar/APIC/releases/download/APIC/APIC.zip)

</div>

<br>

## 🧰 Built With

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-e34f26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572b6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=black)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-005ced?style=for-the-badge&logo=onnx&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654ff0?style=for-the-badge&logo=webassembly&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222?style=for-the-badge&logo=github&logoColor=white)

</div>

A single-page, client-side app: canvas-based image pipeline, ONNX models running on WebAssembly, Firebase for Google sign-in, and GitHub Pages for hosting.

<br>

## ❓ FAQ

<details>
<summary><b>Is APIC really free?</b></summary>
<br>
Yes. There are no paid tiers. You can use every tool without an account and sign in with Google only when you export your work.
</details>

<details>
<summary><b>Are my photos uploaded to a server?</b></summary>
<br>
No. Editing, converting, compressing, resizing, background removal and object removal all run on your own device.
</details>

<details>
<summary><b>Which formats can I convert between?</b></summary>
<br>
PNG, JPEG, WebP, BMP, ICO and PDF. Use <b>PNG or WebP</b> if you want to keep a transparent background after removing it.
</details>

<details>
<summary><b>Can I compress an image to an exact file size?</b></summary>
<br>
Yes. The Compress tool searches for the best quality that fits your target size, so you can meet an upload limit without guessing.
</details>

<details>
<summary><b>Why is the first AI run slower?</b></summary>
<br>
AI tools download their model once. After that it's cached in your browser, so later runs start much faster, even with a weak connection.
</details>

<details>
<summary><b>Is there an offline version?</b></summary>
<br>
Yes, <b>APIC for PC</b> is a Windows app that works fully offline. See the <a href="#️-apic-for-pc">desktop section</a> above.
</details>

<br>

## 🐛 Found a Bug or Have an Idea?

Open an issue on the [APIC issue tracker](https://github.com/Akhouri-Anmol-Kumar/APIC/issues). Feedback is always welcome.

<br>

## 📄 License

**Copyright © 2026 Akhouri Anmol Kumar. All Rights Reserved.**

This project is proprietary. You're welcome to use the live website and read the source for personal learning, but copying, re-hosting or building derivative products is **not permitted** without written permission. See [`LICENSE`](LICENSE) for the full terms.

<br>

<div align="center">

### 💚 Made with care by [Akhouri Anmol Kumar](https://github.com/Akhouri-Anmol-Kumar)
**An Akhouri Systems product**

<br>

[![Try APIC now](https://img.shields.io/badge/✨_TRY_APIC_NOW-it's_free-39ff9d?style=for-the-badge&labelColor=07070a)](https://akhouri-anmol-kumar.github.io/APIC-web/)

<sub>⭐ If APIC helped you, a star on this repo means a lot!</sub>

</div>
