# Colourful-Calender

📅 Colorful Calendar (Python + Rich)

This project generates a colorful yearly calendar directly in your terminal using the rich
 library.Each month is displayed in a neatly formatted table with colors highlighting weekdays and weekends.

✨ Features


* Full 12-month calendar display.

* Weekdays in green, Saturday in yellow, Sunday in red.

* Simple, lightweight, and customizable.

🛠 Requirements


* Python 3.x

* Install rich:

* pip install rich

📂 Example Output

┏━━━━━━━━━━━━━━━━━━━━━━ January ━━━━━━━━━━━━━━━━━━━━━━┓
┃ Mon │ Tue │ Wed │ Thu │ Fri │ Sat │ Sun            ┃
┃     │     │  1  │  2  │  3  │  4  │  5             ┃
┃  6  │  7  │  8  │  9  │ 10  │ 11  │ 12             ┃
┃ ... │ ... │ ... │ ... │ ... │ ... │ ...            ┃
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛

⚙️ Customization


* Edit the script to change the year:

* colorful_calendar(2025)


Replace 2025 with any year you want.

📝 Notes


* The output looks best on terminals that support ANSI colors.

* If your terminal does not show colors, try using Windows Terminal, PowerShell, or any Linux terminal.

The rich library must be installed; otherwise, the script will not run.

You can easily adjust styles by modifying the column style values in the script.
