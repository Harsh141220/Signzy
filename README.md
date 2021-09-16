# Signzy
To Run

Use python3 main.py -i (path here)
eg. python3 main.py -i /Users/harshbhandari/PycharmProjects/AI/card1.jpeg

You will get 2 outputs: 1 of input image and other of boundary on the image

Please do install:

imutils	0.5.4	0.5.4
opencv-python	4.5.3.56	4.5.3.56
argparse
numpy	1.21.2	


Working:
step1:Load image
step2:convert to Grayscale
step3:apply gaussian filter(smoothen)
step4:apply canny edge algorithm
step5:draw contours and chose the one with highest area
step6:Display
