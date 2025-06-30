# Selenium Tests for IT Karijera Website

This project contains automated Selenium test cases for the **IT Karijera** website (`https://itkarijera.ba`). The tests are implemented in Java using JUnit 5 and Selenium WebDriver, focused on validating various functionalities and responsiveness of the site.

---

## Project Overview

The tests cover:

- Login form validation with invalid and blank inputs  
- Checkbox selection functionality for location filters  
- HTTP to HTTPS redirection and secure cookie checks  
- Mobile and tablet responsiveness for different device resolutions  
- Search functionality with valid and special character inputs  
- Navigation bar, footer links, sidebar filters, and other UI components  
- Homepage loading performance tests  

---

## Test Classes Included

- `LoginFormTest.java` — Tests login form validation errors  
- `Regular3Test.java` — Tests location checkbox selections (Sarajevo, Banja Luka, Tuzla)  
- `HTTPTest.java` — Tests HTTP redirection to HTTPS and secure cookies  
- `MobileResponsivenessTest.java` — Tests page responsiveness on iPhone, iPad, and Android devices  
- `SearchFunctionalityTest.java` — Tests search bar behavior with valid and invalid inputs  
- Additional tests like `DevOpsSuccessStoryTest`, `FooterLinksTest`, `HomepageLoadingTimeTest`, `NavigationBarTest`, and others focusing on various UI and functional validations

---

## Setup & Running Tests

1. **Prerequisites**:
   - Java 17+ installed  
   - Maven or Gradle build tool (if you want to manage dependencies)  
   - Chrome browser installed  
   - ChromeDriver executable downloaded and the path updated in the test classes (currently set to `C:\Users\PC\Desktop\chromedriver-win64\chromedriver.exe`)

2. **Running Tests**:
   - Open the project in your favorite IDE (IntelliJ IDEA, Eclipse, VS Code with Java support)  
   - Make sure the ChromeDriver path is correct in each test class  
   - Run the tests as JUnit tests individually or as a suite

---

## Notes

- Tests use explicit waits to handle dynamic page elements and ensure reliability  
- The project uses ChromeOptions with the `--remote-allow-origins=*` argument to support the current ChromeDriver setup  
- The base URL for the tests is mainly `https://itkarijera.ba` or specific subpages  
- Error messages and UI elements are validated based on the website's current content (may require updates if the site changes)

---

## Contact

For any questions or issues, feel free to contact me.

---

*This project was created as part of automated testing practice for the IT Karijera website using Selenium WebDriver and JUnit 5.*
