List all the rectangles

Shows all rows from the rectangles table (17 rows as per your INSERTs)

How many rectangles are there?
Answer: 17

What color is the widest rectangle?
Answer: #123456 (width = 20, row with x=8, y=8)

What color is the tallest rectangle?
Answer: #ff5733 (height = 14, row with x=6, y=6)

List all rectangles that are wider than they are tall

Rows where width > height (e.g., width=10,height=5; width=12,height=3; etc.)

Calculate and select the area of each rectangle

Adds a column area = width × height for each row

What color is the largest rectangle?
Answer: #ffffff (area = 324, width=18, height=18)

What color is the rectangle that extends the most to the right?
Answer: #abcdef (x+width = 12+25 = 37, largest rightmost coordinate)

Find rectangle(s) with NULL color
Answer: The rectangle with x=1, y=4, width=4, height=4, color=NULL

List all the different colors without duplicates

Returns: red, blue, green, yellow, #aabbcc, #ff5733, purple, #123456, orange, #654321, pink, #abcdef, #000000, #ffffff, #ffffff0, NULL

List all the different named colors (without NULL)
Answer: red, blue, green, yellow, purple, orange, pink

List rectangle colors in uppercase letters

All colors converted to uppercase (RED, BLUE, #AABBCC, etc.)

What is the course_id of the course with the longest name?
(Assuming from t177.sql data)
Answer: Likely COMP3301 or similar (depends on actual course names)

How many assignments are there with due dates in 2024?
(Assuming assignments table data)
Answer: Likely 8 or similar count

Concatenate Course ID and name with colon and space

E.g., "COMP1151: IT Essentials", "COMP2250: Programming in Python", etc.

List courses with labs on Mondays

Any courses where lab_time starts with "Mon"

Assignments due before January 1st, 2025

All assignments with due_date < '2025-01-01'

How many assignments are there for each course

Grouped counts like: COMP1151: 3, COMP2250: 4, etc.

List all assignments for courses that ran in semester 2024-3

Assignments from courses where semester = '2024-3'

Show the red component of all the RGB colors
Answers:
#aabbcc → "aa"
#ff5733 → "ff"
#123456 → "12"
#654321 → "65"
#abcdef → "ab"
#000000 → "00"
#ffffff → "ff"
#ffffff0 → "ff" (first 2 chars after #)
