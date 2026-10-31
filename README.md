# Adactin Hotel Booking Automation Testing

## Project Overview

This project is developed as part of the Software Testing course. It focuses on automating the Adactin Hotel Booking Application using Selenium WebDriver with C#.

The project follows the Page Object Model (POM) design pattern to maintain clean, reusable, and organized automation code.

**Website:** https://adactinhotelapp.com/

## Technologies Used

- C#
- Selenium WebDriver
- NUnit Framework
- Visual Studio
- Allure NUnit
- JSON Test Data
- Chrome Browser

## Project Structure

```text
Kuchbhee/
│
├── Data File/
│   └── data.json
│
├── LocateFile/
│   └── LocatorClass.cs
│
├── MiscFile/
│   ├── BaseClass.cs
│   └── UnitTest.cs
│
├── PageClass/
│   ├── LoginPage.cs
│   ├── SearchHotel.cs
│   ├── SelectHotel.cs
│   ├── BookHotel.cs
│   ├── BookingConfirmation.cs
│   └── Logout.cs
│
└── UnitTest1.cs
```

## Test Scenarios

1. **Login:** Verify user login functionality using valid credentials.
2. **Search Hotel:** Search hotels using location, hotel name, room type, dates, and guest details.
3. **Select Hotel:** Select an available hotel.
4. **Book Hotel:** Enter customer and payment information.
5. **Booking Confirmation:** Verify successful booking and retrieve the order number.
6. **Logout:** Verify successful logout functionality.

## Framework Design

The project uses the Page Object Model (POM), where each application page has a separate class.

- **BaseClass:** Handles ChromeDriver initialization, browser navigation, JSON test data reading, and browser closing.
- **LocatorClass:** Stores element locators.
- **Page Classes:** Contain individual page actions.
- **Unit Tests:** Execute the automation test scenarios using NUnit.

## Test Data Management

Test data is maintained in a separate JSON file. This allows credentials and booking information to be managed independently from the automation scripts.

## How to Run the Project

1. Clone or download this repository.
2. Open the project in Visual Studio.
3. Restore the required NuGet packages.
4. Configure the test data in `data.json`.
5. Build the solution.
6. Open Test Explorer.
7. Run the required NUnit test cases.

## Project Objective

The objective is to gain practical experience in browser automation, Selenium WebDriver, NUnit test execution, JSON-based test data handling, and the Page Object Model design pattern.

---

**Developed as part of Software Testing coursework.**
