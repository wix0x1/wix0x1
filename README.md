<!--
  WALID | WIX0X1
  Android Systems & UI Engineer — WaveZone
  Theme: Warm Sunset Orange, Frosted Glass, Multi-Module Clean Architecture
-->

<!-- =============== HEADER =============== -->
<p align="center">
  <img
    width="100%"
    src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:FFEDD5,45:FB923C,100:EA580C&text=Walid&fontSize=62&fontColor=431407&fontAlignY=38&animation=fadeIn&desc=Android%20Engineer%20%E2%80%A2%20Creator%20of%20WaveZone&descAlignY=60&descSize=18"
    alt="Walid — Android Engineer"
  />
</p>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=17&duration=2600&pause=900&color=EA580C&center=true&vCenter=true&width=640&lines=Architecting+WaveZone+(com.wavezone.app)+%F0%9F%8C%8A;10-Module+Clean+Architecture+in+100%25+Kotlin;Zero-Telemetry+%26+Privacy-First+Media+Extraction;Jetpack+Compose+%E2%80%A2+Material+3+%E2%80%A2+Frosted+Glass+UI+%E2%9C%A8"
    alt="Animated introduction"
  />
</p>

<p align="center">
  <a href="https://github.com/wix0x1">
    <img src="https://img.shields.io/badge/GitHub-wix0x1-431407?style=for-the-badge&logo=github&logoColor=FFEDD5" alt="GitHub"/>
  </a>
  <a href="https://github.com/wix0x1/Wave-Zone-Releases">
    <img src="https://img.shields.io/badge/WaveZone-Releases-EA580C?style=for-the-badge&logo=android&logoColor=white" alt="WaveZone Releases"/>
  </a>
  <img src="https://img.shields.io/badge/Zero_Telemetry-100%25_Private-FB923C?style=for-the-badge&logo=proton&logoColor=431407" alt="Privacy First"/>
</p>

---

## 👋 Hey, I'm Walid

I engineer native Android applications where **strict architectural modularity**, **tactile UI polish**, and **uncompromising user privacy** converge.

My flagship work is **[WaveZone](https://github.com/wix0x1/Wave-Zone-Releases)** (`com.wavezone.app`)—a 100% private, zero-telemetry Android media client and stream extractor built from the ground up with **Kotlin**, **Jetpack Compose**, and **Material 3**.

<p align="center">
  <i>"Less complexity. Better experiences. Complete user control."</i>
</p>

---

## 🌊 WaveZone — Flagship Engineering

<p align="center">
  <img
    width="100%"
    src="https://capsule-render.vercel.app/api?type=rounded&height=140&color=0:FFF7ED,50:FDBA74,100:F97316&text=WAVEZONE&fontSize=40&fontColor=431407&fontAlignY=44&animation=fadeIn&desc=100%25%20Private%20Media%20Client%20%26%20Stream%20Extractor&descAlignY=70&descSize=16"
    alt="WaveZone — Your media, your privacy"
  />
</p>

<table>
  <tr>
    <td width="62%" valign="middle">
      <h3>🎯 The Engineering Philosophy</h3>
      <p>
        Most media utilities on Android force a trade-off between functionality, invasive tracking, and dated interfaces. <b>WaveZone</b> eliminates that compromise—combining high-speed stream extraction and offline downloads with a responsive, frosted-glass aesthetic.
      </p>
      <ul>
        <li>🔒 <b>Strict Zero-Telemetry Policy:</b> Zero analytics SDKs, zero crash-reporting trackers, and zero background data harvesting.</li>
        <li>🎨 <b>Frosted-Glass & Bento UI:</b> Adaptive Jetpack Compose layouts featuring translucent surfaces, warm sunset accents, and smooth micro-interactions.</li>
        <li>⚡ <b>Aggressive Build Optimization:</b> Compiled against <b>Android SDK 35</b> (Min SDK 21) with <b>Java 21</b>, <b>Gradle 9.5.1</b>, and strict <b>R8 shrinking/obfuscation</b> for a lean APK footprint and instant cold starts.</li>
        <li>🧱 <b>Scalable Modularity:</b> Strictly decoupled into <b>10 independent Gradle modules</b> to enforce clean boundaries and parallel compilation.</li>
      </ul>
      <p align="center">
        <a href="https://github.com/wix0x1/Wave-Zone-Releases">
          <img src="https://img.shields.io/badge/Download_Latest_APK-EA580C?style=for-the-badge&logo=github&logoColor=white" alt="Download WaveZone"/>
        </a>
      </p>
    </td>
    <td width="38%" align="center" valign="middle">
      <!-- Upload your screenshot to: assets/wave-zone-home.jpg -->
      <img
        src="./assets/wave-zone-home.jpg"
        width="260"
        alt="WaveZone home screen"
      />
      <br/>
      <sub><b>WaveZone UI</b> — Warm sunset tones & frosted-glass surfaces</sub>
    </td>
  </tr>
</table>

### 🧱 10-Module Clean Architecture

WaveZone is structured into isolated layers so feature modules never depend on each other directly or leak data-layer implementations:

```text
com.wavezone.app
├── :app                 # Application entry point, DI graph & root navigation
├── :domain              # Pure Kotlin business logic, use-cases & repository contracts
├── :data                # Stream extraction engines, local persistence & repo implementations
├── :core-common         # Shared utilities, dispatchers & reactive extensions
├── :core-ux             # Design system, frosted-glass modifiers, Bento grid & Material 3 theme
└── Feature Modules
    ├── :feature-home      ├── :feature-player     ├── :feature-downloads
    ├── :feature-browser   ├── :feature-library    └── :feature-settings
