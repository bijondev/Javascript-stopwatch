# Javascript stopwatch

The JavaScript stopwatch is a basic implementation of a stopwatch that can be used in web applications. The stopwatch consists of three buttons: Start, Stop, and Reset, and a display that shows the elapsed time in minutes, seconds, and hundredths of seconds.

The stopwatch is implemented using JavaScript functions that utilize the Date.now() function to keep track of the elapsed time. The setInterval() function is used to update the display every 10 milliseconds, and the clearInterval() function is used to stop the timer when the Stop button is clicked.

The Reset button resets the elapsed time to 0 and updates the display accordingly. The display is formatted to show leading zeros for each component of the elapsed time, and the padStart() method is used to ensure that each component always has at least 2 digits.

This JavaScript stopwatch can be easily customized and integrated into other web applications as needed.
