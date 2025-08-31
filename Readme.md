# Test Automation Framework

This framework is built on **Java** and provides a structured approach to test automation.  

It incorporates **data-driven testing, detailed logging, and advanced reporting**, with seamless integration to cloud-based platforms such as **LambdaTest** for scalable execution.  

---

## 🚀 About Me  
Hi, my name is **Karan Sagale**. I have **7 years of experience** in Software Testing, specializing in **CRM and CLM applications** in the pharmaceutical domain.  

My expertise spans **Manual Testing, API Testing, and Selenium-based automation**, with a focus on building reliable and scalable test solutions.  

---

## 👤 Author

- GitHub: [@karan-sagale](https://github.com/karan-sagale)  
- Email: karan.sagale@gmail.com  

---

## 🔗 Links

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/karan-sagale)  
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karan-sagale-8b93b4151/)  

---

## 🛠 Prerequisites

Before running this framework, ensure the following software is installed on your system:

- **Java 11** – Make sure Java is installed and the `JAVA_HOME` environment variable is set.  
- **Maven** – Ensure Maven is installed and added to the system path.  
- Download Link: [https://maven.apache.org/download.cgi](https://maven.apache.org/download.cgi)  

---

## ✨ Features
- **Data-Driven Testing** – Read test data from CSV, Excel, and JSON using OpenCSV, Apache POI, and Gson.  
- **Cross-Browser Testing** – Supports running tests on multiple browsers.  
- **Headless Mode** – Faster execution by running tests in headless mode.  
- **Cloud Testing** – Integrated with **LambdaTest** for cloud execution.  
- **Logging** – Powered by **Log4j** for detailed logs.  
- **Reporting** – Generates interactive reports using **Extent Reports**.  

---

## 🧩 Tech Stack
- Java 11  
- TestNG  
- OpenCSV  
- Gson  
- Apache POI  
- Faker  
- LambdaTest  
- Log4j  
- Extent Reports  

---

## ⚙️ Setup Instructions

**Clone the Repository:**
```bash
  git clone https://github.com/karan-sagale/Test-Automation-Framework.git

  cd Test-Automation-Framework
```
    

**Running Tests on LambdaTest:**

```bash
  mvn test  -Dbrowser=chrome -DisLambdaTest=true -DisHeadless=false -X

```


**Running Tests on Chrome browser on Local Machine in Headless Mode:**

```bash
  mvn test  -Dbrowser=chrome -DisLambdaTest=false -DisHeadless=true -X

```


## 📊 Reports & Logs

**Reports** – After execution, a detailed HTML report is generated at ./report.html.
Includes summary of passed, failed, skipped test cases, along with screenshots for failures.

**Logs** – Execution logs are created during test runs and stored in the ./logs/ directory.

## ⚡ GitHub Actions Integration

This framework is integrated with GitHub Actions for CI/CD automation.

- ⏰ Tests are executed daily at 11:30 PM IST

- 📂 Reports are archived in the gh-pages branch

- 🌐 Reports are accessible online via GitHub Pages

👉 You can view the html reports at:
https://karan-sagale.github.io/Test-Automation-Framework/report.html
