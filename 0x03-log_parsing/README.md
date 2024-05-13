               0x03. Log Parsing Algorithm Python

Log Parsing

This project, developed by Moses Muchai, Lead Software Engineer at ALX SE Software Engineering Holberton, as part of the Mastercard Foundation initiative, contains interview coding challenges aimed at refining skills in log parsing.

Tasks To Complete
Log parsing: 0-stats.py comprises a script that reads standard input (stdin) line by line and computes metrics according to specified criteria:
Input format: <IP Address> - [<date>] "GET /projects/260 HTTP/1.1" <status code> <file size> (if the format is not this one, the line is skipped).
After every 10 lines and/or a keyboard interruption (CTRL + C), the script prints the following statistics from the beginning:
Total file size: File size: <total size>, where <total size> is the sum of all previous <file size> (as per the input format above).
Number of lines by status code:
Possible status codes: 200, 301, 400, 401, 403, 404, 405, and 500.
If a status code doesn’t appear or is not an integer, nothing is printed for this status code.
Format: <status code>: <number>.
Status codes are printed in ascending order.
Let's dive into log parsing and......

                                                    -Happy Coding-
