# Babylon.js Mesh Extrusion Application
This project is an implementation of a Babylon.js application that allows users to extrude a cube to modify its shape. The application provides a user-friendly interface for selecting a face of the cube and smoothly animating the extrusion effect.

## Features
* User Input: Users can select a face of the cube to be extruded by clicking on it.
* Extrusion Animation: When the user triggers the extrusion action, the cube's vertices smoothly animate to create the extrusion effect.

## Installation
1. Clone the repository:
  ```
  git clone [https://github.com/your-username/babylon-withoutgizmos.git](https://github.com/Nikhilshetty-github/babylon-withoutgizmos.git)https://github.com/Nikhilshetty-github/babylon-withoutgizmos.git

  ```
2. Open the project folder:
    ```
    cd babylon-withoutgizmos
  
    ```
3. Run a local development server (e.g., using VS Code's Live Server extension) or host the project on a web server.
4. For this project i used MAMP server you can use the live server from the vs code or just download the MAMP server and run locally on you machine.

## Usage
1. Open the application in a web browser by navigating to index.html.
2. You will see a cube displayed in the scene.
3. To extrude a face:
   * Click on the desired face of the cube.
4. The cube's vertices will smoothly animate to create the extrusion effect.

## Assumptions
* This implementation assumes a basic understanding of Babylon.js and JavaScript programming.
* I have not used Gizmos object from the babylon
* We have used wireframeMaterial standardmaterial which helps in bounding box.
* We shall find the difference between the two coordinates and find the aspect ratio.
* Then calculate the desired size based on pointer movement.
* Update the box size while maintaining the aspect ratio.

## Resources
[Babylon.js Documentation](https://doc.babylonjs.com/)

## Credits
This project was developed by [Nikhil S Shetty](https://github.com/Nikhilshetty-github). Please feel free to reach out with any questions or feedback.
