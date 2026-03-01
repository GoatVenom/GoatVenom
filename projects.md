[Home](https://goatvenom.github.io/GoatVenom/) | [Projects](https://goatvenom.github.io/GoatVenom/projects)

---

## 📂 Projects

---

### 🕵️ Dark Web Intelligence Platform

> A production-grade real-time intelligence platform for cryptocurrency threat detection, criminal network analysis, and automated security reporting.

🔗 [View Repository](https://github.com/GoatVenom/Dark-Web-Intelligence-Platform) | [📄 Linked Documentation](https://github.com/GoatVenom/Dark-Web-Intelligence-Platform#readme)

**💻 Technologies Used**

`Python` `Random Forest` `scikit-learn` `Flask` `pandas` `Discord Webhooks`

**🎯 What It Does**
- Real-time cryptocurrency threat detection (20+ transactions/second, <100ms latency)
- ML classification with Random Forest (85%+ accuracy)
- Criminal network analysis and IOC enrichment
- Live intelligence dashboards with automated alerting
- Automated intelligence reporting (5 report types)

**🧠 Skills Obtained**
- Real-time threat detection pipeline engineering
- ML classification and explainable AI (probability scoring)
- Criminal network and cryptocurrency transaction analysis
- Intelligence dashboard design and automated reporting

**📖 Lessons Learned**
> Building a real-time threat detection platform reinforced that intelligence systems must balance speed, accuracy, and explainability. Operationalizing ML for cryptocurrency crime analysis required aligning model outputs to investigator workflows — not just optimizing for performance metrics.

---

### 🍯 ShadowSentinel

> A high-interaction Windows honeypot tool designed to deceive, trap, and monitor attackers using decoy files, fake admin consoles, and real-time Discord alerts.

🔗 [View Repository](https://github.com/GoatVenom/ShadowSentinel) | [📄 Linked Documentation](https://github.com/GoatVenom/ShadowSentinel#readme)

**💻 Technologies Used**

`C++` `Win32 API` `CURL` `Discord Webhooks` `Windows 10/11`

**🎯 What It Does**
- Simulates a fake admin console to engage and deceive attackers
- Generates convincing decoy files (credentials, bank info, system configs)
- Logs all file access attempts with timestamps and user context
- Sends real-time alerts to Discord with suspicion level and event details
- Locks files after access to simulate ransomware behavior and trap attackers

**🧠 Skills Obtained**
- Honeypot architecture and deception technology design
- File system monitoring and attacker behavior logging
- Real-time alerting and incident triage
- Adversarial thinking and attacker engagement techniques

**📖 Lessons Learned**
> Designing a honeypot system taught me to think like an attacker — understanding what looks convincing, what triggers interaction, and how to capture meaningful forensic evidence without tipping off the adversary. Real-time alerting and deception engineering are as much about psychology as they are about technology.

---

### 🖥️ Native5

> Custom Windows tools built from scratch to emulate native cd and dir command behavior using low-level Win32 API calls.

🔗 [View Repository](https://github.com/GoatVenom/Native5) | [📄 Linked Documentation](https://github.com/GoatVenom/Native5#readme)

**💻 Technologies Used**

`C++` `Win32 API` `Microsoft Visual Studio` `Windows`

**🎯 What It Does**
- NativeFive.exe emulates cd, supporting multi-level directory traversal (up and down)
- NativeFive.2.exe emulates dir, supporting /A, /S, /Q switches
- Uses Win32 APIs: SetCurrentDirectoryW, FindFirstFileW, GetFileAttributesW, LookupAccountSidW
- Retrieves file ownership, attributes, size, and timestamps natively

**🧠 Skills Obtained**
- Low-level Windows systems programming
- Win32 API integration (file system, security, directory traversal)
- Binary compilation and executable engineering
- Understanding of OS process and shell session behavior

**📖 Lessons Learned**
> Re-implementing native OS commands at the API level exposed the gap between what the shell presents and what the OS actually does. This project deepened my understanding of Windows internals, process isolation, and the importance of low-level systems knowledge for forensic and security work.

---

### 📊 Data-Driven Security Insights

> A machine learning project analyzing and predicting the nature and impact of cybersecurity breaches.

🔗 [View Repository](https://github.com/GoatVenom/Data-Driven-Security-Insights) | [📄 Linked Documentation](https://github.com/GoatVenom/Data-Driven-Security-Insights#readme)

**💻 Technologies Used**

`Python` `pandas` `scikit-learn` `matplotlib` `seaborn` `Jupyter`

**🎯 What It Does**
- Classifies breach methods (Hacking, Phishing, Lost Device)
- Predicts breach impact using regression models (records affected)
- Visualizes breach trends, frequency, and impact types over time

**🧠 Skills Obtained**
- Machine learning model development (classification & regression)
- Security data analysis and breach pattern recognition
- Data visualization and insight communication
- Translating technical outputs into strategic security recommendations

**📖 Lessons Learned**

**Strategic Value of Data in Security Decision-Making**
> Predictive models are only as valuable as the decisions they inform. Transforming raw breach data into actionable, prioritized recommendations requires understanding how security leaders operationalize insights — aligning outputs to risk prioritization, resource allocation, and strategic planning.

**Balancing Model Precision and Operational Relevance**
> Accuracy metrics alone don't define success. Model performance must be evaluated within the context of noise, evolving threat patterns, and operational constraints — balancing predictive performance with maintainability, interpretability, and continuous validation.