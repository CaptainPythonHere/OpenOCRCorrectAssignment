This code is an extension of the code https://github.com/rohitsaluja22/OpenOCRCorrect/blob/master/README.md \
Kindly refer to the above link to know more about the background of the project.\
Extension is  Under ‘Format’:\
1.	Bold
2.	Un-Bold
3.	Italics
4.	Un-Italics
5.	Underline
6.	Un-Underline
And last ‘About’

## How to run ##
1.	First install qt5
  >  Sudo apt-get install qt5-default
2.	Download the zip file
3.	Extract all files
4.	Open terminal
  >  cd FrameWorkCode
  > qmake qpadfinal.pro
  > make
5.  To run the code:
  > ./qpadfinal

## What has been done? ##
Each feature mentioned above has a purpose as its name. The features Bold/Un-Bold, Italics/Un-Italics, Underline/Un-Underline only affect text highlighted by the cursor, be it a character, word, line or an entire document. Their icons are saved in Resources/Images. There also exits another feature i.e., 'About' displays a URL of youtube video that explains a bit about the project in a dialog box. The entire process has been divided into mainly three files:\
mainwindow.ui, main.cpp,  and mainwindow.cpp.
1.	mainwindow.ui contains the entire layout of the application. Basically, how you want to style and make it look is what is done here. You define the menu bar, tool bar, size of the text editor and placements of buttons here.
2.	main.cpp contains the main function.
3.	mainwindow.cpp contains all the methods that are triggered by clicking on to these buttons of the features. These methods are also refereed to as slots of the buttons, widgets etc.

## Challenges ##
1.	One should be familiar with CPP and OOP.
2.	In depth knowledge and understanding of documentation of qt.
3.	Things might get confusing if not named properly.
