#**SUDOKU-SOLVER**
_We all played sudoku at least once in our childhood. It is a very interesting puzzle game. In this project, we’re going to build a sudoku solver program using OpenCV. It detects a sudoku board from an image and then solves it._

First, the program will detect a sudoku board in an image then extract only the board. Then it detects each given number from that board and then it solves the board. After solving the board it puts the solved numbers in that original image at the same position where the board was empty. All these operations will be built with OpenCV python and Deep learning OCR detection.

#What is OpenCV?
>OpenCV is an Image processing library for python and it is written in C/C++. We can also perform some real-time operations with OpenCV because it is very fast and lightweight.

#What is Deep Learning?
>Deep learning is a subset of machine learning that is built with neural networks. Neural networks try to mimic human brains to solve a problem. Deep learning is used to solve complex problems that cannot be solved with typical machine learning algorithms.

To detect numbers from the sudoku board we’ll use a pre-trained OCR model. OCR or Optical Character Recognition is a technology that recognizes text within a digital image. The model that we’ll be using is specially trained for sudoku. It only detects a single digit in an image.

#Prerequisites:
Order Lists:
1. Python 3.x (we used 3.7.10)
2. OpenCV – 4.4.0
3. Numpy – 1.19.3
4. Tensorflow – 2.5.0
5. Imutils – 0.5.4
