# Gamma_Corr_Updated
This is an "updated" version of Joey de Vries's sample code he provided in his LearnOpenGL's "Gamma Correction" tutorial. The link to that tutorial is here: (note: I found there are hyperlinks in this site connecting to other files too.)

https://learnopengl.com/code_viewer_gh.php?code=src/5.advanced_lighting/2.gamma_correction/gamma_correction.cpp

Changes:

-I replaced function loading code involving GLAD with code involving GLEW, and I replaced image loading code involving "stb_image.h" with code involving SOIL.h.

-I also updated some of the Shader function calls. Mainly changed use() to Use(), and used more functions of the form "glUniform". 

-I replaced camera.Zoom with glm::radians(camera.Zoom). 

-Lastly, I used wood.jpg instead of wood.png, for some reason the png file wasn't working for me correctly. 

I admit, I'm still new to OpenGL as I'm writing this, most of my time right now is just copying/pasting code, just happy to see stuff work for now haha. But the code works for me. Hope it helps. 

Also, thanks to Joey for making tutorials like these. They're helpful. May not get it at all in the first few reads, but I feel it's easier to understand than other tutorials.

