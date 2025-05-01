# FinalYearProject
Static &amp; Dynamic Analysis of Wuta Camera App

## Project Overview
This project performs a **comprehensive static and dynamic security analysis** of the Wuta Camera Android application, aiming to detect vulnerabilities and map them to the **OWASP Mobile Top 10**.

The project involved:
- **Static Analysis:**  
  - Tools: MobSF, JADX  

- **Dynamic Analysis:**  
  - Tool: Burp Suite Community, MobSF  

- **Manual Review:**  
  - Decompiling APK source to validate automatic findings.
  - Mapping vulnerabilities against industry standards (OWASP MASVS, MASTG, Mobile Top 10).

---

## Tools and Techniques Used
- **MobSF:** Automated static &amp; Dynamic analysis for Android APKs.
- **JADX:** Reverse-engineering tool to manually inspect decompiled Java code.
- **Burp Suite:** Intercepted real device traffic for dynamic testing.
- **Android Emulator & Real Device (Galaxy J5):** Testing platforms for analysis.
