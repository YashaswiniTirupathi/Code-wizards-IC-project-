README
This program is a simple area calculator that can calculate the areas of various shapes, including rectangles, triangles, trapezoids, ellipses, parallelograms, rhombuses, and regular polygons. It also has the capability to calculate the area of an irregular shape by decomposing it into triangles.

Usage
To run the program, simply save the code as a .c file and compile it using a C compiler. Once compiled, execute the program. The program will prompt you to enter your choice of shape to calculate the area for.

Options
Here are the available options:

Rectangle: Calculates the area of a rectangle given its length and width.
Triangle: Calculates the area of a triangle given its base and height.
Trapezoid: Calculates the area of a trapezoid given its two bases and height.
Ellipse: Calculates the area of an ellipse given its major and minor axes.
Parallelogram: Calculates the area of a parallelogram given its base and height.
Rhombus: Calculates the area of a rhombus given the lengths of its diagonals.
Regular Polygon: Calculates the area of a regular polygon given the number of sides, side length, and apothem.
Irregular Shape: Calculates the area of an irregular shape given the coordinates of its vertices.
Input Format
For each shape, the program will prompt you to enter the required input values. The input format for each shape is as follows:

Shape	            Input Format
Rectangle	        Length, Width
Triangle	        Base, Height
Trapezoid        	Base1, Base2, Height
Ellipse	          MajorAxis, MinorAxis
Parallelogram    	Base, Height
Rhombus          	Diagonal1, Diagonal2
Regular Polygon  	Number of Sides, Side, Length, Apothem
Irregular Shape	  Number of Vertices, Coordinates of Vertices (x y) for each vertex

Output Format
The program will display the calculated area of the selected shape. The output format for each shape is as follows:

Shape:	Output Format
Rectangle	Area of the rectangle: %f
Triangle	Area of the triangle: %f
Trapezoid	Area of the trapezoid: %f
Ellipse	Area of the ellipse: %f
Parallelogram	Area of the parallelogram: %f
Rhombus	Area of the rhombus: %f
Regular Polygon	%f
Irregular Shape	Area of the irregular shape: %f square units
