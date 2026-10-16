<div align="center">

  <h1>🛡️ MailGuard AI</h1>
  <p><strong>Autonomous Zero-Trust Neural Phishing & Threat Intelligence for Google Chrome</strong></p>

  <p>
    <a href="https://hao610.github.io/mailguard-ai/"><strong>🌐 Experience Interactive Live Demo »</strong></a>
  </p>

  [![Live Showcase](https://img.shields.io/badge/Live_Showcase-Apple--Grade_Demo-0071e3?style=for-the-badge&logo=apple)](https://hao610.github.io/mailguard-ai/)
  [![Manifest V3](https://img.shields.io/badge/Chrome-Manifest_V3-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://developer.chrome.com/docs/extensions/mv3/)
  [![Zero Egress](https://img.shields.io/badge/Privacy-100%25_On--Device-30d158?style=for-the-badge)](https://hao610.github.io/mailguard-ai/)
  [![V8 Latency](https://img.shields.io/badge/V8_Inference-38_ms-ff9f0a?style=for-the-badge)](https://hao610.github.io/mailguard-ai/)

</div>

---

### 🚀 Key Technical Highlights

* **100% Client-Side V8 Inference**: Dual-expert classification engine (Multi-Layer Perceptron + One-Class SVM) executing in **under 38 milliseconds** directly within the sandboxed Chrome runtime.
* **Zero-Egress Architecture**: 0 network roundtrips for inference. Raw emails, user credentials, and OAuth tokens never touch external third-party cloud servers.
* **74-Dimensional Topological Feature Space**:
  * 🔗 **URL Spoofing & Homoglyphs**: Real-time detection of Cyrillic/Latin homographs, `href` anchor destination mismatches, and open redirect traps.
  * ⏰ **Odd-Hour Circadian Anomalies**: Statistical deviation analysis between MIME `Date` headers and sender organizational time zones.
  * 🚨 **Artificial Urgency Exploits**: Localized NLP scoring of cognitive coercion and psychological pressure triggers.
  * 🌐 **Multi-Hop Routing Graph Forensics**: Graph-theoretical inspection of RFC 5322 `Received:` headers to unmask forged MTA relays.
  * 👁️‍🗨️ **Zero-Width Unicode Steganography**: Detection of invisible space injection (`U+200B`) crafted to evade traditional NLP regex filters.
  * 📎 **Double-Extension Traps**: Attachment structure analysis for dual-extension masquerading (e.g. `.pdf.vbs`).
* **$O(74)$ First-Order SHAP**: Computes live diagnostic attribution bars in milliseconds, replacing astronomical $2^{74}$ combinatorial complexity.

---

### 📊 Benchmark Metrics

| Metric | Measured Specification | Real-World Impact |
| :--- | :---: | :--- |
| **Spam Class F1-Score** | **> 95%** | Robust adversarial detection across benchmark test corpora |
| **Cross-Validation Stability** | **Consistent (~0.95)** | Multi-fold validation confirming generalization stability |
| **False Positive Rate (FPR)** | **< 0.1%** | Virtually zero disruption to genuine corporate communication |
| **V8 Inference Latency** | **38 ms** | Real-time viewport evaluation with 60 FPS UI responsiveness |
| **Tensor Payload Size** | **162 KB** | Ultra-lean JSON weight matrix bundled inside the client |
| **Inbox Viewport Scan (50 items)** | **3 – 5 sec** | Staggered asynchronous dispatch preventing Google 429 quota exhaustion |

---

### 🔒 Note on Source Code & Dataset

> **University Final Year Project (FYP):**  
> This repository provides the technical architecture overview and live interactive demonstration for my university Final Year Project (FYP) at **Universiti Tunku Abdul Rahman (UTAR)**.  
> In accordance with academic project guidelines, the raw training datasets, model weights, and backend scripts are retained in a private repository.

---

### 📚 Academic Citation

If you reference this project, please cite:

```bibtex
@misc{Loi_MailGuard_AI_2026,
  author       = {Loi, Chiang Hao},
  title        = {{MailGuard AI: Autonomous On-Device Phishing and Threat Intelligence Framework}},
  year         = {2026},
  howpublished = {Final Year Project (FYP), Department of Computer and Communication Technology, Faculty of Information and Communication Technology (FICT), Universiti Tunku Abdul Rahman (UTAR)},
  url          = {https://github.com/Hao610/mailguard-ai},
  note         = {Area of Study: Cybersecurity, On-Device Artificial Intelligence}
}
```

---

### 👨‍💻 Author

**Loi Chiang Hao**  
*Faculty of Information and Communication Technology (FICT), Universiti Tunku Abdul Rahman (UTAR)*  
🌐 **Portfolio**: [loichianghao.vercel.app](https://loichianghao.vercel.app/)  
💼 **LinkedIn**: [linkedin.com/in/loi-chiang-hao](https://www.linkedin.com/in/loi-chiang-hao/)  
🐙 **GitHub**: [@Hao610](https://github.com/Hao610)
