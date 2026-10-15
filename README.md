<div align="center">

# 🛡️ ArmHack-Team
### Cybersecurity Assessment, Cryptographic Research & Defensive Engineering Unit

[![Official Website](https://img.shields.io/badge/Website-armhack.team-0A66C2?style=for-the-badge&logo=cloudflare&logoColor=white)](https://armhack.team)
[![Security Advisories](https://img.shields.io/badge/Public_Registry-STIRS_v2.0-critical?style=for-the-badge&logo=github&logoColor=white)](https://github.com/armhackteam/reports)
[![Research Standard](https://img.shields.io/badge/Compliance-RFC_5280_%7C_RFC_8446_%7C_OWASP_MASVS-success?style=for-the-badge)](https://github.com/armhackteam/reports/blob/main/DISCLAIMER.md)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey?style=for-the-badge)](https://github.com/armhackteam/reports/blob/main/LICENSE)

---

**Independent Cryptographic Auditing • PKI & TLS Trust Modeling • Protocol Security Analysis • AI-Driven L7 WAF Defense**

</div>

---

## 🌐 About Us / О подразделении

**🇬🇧 English:**  
**`ArmHack-Team (Cybersecurity Assessment & Defensive Engineering Unit)`** is an independent cybersecurity research collective and defensive engineering team specializing in:
- **Public Key Infrastructure (PKI) & Transport Layer Security (TLS):** Auditing Root CA hierarchies, X.509 trust boundaries, Certificate Transparency (CT) ecosystems, and transit-layer inspection risks (`RFC 5280`, `RFC 8446`, `CA/Browser Forum Baseline Requirements`).
- **Cryptographic Protocol & Privacy Architecture Analysis:** Evaluating end-to-end encrypted (E2EE) messaging protocols, post-quantum key encapsulation (`sntrup761`, `ML-KEM`), metadata leakage, and traffic correlation resistance.
- **Application Security (AppSec) & Endpoint Hardening:** Static and dynamic telemetry verification under `OWASP MASVS / MASTG` and `NIST SP 800-52 Rev. 2`.
- **Active Infrastructure Protection:** Web Application Firewall (WAF), L7 DDoS mitigation, and defensive infrastructure hardening via [armhack.team](https://armhack.team).

**🇷🇺 Русский:**  
**`ArmHack-Team (Cybersecurity Assessment & Defensive Engineering Unit)`** — исследовательское подразделение в области кибербезопасности, криптографического анализа и защитной системной инженерии. Ключевые направления:
- **Аудит инфраструктуры открытых ключей (PKI) и TLS:** Исследование корневых удостоверяющих центров (Root CA), границ доверия X.509, журналов Certificate Transparency и векторов транзитной инспекции трафика (`RFC 5280`, `RFC 8446`).
- **Криптографический анализ протоколов и архитектуры приватности:** Верификация мессенджеров со сквозным шифрованием (E2EE), постквантовых алгоритмов обмена ключами (`sntrup761`, `ML-KEM`), устойчивости к корреляции трафика и защиты метаданных.
- **Безопасность приложений (AppSec) и защита конечных узлов:** Статический и динамический анализ клиентской телеметрии по стандартам `OWASP MASVS / MASTG` и `NIST SP 800-52 Rev. 2`.
- **Защита веб-инфраструктуры:** L7 WAF, защита от DDoS-атак и проактивный мониторинг угроз на базе [armhack.team](https://armhack.team).

---

## 🗂️ Featured Security Assessments & Advisories ([`armhackteam/reports`](https://github.com/armhackteam/reports))

All technical publications follow the **STIRS v2.0 (Standardized Technical Information & Risk Specification)** framework and are available in both **English** and **Russian**:

| Advisory ID | Evaluated Subject | Category | Risk / Rating | Documentation |
| :--- | :--- | :---: | :---: | :---: |
| **[`AHT-SEC-2026-PKI-01`](https://github.com/armhackteam/reports/tree/main/reports/2026/AHT-SEC-2026-PKI-01)** | Russian National Root CA (`Russian Trusted Root CA`) & Client Trust Store Architecture (`Yandex Browser`) | `PKI` | ![CRITICAL](https://img.shields.io/badge/Risk-CRITICAL-red) | [🇬🇧 EN](https://github.com/armhackteam/reports/blob/main/reports/2026/AHT-SEC-2026-PKI-01/REPORT.md) \| [🇷🇺 RU](https://github.com/armhackteam/reports/blob/main/reports/2026/AHT-SEC-2026-PKI-01/REPORT.ru.md) |
| **[`AHT-SEC-2026-NET-02`](https://github.com/armhackteam/reports/tree/main/reports/2026/AHT-SEC-2026-NET-02)** | SimpleX Chat Protocol (`SMP` / `XFTP`) & Zero-Identifier Network Architecture (`chat.simplex.app`) | `NET` | ![LOW](https://img.shields.io/badge/Risk-LOW%20(Grade%20A%2B)-brightgreen) | [🇬🇧 EN](https://github.com/armhackteam/reports/blob/main/reports/2026/AHT-SEC-2026-NET-02/REPORT.md) \| [🇷🇺 RU](https://github.com/armhackteam/reports/blob/main/reports/2026/AHT-SEC-2026-NET-02/REPORT.ru.md) |
| **[`AHT-SEC-2026-APP-03`](https://github.com/armhackteam/reports/tree/main/reports/2026/AHT-SEC-2026-APP-03)** | Element Messenger Client (`im.vector.app` / `io.element.android.x`) & Matrix Federated Protocol (`vodozemac`) | `APP` | ![MEDIUM](https://img.shields.io/badge/Risk-MEDIUM%20(Grade%20B%2B)-yellow) | [🇬🇧 EN](https://github.com/armhackteam/reports/blob/main/reports/2026/AHT-SEC-2026-APP-03/REPORT.md) \| [🇷🇺 RU](https://github.com/armhackteam/reports/blob/main/reports/2026/AHT-SEC-2026-APP-03/REPORT.ru.md) |

👉 **[Browse the Full Advisory Registry →](https://github.com/armhackteam/reports)**

---

## 🔬 Research Methodology & Legal Framework (Safe Harbor)

Our security assessments adhere strictly to international defensive engineering standards:
1. **Artifact Pinning & Reproducibility:** Every finding is anchored to verifiable cryptographic hashes (`SHA-256`), X.509 certificate chains, and open specifications.
2. **Architectural Capability vs. Intent:** Reports evaluate mathematical trust boundaries, protocol mechanics, and systemic risk vectors rather than making subjective claims regarding vendor motives.
3. **Strict Data Sanitization:** All laboratory captures and protocol traces are scrubbed of personal identifiers (`[REDACTED]`) prior to publication.

*Read our full legal framework: [🇬🇧 Research Disclaimer](https://github.com/armhackteam/reports/blob/main/DISCLAIMER.md) | [🇷🇺 Юридический регламент](https://github.com/armhackteam/reports/blob/main/DISCLAIMER.ru.md)*

---

<div align="center">

**[🌐 armhack.team](https://armhack.team)** • **[📂 Advisory Registry](https://github.com/armhackteam/reports)**

</div>
