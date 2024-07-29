# Three.js Project

This project demonstrates a 3D scene using Three.js, a popular JavaScript library for creating 3D graphics in the web browser. The scene includes a 3D model and allows for user interaction through various controls.

<img width="1324" alt="Screenshot 2024-07-29 at 2 59 02 PM" src="https://github.com/user-attachments/assets/745c5bce-5c02-4dbd-80fc-d3e4ebdc8814">

## Table of Contents
- Getting Started
- Project Structure
- Dependencies
- Usage
- License

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

3. Open your web browser and go to http://localhost:8080.

