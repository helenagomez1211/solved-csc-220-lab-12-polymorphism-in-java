Download Link: https://assignmentchef.com/product/solved-csc-220-lab-12-polymorphism-in-java
<br>
Exercise polymorphism in Java.

<ol>

 <li>Write a class Point. Points are described as having an (x,y) location. Instance variables should be private. Your class should contain a constructor that takes two integer values to set the point, accessor and mutator methods for the private instance variables and a toString method that prints the coordinates of the point.</li>

 <li>Write a class Circle. Since circles are described by a centerpoint and a radius, the Circle class should extend the Point You need to add a private double for the radius. You should include a constructor, an accessor and a mutator method for the radius. Negative radii are not permitted (check and print an error message in the mutator). You should override the toString method to print the coordinates of the point, the radius, and the area of the circle.</li>

 <li>Write a class Cylinder. Since cylinders are circles with heights, the Cylinder class should extend the Circle Add the appropriate instance variable and include a constructor, an accessor and a mutator method. Override the toString method to print the coordinates of the point, the radius, the height and the volume of the cylinder.</li>

 <li>Write a driver class called Application that reads three x,y locations, radii and heights from the user. Create 3 point, 3 circle and 3 cylinder objects using the input values. Use polymorphism (and a for loop) to store all objects in one ArrayList. Finally use polymorphism to print the description of each object.</li>

</ol>