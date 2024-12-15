![Screenshot from 2024-12-15 15-16-48](https://github.com/user-attachments/assets/e8055803-c717-41d5-8b65-b3b6f514211b)

# Calendar App </br>

# Overview </br>

The Calendar App is a simple and visually appealing web application that displays the current date, day, month, and year. It uses modern web development practices, including HTML, CSS, and JavaScript, to create a dynamic and responsive user interface. </br>

# Features </br>

Displays the current date, day, month, and year dynamically. </br>

Stylish and responsive design using CSS and flexbox. </br>

Uses JavaScript to fetch and update the date and time information in real-time. </br>

# Files </br>

index.html: Contains the structure of the web page. </br>

style.css: Contains the styling rules for the app. </br>

JavaScript: Included in the index.html file to handle date and time logic. </br>

# Usage </br>

Clone or download the repository. </br>

Open the index.html file in any modern web browser. </br>

View the dynamically updated calendar interface. </br>

# Installation </br>

To use the Calendar App, follow these steps: </br>

## Clone the Repository: </br>

git clone https://github.com/MuchiriKinyua/Calendar-App </br>

## Navigate to the Project Directory: </br>

cd calendar-app </br>

## Open the App: </br>
Open index.html in any web browser. </br>

## Structure </br>

calendar-app/ </br>
├── index.html    # Main HTML file </br>
├── style.css     # Styling rules </br>
└── README.md     # Documentation </br>

# Code Snippets </br>

## JavaScript Logic </br>

const date = document.getElementById("date"); </br>
const day = document.getElementById("day"); </br>
const month = document.getElementById("month"); </br>
const year = document.getElementById("year"); </br>

const today = new Date(); </br>

const weekDays = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"]; </br>
const allMonths = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"]; </br>

date.innerHTML = (today.getDate() < 10 ? "0" : "") + today.getDate(); </br>
day.innerHTML = weekDays[today.getDay()]; </br>
month.innerHTML = allMonths[today.getMonth()]; </br>
year.innerHTML = today.getFullYear(); </br>

## CSS Styling </br>

.hero { </br>
    width: 100%; </br>
    min-height: 100vh; </br>
    background: linear-gradient(45deg, #1d0000, #20205b); </br>
    display: flex; </br>
    align-items: center; </br>
    justify-content: center; </br>
} </br>

.container { </br>
    text-align: center; </br>
} </br>

.name { </br>
    font-size: 30px; </br>
    color: blue; </br>
    margin-bottom: 20px; </br>
} </br>

.calendar { </br>
    width: 300px; </br>
    height: 250px; </br>
    background: #fff; </br>
    display: flex; </br>
    align-items: center; </br>
    border-radius: 10px; </br>
    margin: 0 auto; </br>
} </br>

# Thank you for using the Calendar App!
