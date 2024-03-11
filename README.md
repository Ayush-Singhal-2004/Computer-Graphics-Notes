<h1>Unit 1</h1>

<h3>Q1. Explain passive computer graphics?</h3>
- In non-interactive computer graphics, the picture is produced on the monitor, and the user does not have any controlled over the image, i.e., the user cannot make any change in the rendered image. One example of its Titles shown on T.V. </br>
- Non-interactive Graphics involves only one-way communication between the computer and the user, User can see the produced image, and he cannot make any change in the image. </br>

<h3>Q2. Write applications of computer graphics ?</h3>
i. Education and Training: Computer-generated model of the physical, financial and economic system is often used as educational aids. Model of physical systems, physiological system, population trends or equipment can help trainees to understand the operation of the system. For some training applications, particular systems are designed. For example Flight Simulator. Flight Simulator helps in giving training to the pilots of airplanes. These pilots spend much of their training not in a real aircraft but on the ground at the controls of a Flight Simulator. </br>
ii. Use in Biology: Molecular biologist can display a picture of molecules and gain insight into their structure with the help of computer graphics. </br>
iii. Computer-Generated Maps: Town planners and transportation engineers can use computer-generated maps which display data useful to them in their planning work.  </br>
iv. Architect: Architect can explore an alternative solution to design problems at an interactive graphics terminal. In this way, they can test many more solutions that would not be possible without the computer. </br>
v. Presentation Graphics: Example of presentation Graphics are bar charts, line graphs, pie charts and other displays showing relationships between multiple parameters. Presentation Graphics is commonly used to summarize Financial Reports, Statistical Reports, Mathematical Reports, Scientific Reports, Economic Data for, research reports, Managerial Reports, Consumer Information Bulletins, and other types of reports. </br>
vi. 6. Computer Art: Computer Graphics are also used in the field of commercial arts. It is used to generate television and advertising commercial. </br>
vii. 7. Entertainment: Computer Graphics are now commonly used in making motion pictures, music videos and television shows. </br>
viii. Visualization: It is used for visualization of scientists, engineers, medical personnel, business analysts for the study of a large amount of information. </br>
ix. Educational Software: Computer Graphics is used in the development of educational software for making computer-aided instruction. </br>
x. Printing Technology: Computer Graphics is used for printing technology and textile design. </br>

<h3>Q3. What is persistence?</h3>
- Persistence is the duration of phosphorescence. Different kinds of phosphors are available for use in CRT. Besides color, a major difference between phosphor in their persistence how they continue to emit light after the electron beam is removed. </br>

<h3>Q4. Define aspect ratio?</h3>
- Aspect Ratio: It is the ratio of width to its height. Its measure is unit in length or number of pixels. </br>

<h1>Unit 2</h1>


<h3>1. What are spline curves?(2022)</h3>
- Spline curves in computer graphics are mathematical representations used to create smooth and flexible curves. They are commonly employed in computer-aided design (CAD), computer graphics, and animation to model and generate curves with desirable properties. Spline curves are particularly useful for creating aesthetically pleasing and visually smooth shapes.</br></br>

There are two main types of spline curves: interpolation splines and approximation splines.</br></br>

i. Interpolation Splines:</br>

Bezier Curves: Bezier curves are one of the most popular types of interpolation splines. They are defined by a set of control points that influence the shape of the curve. Bezier curves can be quadratic (degree 2), cubic (degree 3), or higher degree, depending on the number of control points.
B-splines (Basis Splines): B-splines are defined by a set of control points and a set of basis functions. They provide a flexible way to represent curves and surfaces, allowing for local control over the shape.</br></br>
ii. Approximation Splines:</br>

NURBS (Non-Uniform Rational B-splines): NURBS are a type of spline curve that extends the concept of B-splines. They incorporate weights for each control point, allowing for more control over the influence of each point on the curve. NURBS are widely used in computer-aided design and modeling due to their flexibility.
Spline curves offer advantages such as smoothness, local control over the curve shape, and the ability to represent complex shapes with a relatively small number of control points. They are extensively used in various applications, including 2D and 3D graphics, animation, and industrial design. Software tools like Adobe Illustrator, AutoCAD, and Blender utilize spline curves for creating and manipulating shapes.</br>


