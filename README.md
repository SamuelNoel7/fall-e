# DALL-E Image Generation Application

![DALL-E Image Generation]

Welcome to the DALL-E Image Generation Application! This project showcases a web application built using the MERN (MongoDB, Express, React, Node.js) stack. With the power of the DALL-E model and an open API key, users can enter prompts, and the application will generate corresponding images, displaying them on the frontend page.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- Enter prompts in the application.
- Utilize the DALL-E model to generate images based on prompts.
- Display generated images on the frontend page.
- Seamless integration of the MERN stack for a responsive and interactive experience.

## Technologies Used

- **Frontend**: React, HTML, CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **External API**: DALL-E API (Open API Key)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/dalle-image-generation-app.git
   cd dalle-image-generation-app
   ```

2. Install the frontend dependencies:

   ```bash
   cd client
   npm install
   ```

3. Install the backend dependencies:

   ```bash
   cd ../server
   npm install
   ```

4. Set up your MongoDB database and obtain the DALL-E API key.

5. Create a `.env` file in the `server` directory and add the following:

   ```env
   MONGODB_URI=your_mongodb_connection_string
   DALL_E_API_KEY=your_dall_e_api_key
   ```

6. Start the backend server:

   ```bash
   npm start
   ```

7. Start the frontend development server:

   ```bash
   cd ../client
   npm start
   ```

## Usage

1. Open your web browser and navigate to `http://localhost:3000`.

2. Enter prompts in the input field and submit them.

3. The application will use the DALL-E model to generate images based on your prompts.

4. Enjoy the creatively generated images displayed on the frontend page!


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

