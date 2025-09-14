Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.

21. Since no time is started so the time starts at 00:00
23. I need to call the method 60 times. Or you may call the setTime method and set the minutes to 60 manually.
24. NumberDisplay digit = new NumberDisplay(10);
25. Rectangle window = new Rectangle(12, 10)
26. The second constructor allows you to create a clock display with your own limits for the hours and minutes.
27. The second constructor has parameters while the first doesn't. The second doesn't have the updateDisplay method which is a difference in both constructors, because it has the setTime display which has the updateDisplay method in it so that's what is different.
28. p1.print("File", True);
    p1.getStatus(1);
29. Triangles, squares, and circles.
30. roof = new Triangle();
    roof.changeSize(60, 180);
    roof.moveHorizontal(20);
    roof.moveVertical(-60);
    roof.makeVisible();
    roof.changeColor("black");
    roof.changeColor("green");
31. Yes is the answer.
32. 2
33. It accepts negative numbers as well.
