# Fractals
Fractal geometry using OpenGL and C

This code was created as a part of my 6th Sem CG lab project.

I have created 5 fractals using OpenGL and C:
1. Sierpinski Gasket
2. Barnsley fern
3. Koch snowflake
4. Dragon curve
5. Cantor set

The SOIL library has been used to load the image fractalblack.jpg
SOIL.h can be installed using the following command:
sudo apt-get install libsoil-dev

OpenGL can be installed using the following command:
sudo apt-get install freeglut3-dev

Compilation of the file must be done as:
gcc -o foo foo.c -lglut -lGLU -lGL -lm -lSOIL
