# index.html
firstly we have created two  buttons which to clear the board and one is for undo the results 
second we have a canvas tag which is for board 
then we have
 created three more button for selecting the color to draw

 # index.js
 then we are selecting the canvas and giving the height and width
 then we have context for line which is given 2d
 then we declare variable as null and giving the width of line
 after that we are defining the initial color of line which is black

  after that we are added two event listener one is for drawing and another is for stop the drawing 
  then we are checking the condition that if it is null then it will not draw 
  else it will run this part of code which says that
  <!-- let currentX=e.clientX,
currentY=e.clientY;
context.beginPath();
context.moveTo(x,y);
context.lineTo(currentX,currentY);
context.stroke();

x=currentX;
y=currentY;
}); -->
from where to begin and mmove till where and from currentx to current y it will draw the line and stroke will stop where we stop the moving 