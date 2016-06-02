# graphics-glfw-bezierSurface
An expansion of the Bezier Curve example, which now deals with a surface.

An expansion of the Bezier curve example, this example deals with a Bezier surface, now with 16 control points. The math theory is still the same, just the curve now needs to be solved for more control points. To find the position of a given point on the surface, each row of control points needs to be solved at that column to form 4 meta-control points that can then be used to solve to for the current vertex position.


This example also includes expanded camera functionality so you can get a better look at that curve.

Controls:

Use left and right arrow keys to change the current control point.

Use WASD, Ctrl and Shift to move the current control point.

Space bar to toggle visible control points.

Click and drag with the left mouse button to move the camera.
