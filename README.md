<div align="center">

<h1 align="center">
  <picture>
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:f2f1fa,100:e4e1fb&height=200&section=header&text=RedoSan%20Authenticity&fontSize=46&fontColor=4a3fb8&fontAlignY=38&desc=Watermarking%20%C2%B7%20C2PA%20%C2%B7%20Steganography%20%C2%B7%20DID&descSize=16&descAlignY=64&animation=fadeIn">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0f1a,100:6c5ce7&height=200&section=header&text=RedoSan%20Authenticity&fontSize=46&fontColor=8a7bf0&fontAlignY=38&desc=Watermarking%20%C2%B7%20C2PA%20%C2%B7%20Steganography%20%C2%B7%20DID&descSize=16&descAlignY=64&animation=fadeIn" width="100%" alt="RedoSan Authenticity" />
</picture>
</h1>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1400&color=8a7bf0&center=true&vCenter=true&width=640&height=110&lines=Digital+Authenticity+Toolkit%0A63+Algorithms+%E2%80%A2%2020+Modules%0AWatermarking+%2B+C2PA+%2B+Steganography%0ADID+%2B+Certificates+%2B+Fingerprints&multiline=true" alt="Typing SVG: project tagline" />

<br/>

<a href="https://github.com/Redo-San/RedoSan-Authenticity"><img src="https://img.shields.io/badge/site-redo--san.github.io-6c5ce7?style=for-the-badge&logo=github&logoColor=white" alt="Project site" /></a>
<a href="#license"><img src="https://img.shields.io/badge/license-GPL--2.0-00e676?style=for-the-badge" alt="License GPL-2.0" /></a>
<a href="#-modules"><img src="https://img.shields.io/badge/modules-20-8a7bf0?style=for-the-badge" alt="20 modules" /></a>
<a href="#-algorithm-breakdown"><img src="https://img.shields.io/badge/algorithms-63-6c5ce7?style=for-the-badge" alt="63 algorithms" /></a>
<a href="#-what-it-does"><img src="https://img.shields.io/badge/privacy-100%25%20client--side-00e676?style=for-the-badge" alt="100% client-side" /></a>
<img src="https://komarev.com/ghpvc/?username=Redo-San&label=visitors&color=6c5ce7&style=for-the-badge" alt="Profile visitors" />

</div>

## 🛡️ What it does

Digital authenticity toolkit — embed a verifiable proof of origin inside images, audio, video
and documents, then extract and verify it later. **Everything runs client-side**: no upload, no
account, no telemetry. Files never leave the machine.

Vanilla JavaScript, no framework, no build step.

## 📦 Modules

| Module                 | What it does                                                      |
| ---------------------- | ----------------------------------------------------------------- |
| **Watermark**          | Image watermarking — spatial, frequency and hybrid embedding      |
| **Audio Watermark**    | Audio watermarking across 8 algorithms                            |
| **Pixel Injection**    | Steganography and pixel-domain injection                          |
| **Document Watermark** | Zero-width characters, Unicode homoglyphs, whitespace replacement |
| **Fingerprint**        | Cryptographic and perceptual hashing                              |
| **C2PA**               | Content provenance manifests, CBOR / COSE Sign1                   |
| **Certificate**        | Digital passports — PDF, DOCX, EPUB, OTS                          |
| **DID**                | Decentralized identity — `did:key`, Ed25519 / P-256 / RSA         |
| **Timestamp**          | OpenTimestamps — create, verify, upgrade                          |
| **Forensic**           | ELA, noise analysis, JPEG marker inspection                       |
| **Metadata**           | EXIF reader                                                       |
| **Converter**          | FFmpeg.wasm for image, audio, video, documents, subtitles         |
| **Face Biometric**     | Face detection, registration and matching                         |
| **ID Forge**           | UUID v4 / v7, ULID, NanoID, SWHID                                 |

Exports to **PDF · DOCX · JSON · CSV · TXT · XML · HTML**. Interface in **8 languages**:
Arabic, German, English, Spanish, French, Japanese, Korean, Chinese.

## 🔢 Algorithm breakdown

Counts verified against the source registries, not documentation:

| Area               | Count | Verified in                                                  |
| ------------------ | ----: | ------------------------------------------------------------ |
| Image watermark    |     9 | `watermark.js` numeric dispatch cases `1`–`9`                |
| Audio watermark    |     8 | `aw1` … `aw8` embed/extract pairs                            |
| Pixel injection    |    22 | 19 embedding algorithms + 3 detection utilities              |
| Document watermark |     3 | `DOCW_ALGOS`: ZWC, Unicode homoglyphs, whitespace            |
| Fingerprint        |    21 | 17 cryptographic + 4 perceptual (pHash, dHash, aHash, wHash) |

