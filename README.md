# 🛒 Gadgets Automation  
**Automated Gadget Search and Filtering on Snapdeal**

This project automates the Snapdeal gadgets webpage using **Selenium WebDriver**. It searches for a specified gadget, applies filters (sort by popularity and price range), and extracts the top five product names and prices. The framework is powered by **TestNG**, supports **parallel execution**, and uses **Apache POI** for Excel-based data handling.

---

## 🚀 Key Features

- 🔍 Automated gadget search on [Snapdeal](https://www.snapdeal.com)
- 🔼 Sorts results by **Popularity**
- 💰 Applies price filter (From & To range)
- 📦 Extracts **Top 5 Products** (Name + Price)
- 🧪 Test execution managed by **TestNG**
- 📊 Data read/write handled via **Apache POI**
- 🔀 Supports **Parallel Testing** using TestNG

---

## 🛠️ Tech Stack

- Java
- Selenium WebDriver
- TestNG
- Apache POI
- Maven (build tool)

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/gadgets-automation.git
cd gadgets-automation
````

### 2. Build the Project

```bash
mvn clean install
```

### 3. Run TestNG Suite

You can run the suite from command line:

```bash
mvn test
```

Or from your IDE using `testng.xml`.

---

## 📂 Project Structure

```
gadgets-automation/
│
├── src/
│   ├── main/java/
│   │   └── core classes (page objects, utilities)
│   └── test/java/
│       └── automation test scripts
│
├── testng.xml
├── pom.xml
├── ExcelData/
│   └── output.xlsx (extracted data)
├── README.md
```

---

## 📄 Output

* ✅ Top 5 products’ **name** and **price** are extracted and optionally saved in Excel
* 📁 Output location: `ExcelData/output.xlsx`

---

## 🧪 Parallel Testing

Parallel browser sessions are configured in `testng.xml`. You can scale execution across multiple threads for faster results.

---

## 📘 Prerequisites

* Java JDK 8+
* Maven
* Internet connection (Snapdeal live page)
* ChromeDriver (or compatible WebDriver)

---

## 🤝 Contributing

Feel free to fork the repo and submit a pull request. Feedback and improvements are always welcome!

---

## 🙋‍♀️ Author

* **Dhevadharshini A**
  *Automation | QA | Selenium Enthusiast*

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).


