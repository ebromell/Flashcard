# Flashcard App

"The Pomodoro technique is a time-management method developed by Francesco Cirillo in the late 1980s. The technique uses a timer to break down work into intervals, traditionally 25 minutes in length, separated by short breaks. Each interval is known as a pomodoro, from the Italian word for tomato, after the tomato-shaped kitchen timer that Cirillo used as a university student. For this project, you will implement a simplified version of Cirillo's original Pomodoro technique."

This project is designed to test my ability to work with React.
```
Installing packages via NPM
Running tests from the command line
Writing React function components
Using hooks
Debugging React code
```
This project checks for 

```
Use of any non-pure functions
Use of any variable or function names that can be improved.
Use of if statement to bound lower and upper limits of the focus or break duration. This is because using Math.min() and Math.max() appropriately eliminates the need for if statements with numeric boundaries.
Use of if statements in the returned JSX. Although there is nothing wrong with using conditional statements embedded in JSX, avoiding them generally makes the code easier to understand and maintain.
Use of components with multiple responsibilities or multiple reasons to re-render. For example, if the time format or the upper bound for the focus duration change, consider how many components would need to re-render.
Lots of conditional logic embedded in the useInterval() hook. Most logic should be broken out into small, single-responsibility pure functions that mutate the state as necessary.
```