<h3>2. Define important properties of the bezier curve?(2022)</h3>
	
Control Points: Defined by a set of control points.End-point Interpolation: Curve passes through the first and last control points.Local Control: Each point influences a local portion of the curve.Convex Hull Property: Curve lies within the convex hull of control points. De Casteljau's Algorithm: Efficient algorithm for curve evaluation. Parametric Representation: Defined parametrically with a parameter (t). Smoothness: Inherently smooth, suitable for visually appealing curves. Affine Invariance: Maintains shape under affine transformations. Degree Versatility: Can be of varying degrees for curve complexity. </br>


<h3>3. Describe the disadvantages of generating an ellipse using polynomial method.(2021)</h3>
- Generating an ellipse using the polynomial method has some disadvantages:</br>

-Complexity: Polynomial equations for ellipses can be complex, especially for high precision or large ellipses, leading to computational challenges.</br>

-Numerical Stability: Polynomial methods may suffer from numerical instability, especially for extreme ellipse shapes or when dealing with floating-point precision issues.</br>

-Limited Flexibility: Polynomial equations might not offer the same level of flexibility as other methods, such as parametric or geometric approaches, making it challenging to manipulate and control the ellipse's properties.</br>

-Increased Computation Cost: Polynomial evaluations can be computationally expensive compared to other ellipse generation techniques, affecting real-time applications or performance-sensitive scenarios.</br>

-Lack of Intuitive Control: Polynomial methods may not provide an intuitive way to control ellipse parameters, such as major and minor axes, center, and orientation, making it less user-friendly for designers and developers.</br>


<h3>4. What is exterior clipping?(2021)</h3>
In computer graphics, exterior clipping refers to the process of removing portions of geometric objects (such as lines or polygons) that lie outside a specified region or viewport. This ensures that only the visible parts of the objects are displayed on the screen, optimizing rendering and improving visual clarity. Exterior clipping is commonly used to enhance efficiency and eliminate unnecessary computations for hidden or irrelevant portions of graphics primitives.</br>


<h3>5. Explain types of text clipping.(2021)</h3>
- In computer graphics, text clipping refers to the process of determining which parts of text should be displayed within a specified region. There are two main types of text clipping:</br></br>

- Rectangle Clipping:</br>

- Involves defining a rectangular region within which text is to be displayed.</br>
- Text outside this rectangle is clipped or truncated, ensuring it stays within the defined boundaries.</br>
- Commonly used in user interfaces and document layout.</br></br>
- Complex Clipping:</br>

- Deals with non-rectangular or complex shapes for text display areas.</br>
- Uses more advanced algorithms, such as polygonal or path-based clipping, to define intricate regions for text visibility.</br>
- Suitable for applications where text needs to conform to irregular shapes or follow specific contours.</br>
- These text clipping techniques are crucial for optimizing the presentation of text in various graphical applications, ensuring that it remains within specified boundaries for effective display.</br>


<h3>6. Explain Bresenham's circle algorithm.(2021)</h3>
- Bresenham's circle algorithm is an efficient method for drawing circles in computer graphics. Instead of using the traditional Cartesian coordinate system and trigonometric functions, Bresenham's algorithm utilizes integer-based arithmetic for simplicity and speed. The algorithm plots points on the circumference of the circle by maintaining symmetry and making decisions based on pixel positions. It minimizes the need for floating-point calculations, making it computationally efficient. Bresenham's circle algorithm is widely used in graphics programming for its speed and simplicity, especially in environments where computational resources are limited.  </br>


<h3>7. Explain Cohen - Sutherland line clipping algorithm.(2021)</h3>
The Cohen-Sutherland line clipping algorithm is used in computer graphics to efficiently clip a line against a rectangular clipping window. Here's a brief explanation:</br></br>

