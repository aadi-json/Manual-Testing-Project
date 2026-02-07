# Scam Buster – Application & Browser Extension Testing

## 📌 Project Overview
**Scam Buster** is a cybersecurity browser extension with an accompanying application designed to protect users from phishing attacks, scam websites, and malicious online content. The tool performs real-time threat analysis and assigns risk scores to websites based on multiple security parameters.

This repository documents the **manual testing activities** carried out to validate the functionality, accuracy, usability, and reliability of the Scam Buster application and browser extension.

---

## 🎯 Objective
The primary objective of this project was to:
- Validate core security functionalities
- Verify accuracy of threat detection and risk scoring
- Identify functional, security, and usability defects
- Ensure reliable user experience across browsers and platforms

---

## 🧑‍💻 Role & Responsibilities
**Role:** Test Engineer  
**Responsibilities:**
- Designed and executed manual test cases
- Performed functional, usability, exploratory, and regression testing
- Validated authentication and account management workflows
- Identified and documented critical security defects
- Conducted cross-browser and cross-platform testing
- Provided recommendations for security and UX improvements

---

## ⏱ Project Duration
**Duration:** 1 Month (4 Weeks)

---

## 🛠 Application Workflow
1. User installs the Scam Buster browser extension
2. User receives **5 free threat scans** without account creation
3. After free scans are exhausted, account creation is required
4. Registered users receive unlimited access
5. Extension actively scans websites and alerts users of risks

---

## 🔑 Key Features Tested
- Real-time website threat assessment
- Risk score calculation (0–100 scale)
- Phishing and scam detection
- Free trial usage limitation
- User account creation and authentication
- Browser extension behavior and alerts

---

## 🧪 Testing Approach & Methodology

### Test Strategy
- Functional Testing  
- Usability Testing  
- Exploratory Testing  
- Regression Testing  
- Cross-Browser Testing  

---

### Testing Phases

#### Phase 1: Free Trial Testing (Week 1–2)
- Verified 5-scan limitation
- Tested threat detection on legitimate and malicious sites
- Validated scoring consistency
- Evaluated trial user experience

#### Phase 2: Account Management Testing (Week 3–4)
- Tested registration using Gmail, Outlook, and Yahoo
- Verified authentication and session handling
- Validated trial-to-registered-user transition

#### Phase 3: Core Functionality Testing (Week 5–6)
- Tested multiple website categories (banking, e-commerce, social media)
- Verified detection accuracy across threat levels
- Tested edge cases and boundary conditions
- Performance testing under varying network conditions

#### Phase 4: Regression & Integration Testing (Week 7–8)
- Regression testing after defect fixes
- Browser compatibility testing (Chrome, Firefox, Edge)
- Cross-platform testing
- User acceptance scenarios

---

## 🖥 Test Environment

### Browsers
- Google Chrome (v120+)
- Mozilla Firefox (v118+)
- Microsoft Edge (v119+)

### Operating Systems
- Windows 10 / 11
- macOS Ventura
- Ubuntu 22.04

### Network Conditions
- High-speed broadband
- 4G mobile network
- Throttled network

### Test Data
- 50+ legitimate websites
- 30+ known phishing and scam websites (public databases)

---

## 🐞 Defects Identified

### Defect 1: Connectivity Error on Legitimate Websites
- **Severity:** High  
- **Priority:** P1  
- **Issue:** Legitimate websites displayed “Site could not be accessible”  
- **Impact:** Loss of user trust and reliability concerns  

---

### Defect 2: High Safety Score for Malicious Websites
- **Severity:** Critical  
- **Priority:** P2  
- **Issue:** Phishing sites received scores between 85–93 (marked safe)  
- **Impact:** Major security risk and potential user harm  
- **Recommendation:** Immediate algorithm review and threat intelligence update  

---

### Defect 3: Zero Score for Legitimate Websites
- **Severity:** Minor  
- **Priority:** P1  
- **Issue:** Trusted websites displayed score 0 without context  
- **Impact:** User confusion and unclear scoring logic  
- **Recommendation:** Improve UI indicators and scoring explanation  

---

### Defect 4: Gmail Account Creation Failure
- **Severity:** Major  
- **Priority:** P0  
- **Issue:** Google OAuth authentication succeeds, but account creation fails  
- **Impact:** Users blocked after free trial expiration  

---

## 📈 Key Learnings
- Importance of accurate threat intelligence in security tools
- Critical role of UX clarity in security scoring systems
- OAuth integration failures can severely impact user retention
- Security testing requires continuous validation and regression

---

## 📎 Conclusion
This project highlights real-world challenges in testing cybersecurity applications, especially those involving real-time threat detection and user trust. The defects identified emphasize the need for robust security algorithms, reliable backend integrations, and clear user communication.

---

## 🏷 Keywords
`Manual Testing` `Cyber Security Testing` `Browser Extension Testing`  
`Phishing Detection` `Functional Testing` `Regression Testing`
