# OpenGL Shader Eyecandy

This project showcases an OpenGL shader program that renders a visual effect using fragment shaders. The shader code is based on a Shadertoy shader I made and has been ported to OpenGL.

## Features

- Visual effect based on a ported Shadertoy shader.
- Real-time rendering using OpenGL.
- Full-screen quad rendering.
- Dynamic time-based animation.

## Dependencies

- OpenGL
- GLEW
- GLFW

## Build Instructions

1. Make sure you have the necessary dependencies installed on your system: OpenGL, GLEW, and GLFW.

2. Clone this repository to your local machine.

3. Create a build directory and navigate to it:
```bash
mkdir build
cd build
```

4. Run CMake to generate the build files:
```bash
cmake ..
```

5. Build the project using the generated build files:
```bash
make
```

6. Run the executable:
```bash
./OpenGL_Shader
```

## Usage

- Once you run the program, a window will appear showing the rendered shader effect.
- The shader effect will animate and update in real-time based on the current time.
- Experiment with modifying the shader code in the `main.cpp` file to create your own custom effects :).
- Explore and tweak the shader parameters to achieve different visual results.

## License

This project is licensed under the [MIT License](LICENSE).

## To do:

- Add more shaders made by me.
- Separate shaders from source.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
