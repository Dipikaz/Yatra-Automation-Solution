## Automates finding lowest round-trip flight prices on Yatra.com using Selenium in Java. ##

## Project Description ##
This Java/Selenium script opens Yatra.com, handles potential pop-ups, opens the departure date picker, and scrapes the lowest flight price available across the current and next months. It compares both and displays which month offers the cheaper option.


## Features ##
1. Launches Chrome with notification-blocking settings
2. Automatically dismisses pop-ups if present
3. Dynamically selects calendar months and scrapes lowest prices
4. Gracefully handles missing data and stale UI conditions
5. Compares the best prices and prints a summary

## Tech Stack and Dependencies ##
1. Language: Java 11+
2. Build Tool: Maven
3. Libraries:

       Selenium WebDriver & Selenium Chrome Driver 
       (Optional) WebDriverManager for auto driver handling

## Prerequisites ##

1.Java JDK 11 or higher
2.Maven 3.x
3.Chrome Browser
4.ChromeDriver in your PATH, or use WebDriverManager to auto-download

##Installation##

git clone https://github.com/Dipikaz/Yatra-Automation-Solution.git
cd yatra-automation
mvn clean compile

##Project Structure##

    src/
       └── main/
            └── java/
                └── com.yatra.automation/
                         ├── YatraAutomationScript.java    ← Main script entry
                               ├── [utility classes if refactored]
  pom.xml      