- Region Coding:</br>

- Divide the 2D space into nine regions using a binary code (top, bottom, left, right, and four corners).
- Assign binary codes to both the line endpoints based on their positions with respect to the clipping window.
Clipping Process:</br>

- Check if both endpoints are inside the window (both region codes are 0000). If yes, the line is completely visible.</br>
- If both endpoints share at least one common region code, the line is outside the window and can be entirely rejected.</br>
- If the line is partially inside and partially outside the window, calculate the intersection points with the window boundaries.</br></br>
- Iterative Process:</br>

- Repeat the process until the line is completely inside the window or determined to be entirely outside.
- Adjust the line endpoints based on the intersection points and update their region codes.</br></br>
- Efficiency:</br>
- The algorithm efficiently rejects lines that are entirely outside the window without the need for extensive calculations.</br>
- It reduces the number of computations required to clip lines against a rectangular region.</br>
- The Cohen-Sutherland algorithm is simple and effective for quickly identifying and eliminating portions of a line that are outside a given clipping window.</br>

<h3>8. Explain various steps for DDA line drawing algorithm?(2022)</h3>
- The Digital Differential Analyzer (DDA) line drawing algorithm is a simple method used in computer graphics to draw a line between two specified points. Here are the various steps involved :</br>

- Input:</br>

- Input the coordinates (x1, y1) and (x2, y2) of the two endpoints of the line.</br>
Calculate Differences:</br>

- Calculate the differences Δx and Δy between the x-coordinates and y-coordinates of the two endpoints: Δx = x2 - x1 and Δy = y2 - y1.</br>
- Determine Steps:</br>
- Determine the number of steps (N) based on the larger of |Δx| and |Δy|.</br></br>
- Calculate Increment Values:</br>

- Calculate the incremental values for x (dx) and y (dy): dx = Δx / N and dy = Δy / N.</br>
Initialization:</br>

- Initialize the current coordinates (x, y) to the starting point (x1, y1).</br></br>
- Draw Pixel:</br>

- At each step, plot the pixel at the current coordinates (x, y).</br></br>
- Update Coordinates:</br>

- Update the current coordinates using the incremental values: x = x + dx and y = y + dy.</br></br>
- Repeat:</br>

- Repeat steps 6-7 for N steps until the line is drawn.</br>
- The DDA algorithm is a straightforward approach for line drawing, and its simplicity makes it easy to understand and implement. However, it may suffer from rounding errors, and its efficiency decreases with steeper lines due to the need for floating-point arithmetic.</br>


<h3>9. Explain about the mid point circle generating algorithm?</h3>
- The Midpoint Circle Generating Algorithm is a simple and efficient method for drawing a circle in computer graphics. </br>

<h3>10. What are the advantages of b-spline over bezier curve?</h3>
- Advantages of B-spline over Bezier curve : </br>
i. Local Control : B-splines offer better local control over curve segments, allowing adjustments without affecting the entire curve. </br>
ii. Smoothness and Continuity : B-splines often provide smoother curves and better continuity when compared to Bezier curves, especially in higher-degree representations. </br>
iii. Flexibility in Knot Placement : B-splines allow more flexibility in knot placement, enabling precise control over curve shape and reducing sensitivity to control point distribution. </br>
iv. Rational Representation : B-splines support rational representation, incorporating weights for control points, which enhances the ability to model complex shapes. </br>
v. Degree Elevation : B-splines can be easily elevated in degree while maintaining the original curve, offering more versatility in representing curves of varying complexities.  </br>
vi. Partition of Unity : B-splines exhibit the partition of unity property, ensuring that the sum of basis functions at any point equals 1, simplifying curve blending and interpolation. </br>
vii. Versatility in Interpolation : B-splines can interpolate data points while maintaining curve smoothness, providing a useful property for various applications, including computer-aided design and modeling. </br>

<h3>11. Write down and explain the Bresenham’s line drawing algorithm?</h3>
- 
