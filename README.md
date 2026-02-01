# HB-Immersive-Final.
HB IMMERSIVE - Site Officiel &amp; Portfolio Immersif. (Propriété exclusive de Héritier Baguma. Basé à Lubumbashi, RDC
HB-Immersive/
├── README.md
├── LICENSE
├── NOTICE
├── docs/
│   ├── ARCHITECTURE.md
│   ├── FEATURES.md
│   ├── MARKETING.md
│   └── ROADMAP.md
├── public/
│   ├── assets/
│   │   ├── images/
│   │   │   ├── screenshots/
│   │   │   │   ├── fr/
│   │   │   │   └── en/
│   │   │   ├── logo.png
│   │   │   └── favicon.ico
│   │   └── videos/
│   │       └── demo.mp4
│   ├── css/
│   │   └── style.min.css
│   ├── js/
│   │   └── main.min.js
│   └── index.html
└── .gitignorePROPRIETARY SOFTWARE LICENSE
Copyright (c) 2026 HB IMMERSIVE, Inc. All rights reserved.

1. **LICENSE GRANT**
   HB IMMERSIVE grants you a non-exclusive, non-transferable license to use this software solely for personal, non-commercial evaluation. Any other use requires written permission.

2. **RESTRICTIONS**
   - No reverse engineering, decompilation, or disassembly.
   - No reproduction, distribution, or creation of derivative works.
   - No removal of copyright notices or proprietary marks.

3. **CONFIDENTIALITY**
   All information in this repository is confidential and protected under DRC and international law.

4. **TERMINATION**
   This license terminates immediately upon violation. You must then destroy all copies of the software.

5. **JURISDICTION**
   Disputes shall be resolved in Lubumbashi, DRC, under Congolese law.

Contact: legal@hbimmersive.comLEGAL NOTICE – HB IMMERSIVE PROPRIETARY MATERIAL

⚠️ WARNING: This repository contains confidential and proprietary information. Unauthorized use is prohibited and punishable by law.

Report violations: legal@hbimmersive.com

© 2026 HB IMMERSIVE, Inc. All rights reserved.# **HB IMMERSIVE** – **Proprietary AR Technology**
**[hbimmersive.netlify.app](https://hbimmersive.netlify.app)** | **[Contact](#contact--legal)**

> ⚠️ **WARNING**: This repository is **protected by copyright and trade secret laws**. Unauthorized use is prohibited.

---

## **🌍 Overview**
HB IMMERSIVE transforms smartphones into **interactive 3D hologram projectors** using patent-pending AR technology.

| **Protection Type**       | **Status**               |
|---------------------------|--------------------------|
| Copyright                 | Registered (DRC)         |
| Trademark ("HB IMMERSIVE")| ™ (Common Law)           |
| Patent (AR Interaction)   | Pending (PCT/DRC2026/...)|

---

## **🎯 Core Features**
| Feature                     | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| **Hand-Gesture AR Control** | Proprietary algorithm for hand-tracked hologram manipulation.              |
| **One-Click Social Export** | Seamless video sharing to TikTok/Instagram with watermarking.              |
| **Premium Model Library**  | 50+ exclusive 3D models (protected by DRM).                                |

---

## **📱 Screenshots**
### **French Version**
<table>
  <tr>
    <td><img src="./public/assets/images/screenshots/fr/home.jpg" width="200" alt="HB IMMERSIVE Home"/></td>
    <td><img src="./public/assets/images/screenshots/fr/ar_mode.jpg" width="200" alt="AR Mode"/></td>
  </tr>
</table>

---

## **🎥 Demo**
[![HB IMMERSIVE Demo](./public/assets/images/video-poster.jpg)](https://hbimmersive.netlify.app/demo)

---

## **📂 Documentation**
- [Technical Architecture](./docs/ARCHITECTURE.md)
- [Feature Specifications](./docs/FEATURES.md)

---

## **📩 Contact & Legal**
- **Business**: heritier.baguma@hbimmersive.com
- **Legal**: legal@hbimmersive.com
- **Press**: press@hbimmersive.com

© 2026 HB IMMERSIVE, Inc. All rights reserved.
## **Protected Components**
| Component               | Protection Type       |
|-------------------------|-----------------------|
| Gesture Recognition     | Trade Secret          |
| 3D Model DRM            | Copyright + DRM       |<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="robots" content="noindex, nofollow">
    <meta name="copyright" content="© 2026 HB IMMERSIVE, Inc.">
    <title>HB IMMERSIVE | Proprietary Demo</title>
    <link rel="stylesheet" href="css/style.min.css">
    <link rel="icon" href="assets/images/favicon.ico">
</head>
<body>
    <div class="legal-banner">⚠️ Confidential – © HB IMMERSIVE 2026</div>
    <header>
        <img src="assets/images/logo.png" alt="HB IMMERSIVE™" class="logo">
    </header>
    <section class="hero">
        <h1>HB IMMERSIVE™</h1>
        <p>Patent-pending holographic AR technology.</p>
        <video controls poster="assets/images/video-poster.jpg" oncontextmenu="return false;">
            <source src="assets/videos/demo.mp4" type="video/mp4">
        </video>
        <p class="watermark">CONFIDENTIAL – © HB IMMERSIVE 2026</p>
    </section>
    <footer>
        <p>© 2026 HB IMMERSIVE, Inc. | <a href="mailto:legal@hbimmersive.com">Legal</a></p>
    </footer>
    <script src="js/main.min.js"></script>
</body>
</html>// © 2026 HB IMMERSIVE – Proprietary Code
document.addEventListener('contextmenu',e=>e.preventDefault());
document.onkeydown=function(e){if(e.key=='F12'||(e.ctrlKey&&e.shiftKey&&(e.key=='I'||e.key=='J'))){alert('🚨 Action interdite.');return false;}};
const watermark=document.createElement('div');watermark.style.position='fixed';watermark.style.bottom='20px';watermark.style.right='20px';watermark.style.color='rgba(0,0,0,0.5)';watermark.style.fontSize='12px';watermark.style.zIndex='9999';watermark.textContent='CONFIDENTIAL – © HB IMMERSIVE 2026';document.body.appendChild(watermark);# Fichiers sensibles
*.key
*.pem
*.env
*.secret

# Dossiers internes
internal/
legal/
contracts/

# Fichiers système
.DS_Store
Thumbs.db
*.loggit add .
git commit -m "🔒 Initial commit: Proprietary HB IMMERSIVE repository (Copyright © 2026)"
git push origin main
