# KenKen Solver  

![4x4 KenKen puzzle no. 200059 from kenkenpuzzle.com](/images/input.jpg)
*4x4 KenKen puzzle no. 200059 from [kenkenpuzzle.com](https://www.kenkenpuzzle.com/)*
<br><br>

### How to Play

---

Each KenKen puzzle is a square with dimensions *n* by *n*. The objective is to fill the grid in with the digits 1 through *n* so that:

1. Each row contains exactly one of each digit
2. Each column contains exactly one of each digit
3. Each bold-outlined group of cells is a cage containing digits which achieve the specified result using the specified mathematical operation: addition (+), subtraction (−), multiplication (×), and division (÷).
<br><br>

### Creating Your Input File

---

1. Create a text input file and remember the name as you will definitely need it later
2. Using the above KenKen puzzle as an example, your input file will be formatted as follows:
   1. First line contains the dimension of your KenKen puzzle *n* (it's a square so the size of only one side is needed)  
        > 4  
   2. Next *n* lines will be formatted to look like a text representation of the KenKen puzzle with letters representing cells starting from the top left moving across. Each line will have *n* letters each separated by a space and each letter will represent a cell in the bold outlined cage, with a unique letter being assigned to each one cage. The number of unique letters in the input file will equal the number of cages in the KenKen puzzle. An example is given below:
        > a b b c  
        > a d d c  
        > e e d f  
        > g g f f  
    3. The last lines will have each unique letter representing the cage, the specified result, and the operation. If the cage has just one cell, the operator should be an equal (=) sign
        > a 12 *  
        > b 2 /  
        > c 3 -  
        > d 6 +  
        > e 2 /  
        > f 9 +  
        > g 2 -  
    4. Save the input text file in the same directory as kenken.py
<br><br>

## Solving the Puzzle

---

1. Run kenken.py and enter the name of the input file with the extension (input.txt)
2. The program will output your solution in a text file *solution.txt*
    > 3  1  2  4  
    > 4  2  3  1  
    > 2  4  1  3  
    > 1  3  4  2  
3. Input and brag to your friends about how genius you are!
<br><br>
![4x4 KenKen puzzle no. 200059 from kenkenpuzzle.com](/images/output.jpg)
*4x4 KenKen puzzle no. 200059 solution from [kenkenpuzzle.com](https://www.kenkenpuzzle.com/)*
<br><br>

## Versions  

---

**Version 1.0**  
*Original code w tests commented out*

**Version 1.1**  
*Gets filename input using while loop*
<br><br>

## Future updates  

---

*Add GUI and user interface*  
*Source input using image recognization*  
*Provide answers in GUI*