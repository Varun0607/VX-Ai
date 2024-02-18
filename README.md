# VXAI - Generate 4K Images from Textual Inputs

VXAI is a full-stack web application that allows users to generate 4K images from textual inputs. Users can save these images on their personal wall and download them in JPG format. This project leverages the power of OpenAI's API for image generation.

## Tech Stack

- **Frontend**:
  - ReactJS for building the user interface.
  - Tailwind CSS for styling the application.
  - Vite for fast development and building.

- **Backend**:
  - ExpressJS as the server framework.
  - Node.js for server-side JavaScript.
  - MongoDB as the database for storing user data and image metadata.

## Features

- Generate 4K images from textual inputs using OpenAI's API.
- Save generated images to a personal wall.
- Download generated images in JPG format.
- User authentication and registration.
- Store user-specific data in MongoDB.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Varun0607/VX-Ai.git
2. Navigate to the project directory:

   ```bash
   cd vonai
3. Install dependencies for both the frontend and backend:
  cd client && npm install
  cd ../server && npm install
4.Set up your environment variables:

  Create a .env file in the server directory and configure it with the following variables:
  ```
  PORT=3001
  MONGODB_URI=your-mongodb-connection-string
  OPENAI_API_KEY=your-openai-api-key
```
5.Start the development servers:

In the server directory:
```npm run dev```
In the client directory:
```npm run dev```
6.Your application should now be running on http://localhost:3000.
## Usage

1. Register or log in to your account.
2. Enter a textual description or prompt.
3. Click the "Generate Image" button.
4. View and save the generated image on your personal wall.
5. Download the image in JPG format.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m "Add your feature description"`.
4. Push to your forked repository: `git push origin feature/your-feature-name`.
5. Open a pull request to the main repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was made possible by the OpenAI API.
- Thanks to the MongoDB community for their powerful database solution.
- UI styling was made easier with Tailwind CSS.

## Contact

If you have any questions or feedback, feel free to contact the project creator:

- GitHub: [Varun Sapra](https://github.com/Varun0607)
- Email: varunsapra14@gmail.com

Enjoy generating beautiful images with VXAI!



