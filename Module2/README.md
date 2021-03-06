# Module 2
## [Review Assignment 1](https://canvas.uw.edu/courses/1105303/assignments/3464475)
## [Python Data Constructs](https://github.com/summerela/intro_programming_python/blob/master/Module2/2_python_data_contsructs.ipynb)

## Module 2: Formatting Lab

Someone quit their job after writing a broken script and we have to fix it to output data properly.

0. Download and try to run the script `module2_lab1.py`. Note that it doesn't run correctly:

    ```bash
    $ python3 module2_lab1.py
      File "module2_lab1.py", line 8
        a table of rows where the first row
              ^
    SyntaxError: invalid syntax
    ```

0. Find and fix the 3 bad comment sections. Rerun the script when you feel like the problem is solved.
When it runs successfully you'll see output like this:

    ```bash
    $ python3 module2_lab1.py
    FirstName|LastName|City|Zipcode
    Greg|Corradini|Minneapolis|75432
    Summer|Rae|Seattle|98103
    ```

0. Unfortunately, this script is supposed to output a slightly nicer formatted table structure. How might you modify the
last part of the script to produce output that looks sorta like one of the options below?

    ```bash
    |FirstName    |LastName    |City    |Zipcode    |
    |Greg    |Corradini    |Minneapolis    |75432    |
    |Summer    |Rae    |Seattle    |98103    |
    ```

    ```bash
    |FirstName    |LastName     |City         |Zipcode      |
    |Greg         |Corradini    |Minneapolis  |75432        |
    |Summer       |Rae          |Seattle      |98103        |
    ```

## [Operations](https://github.com/summerela/intro_programming_python/blob/master/Module2/3_Operations.ipynb)

## Module 2: Operations Lab

Use string concatenation and user input to write a script that does the following:

0. Create a script called `module2_lab2.py`
0. Write some code that asks the user three arbitrary questions
0. Write some code that takes the three question answers and `print`s the answers using `string.format` in the following style:

    ```bash
    $ python3 module2_lab2.py
    answer1 | answer2 | answer3
    ```

0. Is there a way to do this without string concatenation? Hint, look into the string function `join`

## [String formatting in python](https://github.com/summerela/intro_programming_python/blob/master/Module2/4_String_Formatting.ipynb)

## [Module 2 Homework](https://canvas.uw.edu/courses/1105303/assignments/3464476)
