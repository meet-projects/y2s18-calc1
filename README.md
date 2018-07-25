# Lab: `calc1`
<table>
  <tr>
    <th>Lecture</th>
    <td>Day 3 Lecture 1: <a href="">Introduction to JavaScript, Part 1</a></td>
  </tr>
  <tr>
    <th>Description:</th>
    <td>In this lab, we will be creating a very simple six-function (+, -, *, /, %, ^) calculator that can take input from the user and output the answer.</td>
  </tr>
</table>

## 1&ensp; Using JavaScript
1. Edit the blank HTML Page called `index.html`. Add the appropriate HTML tags so that the page has:
    1. A **title** in of `Calculator`
    2. A **h1** in the body with the text `Calculator`
    3. A **script** tag right before the closing tag of the body (`</body>`). Print something out to the console to make sure your HTML is correct.

Don't know what to do? Code [here]().

## 2&ensp; Functions

1. Write a function within the ``<script>`` tags called <code><b>exponent</b></code> that takes in two parameters `b`, `p` and returns $b^p$. Do this without using `Math.pow`.

Don't know what to do? Code [here]().

## 3&ensp; Conditionals

1. Write a function within the ``<script>`` tags called <code>**calculate**</code> that takes in three arguments: `operation`, `val1`, and `val2`, and have the function return the value of `val1 (operation) val2`. For example, calling ``calculate("/", 10, 2)`` should return `5`.
    - **calculate** should support the following operations:
        1. **+** (addition)
        2. **-** (subtraction)
        3. **\*** (multiplication)
        4. **/** (division)
        5. **%** (remainder, modulus)
        6. **^** (exponent)
    - If `operation` is not one of the six operations above, return `false`.

Don't know what to do? Code [here]().

## 4&ensp; User I/O
1. Write a function within the ``<script>`` that prompts the user three times: the first time for a number $a$, the second for an operation $op$, and third for another number $b$. Pass those values into <code>**calculate**</code> and use an alert to tell the user the result.

Don't know what to do? Code [here]().

## 5&ensp; Congratulations!
1. You did it! You should move on to the challenges (from the exercises) to learn more about JavaScript.