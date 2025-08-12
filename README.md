# 🔐 Login Automation Testing - For Any Website

This project automates login testing for the [Soundbox](https://soundbox.dev.sb.cwdin.com/login) web application using **Java**, **Selenium WebDriver**, **TestNG**, and **Maven**.
But you can change the url and do the login automation testing for any website
---

## ✅ Features

- 🔄 Performs **15 valid login attempts** with different credentials
- ❌ Performs **15 invalid login attempts**
- 📸 Takes **screenshots** for each attempt
- 🧪 Uses **TestNG** for test organization and assertions
- 📂 Stores all screenshots in a `screenshots/` folder

---

## 📁 Project Structure
```
SoundboxLoginTest/
├── drivers/ # ChromeDriver executable
├── screenshots/ # Screenshot output directory
├── src/
│ ├── main/
│ │ └── java/
│ │ └── config/ # Configuration class (e.g., driver path)
│ ├── test/
│ │ ├── java/
│ │ │ ├── pages/ # Page Object Model for Login Page
│ │ │ └── tests/ # Test classes with logic
├── pom.xml # Maven configuration
└── README.md # You're reading it!

```
---

## 🔧 Prerequisites

Ensure the following are installed:

- [Java 17+](https://adoptium.net/) (Tested with Java 21)
- [Apache Maven](https://maven.apache.org/)
- [Google Chrome (latest)](https://www.google.com/chrome/)
- [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads) (matching your Chrome version)

> ⚠️ Place the `chromedriver.exe` inside the `drivers/` folder.

---

## 🚀 How to Run

### Step 1: Clone the Repo

```bash
git clone https://github.com/your-username/SoundboxLoginTest.git
cd SoundboxLoginTest

Object[][] validCreds = {
    {"user1@example.com", "password1"},
    {"user2@example.com", "password2"},
    ...
};

mvn clean test

| Tool         | Version            |
| ------------ | ------------------ |
| Java         | 17+ (tested on 21) |
| Maven        | 3.8+               |
| Selenium     | 4.20.0             |
| TestNG       | 7.8+               |
| Chrome       | 138+               |
| ChromeDriver | Match Chrome       |


---

```

✅ 1. Install Java Development Kit (JDK)
🔗 Download: Adoptium Java 17+

⚙️ After installation:

Set environment variable:
JAVA_HOME = C:\Program Files\Eclipse Adoptium\jdk-21 (or your install path)

Add to Path:
%JAVA_HOME%\bin


🔍 Verify:
```
bash
Copy
Edit
java -version
```
✅ 2. Install Apache Maven
🔗 Download: Maven Downloads

📂 Extract and set environment variables:
MAVEN_HOME = C:\apache-maven-3.9.x
Add to Path: %MAVEN_HOME%\bin

🔍 Verify:
```
bash
Copy
Edit
mvn -version
```
✅ 3. Install Google Chrome
🔗 Download Chrome

📌 Make sure it is updated to the latest version

✅ 4. Download Matching ChromeDriver
🔗 Check your Chrome version:
```
Go to chrome://settings/help
```
🔗 Download matching driver:
ChromeDriver Downloads

📁 Place chromedriver.exe in your project’s drivers/ folder
Or add it to the system PATH.

✅ 5. Install an IDE (Optional but Recommended)
💡 Recommended: Visual Studio Code or IntelliJ IDEA Community Edition

✅ 6. Clone the Project from GitHub
```
bash
Copy
Edit
git clone https://github.com/your-username/SoundboxLoginTest.git
cd SoundboxLoginTest
```
✅ 7. Build and Run the Project
```
Open terminal inside project folder:
bash
Copy
Edit
mvn clean test
```
✅ 8. (Optional) Install Git if you don’t have it
🔗 Git Downloads

🧪 Technologies You Now Have Installed
```
| Tool                  | Purpose                               |
| --------------------- | ------------------------------------- |
| Java JDK              | For compiling and running Java        |
| Maven                 | For managing dependencies and build   |
| Chrome                | To open and test the website          |
| ChromeDriver          | Interface between Selenium and Chrome |
| IDE (VSCode/IntelliJ) | Easier coding and debugging           |
| Git                   | Version control and GitHub access     |
```

🔎 Troubleshooting Tips
```
| Problem                  | Fix                                                  |
| ------------------------ | ---------------------------------------------------- |
| `NoSuchElementException` | Check if IDs are changing dynamically                |
| Chrome doesn't open      | Check `chromedriver.exe` version matches Chrome      |
| `mvn` not recognized     | Check your Maven PATH setup                          |
| Test not doing anything  | Add `Thread.sleep()` or check dynamic loading (AJAX) |
```

If you'd like help adding a GitHub Actions CI workflow or TestNG HTML reporting, just say the word!

---


<h1 align="center">Hi Coders <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="30px"></h1>

## Hey there 👋, I'm [<a href="https://adityakonda04.vercel.app/">Aditya!</a>](https://github.com/AdityaKonda6)

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-0e76a8?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-adi-konda/)
[![Twitter Badge](https://img.shields.io/badge/-Twitter-00acee?style=flat-square&logo=Twitter&logoColor=white)](https://twitter.com/AdityaKonda7)
[![Instagram Badge](https://img.shields.io/badge/-Instagram-e4405f?style=flat-square&logo=Instagram&logoColor=white)](https://www.instagram.com/konda_aditya/)
<img align="right" height="250" width="375" alt="" src="https://github.com/AdityaKonda6/AdityaKonda6/blob/main/giphy2.webp" />


### Glad to see you here! &nbsp; ![](https://visitor-badge.glitch.me/badge?page_id=adityakonda.adityakonda&style=flat-square&color=0088cc)

I’m a **2025 IT Graduate** passionate about **DevOps, Cloud, and Software Development** 🚀.  
My mission? To **bridge the gap between development and operations**—building scalable systems, automating workflows, and ensuring quality from code to deployment.

With a strong foundation in **Java, SQL, Linux**, and hands-on experience with **CI/CD pipelines, Selenium automation, cloud services, and Android development**, I thrive in solving problems end-to-end—from writing code to deploying it in production.

Recently, at **CWD Limited**, I worked on:
- **Automation Testing Frameworks** (Selenium, Java, Maven)
- **Linux-based system configurations & debugging**
- **Hardware-software integration testing**
- API testing with Postman  
…and in the process, strengthened my DevOps skill set.

💡 Curious mind. Fast learner. Always ready to build, break, and rebuild—better.

---

### 🚀 What I’m Working On:
- Building **DevOps projects** (Jenkins, Docker, Kubernetes, AWS, Ansible)
- Enhancing **automation frameworks** for testing & deployment
- Crafting **Android apps** and backend services
- Expanding my **Linux administration** skills

---

### 💼 My Tech Stack:
<code><img height="27" src="https://raw.githubusercontent.com/github/explore/master/topics/java/java.png" alt="Java"></code>
<code><img height="27" src="https://raw.githubusercontent.com/github/explore/master/topics/linux/linux.png" alt="Linux"></code>
<code><img height="27" src="https://raw.githubusercontent.com/github/explore/master/topics/docker/docker.png" alt="Docker"></code>
<code><img height="27" src="https://raw.githubusercontent.com/github/explore/master/topics/kubernetes/kubernetes.png" alt="Kubernetes"></code>
<code><img height="27" src="https://raw.githubusercontent.com/github/explore/master/topics/aws/aws.png" alt="AWS"></code>
<code><img height="27" src="https://raw.githubusercontent.com/github/explore/master/topics/python/python.png" alt="Python"></code>
<code><img height="27" src="https://raw.githubusercontent.com/github/explore/master/topics/javascript/javascript.png" alt="JavaScript"></code>
<code><img height="27" src="https://raw.githubusercontent.com/github/explore/master/topics/react/react.png" alt="React"></code>
<code><img height="27" src="https://raw.githubusercontent.com/github/explore/master/topics/sql/sql.png" alt="SQL"></code>
<code><img height="27" src="https://raw.githubusercontent.com/github/explore/master/topics/git/git.png" alt="Git"></code>
<code><img height="27" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png" alt="nodejs"></code>
<code><img height="27" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSTTzPAw-55ssm1Im594xYZ9eRQu2JylrkYLg&usqp=CAU" alt="mongodb"></code>
<code><img height="27" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" alt="terminal"></code>

---

<img align="right" height="250" width="375" alt="" src="https://raw.githubusercontent.com/iampavangandhi/iampavangandhi/master/gifs/coder.gif" />

### 📌 Highlights:
- 🛠 Built **dynamic Selenium automation scripts** integrated with Maven
- 🚀 Created & deployed **full-stack and Android applications**
- 🐧 Comfortable with **Linux system administration & shell scripting**
- 📦 Implemented CI/CD workflows for smoother deployments
- ☁️ Learning & applying **cloud infrastructure concepts**

--

### 📫 How to Reach Me:
- Email: **adityakonda04@gmail.com**
- Portfolio: [adityakonda04.vercel.app](https://adityakonda04.vercel.app/)
- LinkedIn: [Aditya Adi Konda](https://www.linkedin.com/in/aditya-adi-konda/)

---

### 📊 GitHub Stats:
<details>
  <summary><b>⚡ GitHub Stats</b></summary>
  <br />
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=adityakonda6&show_icons=true&hide_border=true&&count_private=true&include_all_commits=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adityakonda6&show_icons=true&hide_border=true&layout=compact&langs_count=8"/>
</details>

<details>
  <summary><b>🔥 GitHub Streaks</b></summary>
  <br />
  <img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=adityakonda6&hide_border=true" />
</details>

<details>
  <summary><b>☄️ LeetCode Stats</b></summary>
  <br />
   <p align="center"><img align="center" src="https://leetcard.jacoblin.cool/adityakonda04?theme=wtf&font=Coda%20Caption&ext=heatmap" /></p>
</details>

---

💬 Always open to collaborations, tech discussions, and exploring new opportunities in **DevOps, Cloud, and Software Development**.


Like My Work?

<a href="https://www.buymeacoffee.com/adityakonda04" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="60px" width="217px" ></a>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=AdityaKonda6&label=Profile%20views&color=0e75b6&style=flat" alt="AdityaKonda6" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=AdityaKonda6" alt="AdityaKonda6" /></a> </p>


<div align="center">

### Show some ❤️ by starring some of the repositories!
### <a href="https://adityakonda04.vercel.app/">My Portfolio</a>
</div>
