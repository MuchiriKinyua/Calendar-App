![Screenshot from 2024-12-15 15-16-48](https://github.com/user-attachments/assets/e8055803-c717-41d5-8b65-b3b6f514211b)

# Calendar App

# Overview

The Calendar App is a simple and visually appealing web application that displays the current date, day, month, and year. It uses modern web development practices, including HTML, CSS, and JavaScript, to create a dynamic and responsive user interface.

# Features

Displays the current date, day, month, and year dynamically.

Stylish and responsive design using CSS and flexbox.

Uses JavaScript to fetch and update the date and time information in real-time.

# Files

index.html: Contains the structure of the web page.

style.css: Contains the styling rules for the app.

JavaScript: Included in the index.html file to handle date and time logic.

# Usage

Clone or download the repository.

Open the index.html file in any modern web browser.

View the dynamically updated calendar interface.

# Installation

To use the Calendar App, follow these steps:

## Clone the Repository:

git clone (https://github.com/MuchiriKinyua/Calendar-App)

## Navigate to the Project Directory:

cd calendar-app

## Open the App:
Open index.html in any web browser.

## Structure

calendar-app/
├── index.html    # Main HTML file
├── style.css     # Styling rules
└── README.md     # Documentation

# Code Snippets

## JavaScript Logic

const date = document.getElementById("date");
const day = document.getElementById("day");
const month = document.getElementById("month");
const year = document.getElementById("year");

const today = new Date();

const weekDays = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
const allMonths = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"];

date.innerHTML = (today.getDate() < 10 ? "0" : "") + today.getDate();
day.innerHTML = weekDays[today.getDay()];
month.innerHTML = allMonths[today.getMonth()];
year.innerHTML = today.getFullYear();

## CSS Styling

.hero {
    width: 100%;
    min-height: 100vh;
    background: linear-gradient(45deg, #1d0000, #20205b);
    display: flex;
    align-items: center;
    justify-content: center;
}

.container {
    text-align: center;
}

.name {
    font-size: 30px;
    color: blue;
    margin-bottom: 20px;
}

.calendar {
    width: 300px;
    height: 250px;
    background: #fff;
    display: flex;
    align-items: center;
    border-radius: 10px;
    margin: 0 auto;
}

# Thank you for using the Calendar App!
