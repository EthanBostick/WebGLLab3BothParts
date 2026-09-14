# WebGLLab3Part1
submission for Ethan Bostick 9/14/26

1) simply changing the lookat(...) to translate(0,0,-10) does not change the display, because the view is still head on to the z-axis making it invisible.

2) the axis' disappear leaving a blank black screen. This is most likely due to there being no model view matrix to position the viewport

4) a. after changing the height in boxes.html the display warps to accomodate the new dimensions. Noteably the y-axis shrank to fit in at the same ratio relative to the height as before.

b. Similarly changing the width affects the x-axis in the same way, shinking it down to fit within the new dimensions but keeping the relative length/size the same.

c. changing the aspect ratio to width/height makes the displayed axis remain the same size relative to each other, rather than the size being relative to just the dimension of width or height.

10) To keep the x and y axis' original orientations the same I would rotate the camera instead of the scene geometry.

summary:
I got more comfortable with openGL matrix transformations. I also learned more about the view matrix for positioning the camera.