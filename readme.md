# Three.js Project

I always say that I like combining coding with art, this has been a project closest to that!

This project is a web-based 3D visualization application built using Three.js, a powerful JavaScript library for creating 3D graphics. The application showcases an interactive 3D scene featuring a detailed GLTF model of Littlest Tokyo, which users can explore using intuitive orbit controls. The project demonstrates the integration of advanced Three.js features, including the use of Draco compression for efficient 3D model loading, WebAssembly for performance optimization, and various Three.js loaders and controls to enhance the user experience.

Key features of the project include:
- **Interactive 3D Model:** The scene includes a high-quality GLTF model of Littlest Tokyo, allowing users to explore the model with smooth, responsive controls.
- **Orbit Controls:** Users can interact with the 3D scene using mouse or touch input to rotate, zoom, and pan around the model, providing an immersive viewing experience.
- **Draco Compression:** The project leverages Draco compression to reduce the size of 3D models, ensuring faster loading times and efficient performance, especially for large models.
- **WebAssembly Integration:** By utilizing WebAssembly, the project achieves high performance in decoding Draco-compressed models, demonstrating the potential of combining JavaScript and WebAssembly in web applications.
- **Modular and Extensible:** The project is structured in a modular way, making it easy to extend with additional features, models, or controls as needed.


<img width="1324" alt="Screenshot 2024-07-29 at 2 59 02 PM" src="https://github.com/user-attachments/assets/745c5bce-5c02-4dbd-80fc-d3e4ebdc8814">

## Live Demo:
https://aarxa-3d.netlify.app

## Getting Started
To get a local copy of this project up and running, follow these simple steps.

### Prequisites
Make sure you have the following installed:
- Node.js
- npm

### Installation
1. **Clone the respository:**
   ```bash
   git clone https://github.com/aarxa/threeJS-project.git

2. **Navigate to the project directory:**
   ```bash
   cd threeJs-project

3. **Install the required npm packages:**
   ```bash
   npm install

## Project Structure
- **'index.html':** The main HTML file for the project.
- **'main.css':** The CSS file for styling the project.
- **'three.module.js':** The core Three.js library.
- **'GLTFLoader.js':** Loader for GLTF 3D models.
- **'OrbitControls.js':** Controls for orbiting around the 3D scene.
- **'DRACOLoader.js':** Loader for Draco-compressed 3D models.
- **'draco_decoder.wasm':** WebAssembly file for Draco decoding.
- **'draco_wasm_wrapper.js':** JavaScript wrapper for the Draco WebAssembly decoder.
- **'LittlestTokyo.glb':** Example 3D model used in the project
- **'manifest.json':** Manifest file for the project.
- **'.git':** Git configuration files.
- **'.vscode':** VSCode configuration files.
- **'readme.md':** readme file

## Dependencies
This project uses the following main libraries:
- [Three.js](https://threejs.org)
- [GTLFLoader](https://threejs.org/docs/#examples/en/loaders/GLTFLoader)
- [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls)
- [DRACOLoader](https://threejs.org/docs/#examples/en/loaders/DRACOLoader)

## Usage
To run the project locally, open the **'index.html'** file in your web broswe. You can use a local server for better performance and to avoid any issues with file paths. 

### Using a Local Server
You can use any local server to serve the project files. One simple way is to use the http-server package from npm:

1. Install http-server globally:
```bash
npm install -g http-server
```

2. Run the server in the project directory:
```bash
http-server
```

3. Open your web browser and go to http://localhost:8080.

## License

Distributed under the MIT License.
