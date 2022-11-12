# [Bootstrap 5 Crash Course](<https://www.youtube.com/watch?v=Jyvffr3aCp0>)

--- 2:00 --- Container and Breakpoints basics

size below setting class will be fluid(100%width), size above will be bootstrap container style
container-fluid all 100%

--- 5:37 --- Columns

bootstrap use 12 columns hard coded structure,
default "col" use flexbox
"col-6" will take 6/12 of row size
"col-auto" use the smallest size to fit all context
"col-lg-4 col-8" col take 4 size when screen size >= lg, else, take 8 size
"col-lg-4" if no command for smaller size screen, it will accept as col-12 for smaller screen
if more than 12 hard coded col size in one row, it will push to next row
"col-3 offset-3" push this col 3 sizes to right