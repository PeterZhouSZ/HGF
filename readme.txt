This is an implementation of the paper “A Hyperbolic Geometric Flow for Evolving Films and Foams” Sadashige Ishida, Masafumi Yamamoto, Ryoichi Ando, and Toshiya Hachisuka, Transactions on Graphics (SIGGRAPH Asia 2017).

Author: Sadashige Ishida
Lisence: BSD

[[Basic usage]]
Running the executables without command line arguments will display usage
information. All the data files for testing are located in the hgf_assets folder.

[KEY SETTING]
Space: Turn on/off the clock.
s: Proceed one time step.

Slash: Turn on/off the scene specific update. b: Burst a randomly chosen bubble.
l: Move constrained vertices to left.
r: Move constrained vertices to right. +: Inflate a bubble. -: Deflate a bubble.

m: Change rendering mode.
o: Save the state as files containing information of mesh, labels, and constrained vertices.
O: Save the state as above, but with ghost vertices and faces.
and etc.

[[Dependencies]]
This program is built by standard procedures using CMAKE (http://www.cmake.org). The following external libraries are required:
Eigen (http://eigen.tuxfamily.org)
LAPACK (http://www.netlib.org/lapack/)
libigl (http://libigl.github.io/libigl/)
OpenGL (https://www.opengl.org/) 
GLEW (http://glew.sourceforge.net/) for non-mac OS

[Acknowledgement]
This is built on SoapFilm3D, which is a simulation program accompanying the paper “Double Bubbles Sans Toil and Trouble: Discrete Circulation-Preserving Vortex Sheets for Soap Films and Foams”, Fang Da, Christopher Batty, Chris Wojtan, and Eitan Grinspun, Transactions on Graphics (SIGGRAPH 2015).
