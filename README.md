Download Link: https://assignmentchef.com/product/solved-csc22100-exercise1
<br>



1-         Create a hierarchy of Java classes as follows:

MyLine is_a MyShape;

MyPolygon is_a MyShape; MyCircle is_a MyShape.

Class MyShape:

Class MyShapeis the hierarchy’s superclass and inherits the Java class Object.  An implementation of the class defines a point (x, y) and the color of the shape.  The class includes appropriate class constructors and methods, including methods that perform the following operations:

<ol>

 <li>getX, getY, getColor – returns the point (x, y) and color of the MyShape object;</li>

 <li>setX, setY, setColor– sets the point (x, y) and color for the MyShape object;</li>

 <li>toString– returns the object’s description as a String. This method must be overridden in each subclass in the hierarchy.</li>

 <li>draw– draws a MyShape object. This method must be overridden in each subclass in the hierarchy.  For the MyShape object, it paints the drawing canvas in the color specified.</li>

</ol>




Class MyLine:

Class MyLine inherits class MyShape.  The MyLine object is a straight line defined by the endpoints (x<sub>1</sub>, y<sub>1</sub>) and (x<sub>2</sub>, y<sub>2</sub>).  The MyLine object may be of any color.  The class includes appropriate class constructors and methods that perform the following operations:

<ol>

 <li>getLength — returns the length of the MyLine object;</li>

 <li>get_xAngle— return the angle (in degrees) of the MyLine object with the x-axis;</li>

 <li>toString— returns a string representation of the MyLine object: length and angle with the x-axis;</li>

 <li>draw— draws a MyLine object whose end points are (x<sub>1</sub>, y<sub>1</sub>) and (x<sub>2</sub>, y<sub>2</sub>).</li>

</ol>




Class MyPolygon:




Class MyPolygon inherits class MyShape.  The MyPolygon object is a regular polygon defined by the integer parameter, N— the number of the polygon’s equal side lengths and equal interior angles, and the radius, r, in which it is inscribed.  The MyPolygon object may be filled with a color.  The class includes appropriate class constructors and methods that perform the following operations:




<ol>

 <li>getArea— returns the area of the MyPolygon object;</li>

 <li>getPerimeter— returns the perimeter of the MyPolygon object;</li>

 <li>getAngle— return the interior angle (in degrees) of the MyPolygon object;</li>

 <li>getSide— returns the side length of the MyPolygon object;</li>

 <li>toString— returns a string representation of the MyPolygon object: side length, interior angle, perimeter, and area;</li>

 <li>draw— draws a MyPolygon object whose center point (x, y) is defined in class MyShape and inscribed in a circle of radius r.</li>

</ol>




Class MyCircle:




Class MyCircle inherits class MyShape.  The MyCircle object is defined by its radius, r, and center (x, y), and may be filled with a color.  The MyCircle class includes appropriate class constructors and methods that perform the following operations:




<ol>

 <li>getArea— returns the area of the MyCircle object;</li>

 <li>getPerimeter— returns the perimeter of the MyCircle object;</li>

 <li>getRadius— returns the radius of the MyCircle object;</li>

 <li>toString— returns a string representation of the MyCircle object: radius, perimeter, and area;</li>

 <li>draw— draws a MyCircle object of radius r. The center point (x, y) of the circle is defined in class MyShape.</li>

</ol>




2- Use JavaFX graphics and the class hierarchy to draw a geometric configuration comprised of a sequence of alternating concentric circles and their inscribed hexagons as illustrated below, subject to the following additional requirements:




<ol>

 <li>The code is applicable to canvases of variable height and width;</li>

 <li>The dimensions of the shapes are proportional to the smallest dimension of the canvas;</li>

 <li>The hexagons and circles are filled with different colors of your choice, specified through a MyColor enum class.</li>

</ol>




Explicitly specify all the classes imported and used in your Java code.