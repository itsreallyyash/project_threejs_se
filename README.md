
# Project Three.js SE

## Overview

This repository contains the source code for a 3D visualization project built using Three.js, enhanced with OpenAI's DALL·E 2 API. The project demonstrates the capabilities of WebGL, Three.js, and AI-generated images by creating an interactive 3D environment where users can explore AI-generated art.

## Features

- **Interactive 3D Models**: Render and interact with 3D models in real-time.
- **AI-Generated Art**: Integrates with OpenAI's DALL·E 2 API to generate and display AI-created images within the 3D environment.
- **Responsive Design**: Works seamlessly across different screen sizes and devices.
- **Customizable Scenes**: Allows for the customization of lighting, camera angles, and model positioning.
- **User Interaction**: Includes mouse and touch controls for zooming, rotating, and panning the 3D environment.

## Tech Stack

### Front-End

- **HTML5**: Provides the structure for the application.
- **CSS3**: Used for styling the user interface and ensuring responsiveness.
- **JavaScript (ES6+)**: Powers the interactivity and 3D rendering logic.
- **Three.js**: A JavaScript library that simplifies the creation of 3D graphics using WebGL.
- **Webpack**: Used to bundle JavaScript modules for efficient loading and execution.

### Back-End

- **Node.js**: The runtime environment that powers the server-side operations.
- **Express.js**: A web application framework for Node.js, used to manage server routes and API interactions.
- **MongoDB (optional)**: A NoSQL database for storing user data, AI-generated images, and other relevant information.

### APIs

- **OpenAI DALL·E 2 API**: Used to generate images based on user prompts, which are then displayed within the 3D environment.

## Installation & Setup

To get the project up and running on your local machine, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/itsreallyyash/project_threejs_se.git
   cd project_threejs_se
   ```

2. **Install Dependencies**:
   Ensure that Node.js and npm are installed on your machine. Then, install the project dependencies:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root of your project and add the following variables:
   ```bash
   OPENAI_API_KEY=your_openai_api_key
   MONGO_URI=your_mongo_connection_string (if using MongoDB)
   SESSION_SECRET=your_session_secret_key
   ```

4. **Run the Development Server**:
   Start the development server to view the project locally:
   ```bash
   npm run dev
   ```

5. **Access the Project**:
   Open your web browser and navigate to `http://localhost:8080` to view the 3D environment.

## Usage

Once the project is running locally:

- **Explore the Scene**: Use your mouse or touch controls to interact with the 3D scene.
- **Generate AI Art**: Input prompts into the system to generate images using the DALL·E 2 API. These images can be displayed as textures on 3D objects or as standalone elements in the scene.
- **Modify Settings**: Customize the scene by changing lighting, camera angles, or adding/removing objects.

## File Structure

- **`/src`**: Contains the main source code for the project.
  - **`index.html`**: The main HTML file.
  - **`style.css`**: CSS styles for the project.
  - **`main.js`**: The primary JavaScript file where Three.js is initialized and configured.
  - **`dalle.js`**: Handles the interaction with the OpenAI DALL·E 2 API.
- **`/models`**: A directory for storing 3D models used in the project.
- **`/textures`**: Contains any texture files applied to the 3D models, including AI-generated images.
- **`/dist`**: The compiled output from Webpack, ready for production deployment.


1. **Fork the repository**.
2. **Create a new branch** for your feature or bugfix (`git checkout -b feature/YourFeature`).
3. **Commit your changes** (`git commit -m 'Add some feature'`).
4. **Push to the branch** (`git push origin feature/YourFeature`).
5. **Open a Pull Request** to the `main` branch.

Please ensure your code adheres to the project's coding standards and includes relevant tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
