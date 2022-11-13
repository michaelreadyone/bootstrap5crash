# [Bootstrap 5 Crash Course](<https://www.youtube.com/watch?v=Jyvffr3aCp0>)

--- 2:00 --- Container and Breakpoints basics

size below setting class will be fluid(100%width), size above will be bootstrap container style
container-fluid all 100%
breaks points allow you to define what you want to do at that size and above, this appears everywhere in bootstrap

--- 5:37 --- Columns

bootstrap use 12 columns hard coded structure,
default "col" use flexbox
"col-6" will take 6/12 of row size
"col-auto" use the smallest size to fit all context
"col-lg-4 col-8" col take 4 size when screen size >= lg, else, take 8 size
"col-lg-4" if no command for smaller size screen, it will accept as col-12 for smaller screen
if more than 12 hard coded col size in one row, it will push to next row
"col-3 offset-3" push this col 3 sizes to right

--- 14:03 --- Rows

two cols every row:
"row row-cols-2 row-cols-lg-4" 

gap between rows: g: gap, gx: gap in x direction, gy: gap in y direction
"gy-2" number varies between 0 and 5

nested row: row inside a column inside a row

Principles in using rows and cols in bootstrap:
if use a row, everything should go inside a column, don't put row inside a row, don't put col inside a col
structure should be :
- container
    - row
      - col
        - ...

--- 17:35 --- Tables

