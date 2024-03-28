# Three.js Holographic Animation Project

This project utilizes Three.js, a popular JavaScript library for creating 3D graphics in web applications. The primary purpose of this project is to showcase a holographic animation effect using shaders.

## Project Overview

The project contains the following components:

- **JavaScript**: The main script file is `index.js`, which includes the setup of the Three.js scene, camera, renderer, controls, objects, and animation loop.

- **Shaders**: Two shaders are used for the holographic effect: `vertex.glsl` for vertex manipulation and `fragment.glsl` for fragment color computation.

- **Assets**: The project includes a GLTF model (`suzanne.glb`) and custom shaders.

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository to your local machine.
2. Open the project directory in your code editor.
3. Install dependencies using npm or yarn: `npm install` or `yarn install`.
4. Start the development server: `npm start` or `yarn start`.
5. Open your web browser and navigate to `http://localhost:3000` to view the project.

## Usage

Feel free to explore and modify the project as needed. Here are some common tasks you may want to perform:

- Adjust the holographic effect parameters in the shaders to achieve different visual effects.
- Replace the GLTF model (`suzanne.glb`) with your own models for customized animations.
- Experiment with different Three.js features and techniques to enhance the project.

## Credits

- **Three.js**: [threejs](https://threejs.org/)
- **GLTFLoader**: Official Three.js loader for GLTF models.
- **OrbitControls**: Provides orbit control for the camera.
- **lil-gui**: Lightweight GUI library for debugging and adjusting parameters.

The project was made with the help of [threejs-journey course](threejs-journey.com)
