# OpenGL_1
First project working with OpenGL API

# Required dependencies:
- GLFW32bin (https://www.glfw.org/download.html) - already in project

# Additional actions
- Additional include dictionaries:
  - C/C++ General: $(SolutionDir)Dependencies\GLFW\include;$(SolutionDir)Dependencies\GLEW\include
  - Linker General: $(SolutionDir)Dependencies\GLFW\lib-vc2019;$(SolutionDir)Dependencies\GLEW\lib\Release\Win32

- Additional dependencies: glfw3.lib;opengl32.lib;user32.lib;gdi32.lib;Shell32.lib;glew32s.lib
- Preprocessor Definitions: GLEW_STATIC
