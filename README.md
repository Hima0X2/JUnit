# JUnit

### ✅ Description:
This project includes two separate automation tasks using **JUnit and Selenium**:

## 🚀 Task #1: Automate Webform Registration

### 🔗 URL: [Guest Registration Form](https://demo.wpeverest.com/user-registration/guest-registration-form/)

### ✅ Steps Automated:
1. Input fields:
   - Firstname
   - Lastname
   - Email
   - Gender
   - Date of Birth
   - Nationality
   - Phone
   - Country (Bangladesh)
   - Agree to Terms & Conditions  
2. Click on the **Submit** button  
3. Assert that registration was successful (check confirmation message)

### 📸 Screenshot of Report:
![image](https://github.com/user-attachments/assets/0e7aa96d-5b34-486b-a727-b3e7767fc843)

### 🎥 Demo Video:

https://github.com/user-attachments/assets/61c3b05e-0124-4cf2-baff-0d9387595751

---

## 📊 Task #2: Scrap Table Data from DSE

### 🔗 URL: [DSE Share Price Table](https://dsebd.org/latest_share_price_scroll_by_value.php)

### ✅ Steps Automated:
1. Scrape all cell values from the share price table  
2. Print all the values in console  
3. Store the full table data into a `.txt` file  

### 📁 Output Files:
- `data.txt` – All cell values

### 📸 Screenshot of Report:
![image](https://github.com/user-attachments/assets/a691ab3c-65d4-44d4-9027-52057dae4b39)

### 🎥 Demo Video:
https://github.com/user-attachments/assets/dcf982c8-f36f-40bd-8e95-b23492961775


## 🔧 Tools Used:  
- Java  
- JUnit 5  
- Selenium WebDriver  
- ChromeDriver  
- Gradle   

## 📂 Folder Structure
```
├── src/
│   └── test/
│       ├── java/
│       │   ├── dseTableScrap.java
│       │   └── wpeverestRegistration.java
│       ├── resources/
│       │   └── data.txt
├── README.md
└── .gitignore
```

## ✅ How to Run

1. Clone the repo:
```
git clone https://github.com/yourusername/junit-automation-assignment.git
cd junit-automation-assignment
```
### 2. Open in IntelliJ IDEA
Open the project in IntelliJ IDEA

Ensure it’s recognized as a Gradle project

### 3. Install Dependencies
Add the following to your build.gradle file:
```
dependencies {
    implementation 'org.seleniumhq.selenium:selenium-java:4.34.0'
    testImplementation 'org.junit.jupiter:junit-jupiter:5.10.0'
}
```
### 4. Run the Script Task 1
```
src/test/java/wpeverestRegistration.java
```

### 4. Run the Script Task 2
```
src/test/java/dseTableScrap.java
```
Right-click the file and select Run.
A browser window will open, scrape the table, and store data in data.txt.

### 5. Watch the Automation Task 1

- A Chrome browser window will open and fill in the WP Everest Guest Registration form.
- **screenshot** and a **video** gave in ths README.md file.

## 👨‍💻 Author: Sanjida Samanta    

