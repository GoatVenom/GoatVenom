[Home](https://goatvenom.github.io/GoatVenom/) | [Projects](https://goatvenom.github.io/GoatVenom/projects)

---

## Projects

<style>
.project-card {
  border: 1px solid #30363d;
  border-radius: 10px;
  padding: 24px 28px;
  margin-bottom: 32px;
  background-color: #0d1117;
  color: #c9d1d9;
}
.project-card h3 {
  margin-top: 0;
  font-size: 1.4em;
  color: #58a6ff;
}
.project-card .category-badge {
  display: inline-block;
  background-color: #1f3a5c;
  color: #58a6ff;
  font-size: 0.75em;
  font-weight: 600;
  padding: 3px 10px;
  border-radius: 20px;
  margin-bottom: 12px;
  letter-spacing: 0.05em;
  text-transform: uppercase;
}
.project-card .description {
  color: #8b949e;
  font-style: italic;
  margin-bottom: 16px;
  border-left: 3px solid #30363d;
  padding-left: 12px;
}
.project-card .badges { margin-bottom: 16px; }
.project-card .badges img { margin: 2px 3px 2px 0; }
.project-card .section-title {
  font-weight: 700;
  color: #e6edf3;
  margin-top: 16px;
  margin-bottom: 6px;
  font-size: 0.95em;
  text-transform: uppercase;
  letter-spacing: 0.04em;
}
.project-card ul { margin: 0 0 8px 0; padding-left: 20px; color: #c9d1d9; }
.project-card ul li { margin-bottom: 4px; font-size: 0.95em; }
.project-card .links { margin-top: 18px; display: flex; gap: 12px; flex-wrap: wrap; }
.project-card .links a {
  display: inline-block;
  padding: 6px 16px;
  border-radius: 6px;
  font-size: 0.85em;
  font-weight: 600;
  text-decoration: none;
  border: 1px solid #30363d;
  color: #c9d1d9;
  background-color: #161b22;
}
.project-card .links a:hover { background-color: #1f6feb; border-color: #1f6feb; color: #ffffff; }
.project-card table { width: 100%; border-collapse: collapse; font-size: 0.88em; margin-top: 8px; }
.project-card table th { background-color: #161b22; color: #8b949e; text-align: left; padding: 6px 10px; border: 1px solid #30363d; font-size: 0.8em; text-transform: uppercase; }
.project-card table td { padding: 6px 10px; border: 1px solid #30363d; color: #c9d1d9; }
.project-card table tr:nth-child(even) td { background-color: #0d1117; }
.project-card table tr:nth-child(odd) td { background-color: #161b22; }
.project-card .report-table a { color: #58a6ff; text-decoration: none; }
.project-card .report-table a:hover { text-decoration: underline; }
.project-card blockquote { border-left: 3px solid #30363d; padding-left: 12px; color: #8b949e; font-size: 0.9em; margin: 8px 0; }
</style>

<!-- ========== DARK WEB INTELLIGENCE PLATFORM ========== -->
<div class="project-card">
  <div class="category-badge">🕵️ Cyber Threat Intelligence Platform</div>
  <h3>Dark Web Intelligence Platform</h3>
  <div class="description">A production-grade real-time intelligence platform for cryptocurrency threat detection, criminal network analysis, and automated security reporting.</div>

  <div class="badges">
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
    <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
    <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
    <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
    <img src="https://img.shields.io/badge/Random%20Forest-4CAF50?style=flat-square&logoColor=white"/>
    <img src="https://img.shields.io/badge/Discord%20Webhooks-5865F2?style=flat-square&logo=discord&logoColor=white"/>
  </div>

  <div class="section-title">What It Does</div>
  <ul>
    <li>Real-time cryptocurrency threat detection (20+ transactions/second, &lt;100ms latency)</li>
    <li>ML classification with Random Forest (85%+ accuracy)</li>
    <li>Criminal network analysis and IOC enrichment</li>
    <li>Live intelligence dashboards with automated alerting</li>
    <li>Automated intelligence reporting (5 report types)</li>
  </ul>

  <div class="section-title">Skills Obtained</div>
  <ul>
    <li>Real-time threat detection pipeline engineering</li>
    <li>ML classification and explainable AI (probability scoring)</li>
    <li>Criminal network and cryptocurrency transaction analysis</li>
    <li>Intelligence dashboard design and automated reporting</li>
  </ul>

  <div class="section-title">Lessons Learned</div>
  <blockquote><strong>Building and Leading Intelligence Programs</strong><br>Effective threat intelligence programs require defined collection requirements and structured analytic workflows that connect analysts to decision-makers — not just technical capability.</blockquote>
  <blockquote><strong>Operationalizing Intelligence at Scale</strong><br>Designing a real-time pipeline reinforced that CTI infrastructure must sustain continuous collection and analysis to support ongoing threat monitoring, not just one-time assessments.</blockquote>
  <blockquote><strong>Communicating Intelligence to Non-Technical Stakeholders</strong><br>Producing both executive summaries and technical reports highlighted that CTI managers must translate threat actor TTPs and risk findings into clear narratives that drive organizational action.</blockquote>
  <blockquote><strong>Integrating Machine Learning into Threat Analysis Workflows</strong><br>Applying ML classification to criminal network data demonstrated that effective CTI management means knowing when models augment analyst judgment — and when human expertise must take precedence.</blockquote>

  <div class="section-title">🚨 Live Intelligence Alert Feed Sample</div>
  <blockquote>The platform processes 20+ transactions per second in real time, classifying each by threat probability and severity. Below is a sample of actual alerts generated by the system.</blockquote>
  <table>
    <tr><th>Time (UTC)</th><th>Transaction ID</th><th>Severity</th><th>Threat Prob</th><th>Amount (USD)</th><th>Blockchain</th><th>Type</th></tr>
    <tr><td>2026-02-24 03:07:56</td><td>TXN-325462</td><td>🔴 CRITICAL</td><td>98.8%</td><td>$564,546.88</td><td>bitcoin</td><td>exchange</td></tr>
    <tr><td>2026-02-24 03:07:57</td><td>TXN-978652</td><td>🔴 CRITICAL</td><td>100.0%</td><td>$53,109.25</td><td>bitcoin</td><td>withdrawal</td></tr>
    <tr><td>2026-02-24 02:56:51</td><td>TXN-681920</td><td>🟠 HIGH</td><td>59.0%</td><td>$51,947.42</td><td>litecoin</td><td>transfer</td></tr>
    <tr><td>2026-02-24 02:57:04</td><td>TXN-623808</td><td>🟠 HIGH</td><td>50.0%</td><td>$47,502.44</td><td>ethereum</td><td>exchange</td></tr>
  </table>
  <blockquote>⚡ Alerts generated at sub-100ms latency · <a href="https://github.com/GoatVenom/Dark-Web-Intelligence-Platform/blob/master/output/alerts/real_time_alerts.jsonl">View Full Alert Log</a></blockquote>

  <div class="section-title">📄 Generated Intelligence Reports</div>
  <blockquote>The platform automatically produces 5 structured report types covering threat actors, transactions, network nodes, and marketplace activity.</blockquote>
  <table class="report-table">
    <tr><th>Report</th><th>Description</th></tr>
    <tr><td><a href="https://github.com/GoatVenom/Dark-Web-Intelligence-Platform/blob/master/output/reports/intelligence_report.txt">📋 Comprehensive Threat Assessment</a></td><td>Full executive + technical report: 1,000 transactions, 100 threat actors, 5 marketplaces analyzed</td></tr>
    <tr><td><a href="https://github.com/GoatVenom/Dark-Web-Intelligence-Platform/blob/master/output/reports/high_risk_transactions.csv">💸 High-Risk Transactions</a></td><td>155 flagged transactions totalling 91.55 BTC across Bitcoin, Monero, and Ethereum</td></tr>
    <tr><td><a href="https://github.com/GoatVenom/Dark-Web-Intelligence-Platform/blob/master/output/reports/critical_threat_actors.csv">🎯 Critical Threat Actors</a></td><td>13 critical-level actors including ransomware groups and hacker collectives</td></tr>
    <tr><td><a href="https://github.com/GoatVenom/Dark-Web-Intelligence-Platform/blob/master/output/reports/high_risk_network_nodes.csv">🕸️ High-Risk Network Nodes</a></td><td>Flagged mixing services, exchanges, and wallets with elevated risk scores</td></tr>
    <tr><td><a href="https://github.com/GoatVenom/Dark-Web-Intelligence-Platform/blob/master/output/reports/high_risk_marketplace_listings.csv">🛒 High-Risk Marketplace Listings</a></td><td>Active dark web listings for weapons, hacking tools, forged documents, and stolen data</td></tr>
  </table>

  <div class="links">
    <a href="https://github.com/GoatVenom/Dark-Web-Intelligence-Platform">📁 View Repository</a>
    <a href="https://github.com/GoatVenom/Dark-Web-Intelligence-Platform#readme">📖 Documentation</a>
  </div>
</div>

<!-- ========== SHADOWSENTINEL ========== -->
<div class="project-card">
  <div class="category-badge">⚔️ Red Team / Offensive Security</div>
  <h3>ShadowSentinel</h3>
  <div class="description">A high-interaction Windows offensive deception tool designed to deceive, trap, and monitor attackers using decoy files, fake admin consoles, and real-time Discord alerts.</div>

  <div class="badges">
    <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
    <img src="https://img.shields.io/badge/Win32%20API-0078D6?style=flat-square&logo=windows&logoColor=white"/>
    <img src="https://img.shields.io/badge/CURL-073551?style=flat-square&logo=curl&logoColor=white"/>
    <img src="https://img.shields.io/badge/Discord%20Webhooks-5865F2?style=flat-square&logo=discord&logoColor=white"/>
    <img src="https://img.shields.io/badge/Windows%2010%2F11-0078D6?style=flat-square&logo=windows&logoColor=white"/>
  </div>

  <div class="section-title">What It Does</div>
  <ul>
    <li>Simulates a fake admin console to engage and deceive attackers</li>
    <li>Generates convincing decoy files (credentials, bank info, system configs)</li>
    <li>Logs all file access attempts with timestamps and user context</li>
    <li>Sends real-time alerts to Discord with suspicion level and event details</li>
    <li>Locks files after access to simulate ransomware behavior and trap attackers</li>
  </ul>

  <div class="section-title">Skills Obtained</div>
  <ul>
    <li>Offensive deception technology design and lure deployment</li>
    <li>File system monitoring and attacker behavior logging</li>
    <li>Real-time alerting and incident triage</li>
    <li>Adversarial thinking and attacker engagement techniques</li>
  </ul>

  <div class="section-title">Lessons Learned</div>
  <blockquote>Designing a deception tool taught me to think like an attacker — understanding what looks convincing, what triggers interaction, and how to capture meaningful forensic evidence without tipping off the adversary. Real-time alerting and deception engineering are as much about psychology as they are about technology.</blockquote>

  <div class="links">
    <a href="https://github.com/GoatVenom/ShadowSentinel">📁 View Repository</a>
    <a href="https://github.com/GoatVenom/ShadowSentinel#readme">📖 Documentation</a>
  </div>
</div>

<!-- ========== NATIVE5 ========== -->
<div class="project-card">
  <div class="category-badge">🔍 Offensive Reconnaissance</div>
  <h3>Native5</h3>
  <div class="description">Custom Windows offensive reconnaissance tools built from scratch to perform host enumeration and file system reconnaissance using low-level Win32 API calls — bypassing standard shell detection.</div>

  <div class="badges">
    <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
    <img src="https://img.shields.io/badge/Win32%20API-0078D6?style=flat-square&logo=windows&logoColor=white"/>
    <img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=flat-square&logo=visual-studio&logoColor=white"/>
    <img src="https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white"/>
  </div>

  <div class="section-title">What It Does</div>
  <ul>
    <li>NativeFive.exe emulates <code>cd</code>, supporting multi-level directory traversal (up and down)</li>
    <li>NativeFive.2.exe emulates <code>dir</code>, supporting /A, /S, /Q switches</li>
    <li>Uses Win32 APIs: SetCurrentDirectoryW, FindFirstFileW, GetFileAttributesW, LookupAccountSidW</li>
    <li>Retrieves file ownership, attributes, size, and timestamps natively</li>
    <li>Operates at the API level — avoids shell-level logging and EDR detection</li>
  </ul>

  <div class="section-title">Skills Obtained</div>
  <ul>
    <li>Low-level Windows systems programming and host enumeration</li>
    <li>Win32 API integration (file system, security, directory traversal)</li>
    <li>AV/EDR evasion through raw API calls</li>
    <li>Binary compilation and executable engineering</li>
    <li>Post-exploitation situational awareness tooling</li>
  </ul>

  <div class="section-title">Lessons Learned</div>
  <blockquote>Re-implementing native OS commands at the API level exposed the gap between what the shell presents and what the OS actually does. This project deepened my understanding of Windows internals, process isolation, and the importance of low-level systems knowledge for offensive operations and forensic work.</blockquote>

  <div class="links">
    <a href="https://github.com/GoatVenom/Native5">📁 View Repository</a>
    <a href="https://github.com/GoatVenom/Native5#readme">📖 Documentation</a>
  </div>
</div>

<!-- ========== DATA-DRIVEN SECURITY INSIGHTS ========== -->
<div class="project-card">
  <div class="category-badge">📊 Security Research & Analytics</div>
  <h3>Data-Driven Security Insights</h3>
  <div class="description">A machine learning research project analyzing and predicting the nature and impact of cybersecurity breaches — translating raw breach data into actionable, prioritized security recommendations.</div>

  <div class="badges">
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
    <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
    <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
    <img src="https://img.shields.io/badge/matplotlib-11557C?style=flat-square&logo=python&logoColor=white"/>
    <img src="https://img.shields.io/badge/seaborn-4C72B0?style=flat-square&logoColor=white"/>
    <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
  </div>

  <div class="section-title">What It Does</div>
  <ul>
    <li>Classifies breach methods (Hacking, Phishing, Lost Device)</li>
    <li>Predicts breach impact using regression models (records affected)</li>
    <li>Visualizes breach trends, frequency, and impact types over time</li>
  </ul>

  <div class="section-title">Skills Obtained</div>
  <ul>
    <li>Machine learning model development (classification &amp; regression)</li>
    <li>Security data analysis and breach pattern recognition</li>
    <li>Data visualization and insight communication</li>
    <li>Translating technical outputs into strategic security recommendations</li>
  </ul>

  <div class="section-title">Lessons Learned</div>
  <blockquote><strong>Strategic Value of Data in Security Decision-Making</strong><br>Predictive models are only as valuable as the decisions they inform. Transforming raw breach data into actionable, prioritized recommendations requires understanding how security leaders operationalize insights — aligning outputs to risk prioritization, resource allocation, and strategic planning.</blockquote>
  <blockquote><strong>Balancing Model Precision and Operational Relevance</strong><br>Accuracy metrics alone don't define success. Model performance must be evaluated within the context of noise, evolving threat patterns, and operational constraints — balancing predictive performance with maintainability, interpretability, and continuous validation.</blockquote>

  <div class="links">
    <a href="https://github.com/GoatVenom/Data-Driven-Security-Insights">📁 View Repository</a>
    <a href="https://github.com/GoatVenom/Data-Driven-Security-Insights#readme">📖 Documentation</a>
  </div>
</div>
