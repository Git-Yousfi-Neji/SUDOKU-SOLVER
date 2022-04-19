**SUDOKU-SOLVER**<br />
_We all played sudoku at least once in our childhood. It is a very interesting puzzle game. In this project, we’re going to build a sudoku solver program using OpenCV. It detects a sudoku board from an image and then solves it._<br />

First, the program will detect a sudoku board in an image then extract only the board. Then it detects each given number from that board and then it solves the board. After solving the board it puts the solved numbers in that original image at the same position where the board was empty. All these operations will be built with OpenCV python and Deep learning OCR detection.<br />

What is Sudoku?<br />
>Sudoku is a combinational number-placement puzzle. The objective of sudoku is to fill a 9×9 grid with some digits in such a way so that each column, row, and nine 3×3 subgrids contain all of the digits from 0-9.<br />

>We’ll use an algorithm called backtracking. Backtracking is an algorithm for finding solutions to some computational problem. It tries to find a solution until it validates all criteria.<br />

>In sudoku, the algorithm will put a number in an empty space and then move on to the next empty space, if anywhere some criteria fail then it will turn back to some previous solutions and changes it according to the criteria. It continues until it finds a final solution that matches all the criteria.<br />

What is OpenCV?
>OpenCV is an Image processing library for python and it is written in C/C++. We can also perform some real-time operations with OpenCV because it is very fast and lightweight.<br />

What is Deep Learning?
>Deep learning is a subset of machine learning that is built with neural networks. Neural networks try to mimic human brains to solve a problem. Deep learning is used to solve complex problems that cannot be solved with typical machine learning algorithms.<br />

To detect numbers from the sudoku board we’ll use a pre-trained OCR model. OCR or Optical Character Recognition is a technology that recognizes text within a digital image. The model that we’ll be using is specially trained for sudoku. It only detects a single digit in an image.<br />

Prerequisites:<br />
1. Python 3.x
2. OpenCV – 4.4.0
3. Numpy – 1.19.3
4. Tensorflow – 2.5.0
5. Imutils – 0.5.4

**INPUTS**<br />
><img src="../main/Sudoku_Samples/sodoku_1.png?raw=true" ><br />
><img src="../main/Sudoku_Samples/sodoku_2.png?raw=true" ><br />
><img src="../main/Sudoku_Samples/sodoku_3.png?raw=true" ><br />

**OUTPUTS**<br />
><img src="../main/Results/sudoku_1.PNG?raw=true" ><br />
><img src="../main/Results/sudoku_2.PNG?raw=true" ><br />
><img src="../main/Results/sudoku_3.PNG?raw=true" ><br />

