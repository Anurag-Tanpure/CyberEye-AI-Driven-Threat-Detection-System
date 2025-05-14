🛡️ CyberEye: AI-Driven Threat Detection
CyberEye is a real-time phishing detection system that analyzes both URLs and email threats using a combination of Java-based rule features and a Python machine learning model. It integrates a Chrome extension with a Spring Boot backend to provide fast and intelligent detection of malicious links.

🚀 Features
- 🔍 Real-time phishing detection on link click
- 💡 Combines Java heuristics + Python ML model
- 🧠 Confidence-based decision making
- 🌐 Chrome extension integration
- ☁️ Spring Boot backend with API endpoint

🧰 Tech Stack
- Java 17 (Spring Boot 3.x)
- Python 3.10+ (pandas, scikit-learn, joblib)
- Chrome Extension (Manifest v3)
- Maven (for dependency management)
- GitHub + Git LFS (for model storage)
🧪 How to Import & Run the Project in Eclipse (Java 17)


🔁 Step-by-step to Import in Eclipse:
1.	Open Eclipse
2.	Go to File → Import → Archive → Existing Archive Projects
3.	Browse to the cloned ZIP File name CyberEye
4.	Click Finish
5.	Wait for Maven to download dependencies (check Problems tab if any errors)
6.	Open CyberEyeApplication.java (your @SpringBootApplication class)
7.	Right-click → Run As → Java Application
✅ Backend will start on http://localhost:8080

After running project 

Steps for Install the Extension
  * Open your browser and go to chrome://extensions/
  * Enable Developer mode (top right).
  * Click Load unpacked.
  * Select the folder: CyberEye-12/extension
  * Turn on the extension.


Usage
  * Double-click any URL — the extension will check if it's a phishing link.

📁 Project Structure



![image](https://github.com/user-attachments/assets/4336623e-e1b7-4888-9c63-f9df45e1849f)

 