**63 algorithms.** Cryptographic coverage: SHA-1, SHA-224/256/384/512,
SHA3-224/256/384/512, MD2, MD4, MD5, BLAKE2b, BLAKE2s, BLAKE3, RIPEMD-160, Whirlpool.

## 🧰 Tech stack

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />

No UI framework. No runtime dependency for the browser build.

## 🚀 Run it

```bash
git clone https://github.com/Redo-San/RedoSan-Authenticity.git
cd RedoSan-Authenticity
npm install
node cli/index.js --help      # the `redosan` CLI
node dev-server.js           # local web app on :8080
```

## 📊 Stats

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats-one-bice.vercel.app/api?username=Redo-San&show_icons=true&hide_border=true&bg_color=f2f1fa&title_color=4a3fb8&text_color=1f2328&icon_color=1a7f4b&include_all_commits=true">
    <img height="168" src="https://github-readme-stats-one-bice.vercel.app/api?username=Redo-San&show_icons=true&hide_border=true&bg_color=0f0f1a&title_color=6c5ce7&text_color=e8e8f0&icon_color=00e676&include_all_commits=true" alt="RedoSan GitHub statistics" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=Redo-San&hide_border=true&background=f2f1fa&ring=4a3fb8&fire=4a3fb8&currStreakLabel=4a3fb8&sideLabels=1f2328&dates=6b7280">
    <img height="168" src="https://streak-stats.demolab.com?user=Redo-San&hide_border=true&background=0F0F1A&ring=6c5ce7&fire=00e676&currStreakLabel=6c5ce7&sideLabels=8a7bf0&dates=9b9bb5" alt="Contribution streak" />
  </picture>
  <br/>
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats-one-bice.vercel.app/api/top-langs/?username=Redo-San&layout=compact&hide_border=true&bg_color=f2f1fa&title_color=4a3fb8&text_color=1f2328&langs_count=8&custom_title=Toolchain">
    <img width="62%" src="https://github-readme-stats-one-bice.vercel.app/api/top-langs/?username=Redo-San&layout=compact&hide_border=true&bg_color=0f0f1a&title_color=6c5ce7&text_color=e8e8f0&langs_count=8&custom_title=Toolchain" alt="Most used languages" />
  </picture>
</div>

## 📌 Featured

<div align="center">
  <a href="https://github.com/Redo-San/RedoSan-Authenticity">
    <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=Redo-San&repo=RedoSan-Authenticity&hide_border=true&bg_color=f2f1fa&title_color=4a3fb8&text_color=1f2328&icon_color=1a7f4b">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Redo-San&repo=RedoSan-Authenticity&hide_border=true&bg_color=0f0f1a&title_color=6c5ce7&text_color=e8e8f0&icon_color=00e676" alt="RedoSan-Authenticity repository card" />
  </picture>
  </a>
</div>

## 🔗 Connect

<div align="center">

[![Website](https://img.shields.io/badge/website-redo--san.github.io-6c5ce7?style=for-the-badge&logo=firefox&logoColor=white)](https://redo-san.github.io/RedoSan-Authenticity/)
[![Links](https://img.shields.io/badge/links-linktr.ee-8a7bf0?style=for-the-badge&logo=link&logoColor=white)](https://linktr.ee/RedoSan)
[![Follow](https://img.shields.io/badge/follow-%40Redo--San-00e676?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Redo-San)

_Based in Baghdad, Iraq._

</div>

<h1 align="center">
  <picture>
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:e4e1fb,100:f2f1fa&height=120&section=footer&text=GPL--2.0%20%C2%B7%20Everything%20stays%20on%20your%20machine&fontSize=22&fontColor=4a3fb8&fontAlignY=60&animation=fadeIn">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6c5ce7,100:0f0f1a&height=120&section=footer&text=GPL--2.0%20%C2%B7%20Everything%20stays%20on%20your%20machine&fontSize=22&fontColor=8a7bf0&fontAlignY=60&animation=fadeIn" width="100%" alt="Footer" />
</picture>
</h1>

<a name="license"></a>

## 📄 License

GPL-2.0. See [LICENSE](https://github.com/Redo-San/RedoSan-Authenticity/blob/main/LICENSE).
