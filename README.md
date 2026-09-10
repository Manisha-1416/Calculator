# 📅 Python Calendar

A simple **Python Calendar Project** that displays the calendar for a year and month entered by the user.

## 🚀 Features

* Enter any year.
* Enter any month.
* Displays the complete calendar for the selected month.
* Uses Python's built-in `calendar` module.
* Beginner-friendly project for learning Python.

## 🛠️ Technologies Used

* **Python**
* **calendar module**

## 📌 How It Works

The program asks the user to enter:

1. Year
2. Month

It then uses the `calendar.month()` function to display the calendar.

### Example

```text
Enter the year: 2026
Enter the month: 9

   September 2026
Mo Tu We Th Fr Sa Su
    1  2  3  4  5  6
 7  8  9 10 11 12 13
14 15 16 17 18 19 20
21 22 23 24 25 26 27
28 29 30
```

## 💻 Code

```python
import calendar

year = int(input("Enter the year: "))
month = int(input("Enter the month: "))

print(calendar.month(year, month))
```

## ▶️ How to Run

1. Install Python on your computer.
2. Clone or download this repository.
3. Open the project folder in VS Code or a terminal.
4. Run:

```bash
python calendar.py
```

5. Enter the year and month when prompted.

## 📚 What I Learned

* Importing Python modules
* Using the `calendar` module
* Taking user input
* Converting input using `int()`
* Using Python functions
* Displaying formatted output

## 🔮 Future Improvements

* Highlight a selected date.
* Add a graphical user interface (GUI).
* Allow users to enter a specific date.
* Add navigation between months.
* Highlight today's date.

## 👩‍💻 Author

**Manisha**

---

⭐ If you like this beginner Python project, consider giving the repository a star!
