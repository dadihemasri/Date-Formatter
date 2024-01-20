
##  [Date Formatter](https://github.com/dadihemasri/Javascript-DSA-challenge/tree/main/Date%20Formatter)

### Overview 📜

In this project, I focused on working with dates in JavaScript, tackling the challenges of navigating various methods, formats, and time zones. The goal of this project is to enhance my understanding of the JavaScript Date object, including its methods and properties. Additionally, I aimed to master the art of correctly formatting dates.

### Key Concepts Covered:
- JavaScript Date object
- Date methods: getDate(), getMonth(), getFullYear()
- Formatting dates
- Handling time zones

### Implementation Details:

#### 1. Getting Current Date
I used the JavaScript Date object to get the current date, including the day, month, and year.

```javascript
const currentDate = new Date();
const day = currentDate.getDate();
const month = currentDate.getMonth() + 1; // Note: Months are zero-based
const year = currentDate.getFullYear();
```

#### 2. Formatting Date
I formatted the date in the "DD-MM-YYYY" format using template literals.

```javascript
const formattedDate = `${day}-${month}-${year}`;
```

#### 3. Displaying Formatted Date
I updated the HTML to display the formatted date.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Date Formatter</title>
</head>
<body>
    <h1>Date Formatter</h1>
    <p id="formattedDate">Formatted Date: </p>
    <script src="script.js"></script>
</body>
</html>
```

#### 4. Handling Time Zones
I explored handling time zones by adjusting the Date object.

```javascript
const utcDate = new Date().toUTCString(); // Get UTC time
```

### Live Project 🌐

Explore the live project [here](https://dadihemasri.github.io/Date-Formatter/).

<!-- Add screenshots here -->
<img width="398" alt="image" src="https://github.com/dadihemasri/Date-Formatter/assets/85781102/bb1a3c72-9858-48af-bc4a-ee40ac5633c5">


## How to Use 🛠️

1. **Clone this Repository:**
   ```bash
   git clone https://github.com/dadihemasri/Javascript-DSA-challenge.git
   ```

2. **Navigate to Day-4_Date_Formatter:**
   ```bash
   cd Javascript-DSA-challenge/Day-4_Date_Formatter
   ```

3. **Open index.html in a Browser:**
   Simply open the `index.html` file in your preferred web browser to see the Date Formatter in action.

## 🚧 Future Projects
Stay tuned for more exciting projects as I continue my JavaScript DSA Challenge. Each project builds on the concepts learned, providing a comprehensive learning experience in JavaScript and Data Structures/Algorithms.

Happy coding! 🚀
