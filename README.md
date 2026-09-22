# ScamGuard Pro

ScamGuard Pro is a modern cybersecurity web application built with Tailwind CSS and powered by Google AI Studio (`gemini-3-flash-preview`) to detect phishing scams, fake job offers, and recruitment fraud.

## 🚀 Features
* **Real-Time Threat Analysis:** Analyzes email text and URLs instantly.
* **Dynamic Scam Threat Index:** Computes a 0–100% risk score with breakdown metrics.
* **AI-Powered Insights:** Highlights specific risk indicators and red flags.

---

## 🧪 Testing & Validation Suite
To ensure reliability and performance, ScamGuard Pro has been evaluated against the following test cases:
* **Test Case 1 (Phishing URL Detection):** Inputted lookalike domains and spoofed URLs; verified that domain anomaly flags trigger correctly.
* **Test Case 2 (Fake Offer Letter Analysis):** Tested high-pressure recruiter templates containing urgent financial demands; verified high Scam Threat Index output (>90%).
* **Test Case 3 (Edge Case & Error Handling):** Submitted empty inputs and simulated API timeouts to ensure robust fallback states and graceful user error messages.

---

## 🔒 Security & Efficiency Architecture
* **Client-Side Validation:** Sanitizes all user inputs before API transmission to prevent injection or malformed payloads.
* **Optimized Execution:** Lightweight single-file architecture (`index.html`) optimized for rapid DOM rendering and low memory overhead.
* **Error Resilience:** Implements try/catch wrappers around all asynchronous Gemini API network requests.
