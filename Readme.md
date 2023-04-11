![Alt text](client/src/assets/banner.png)

Dinna Dall-E is a web application that allows users to create new images using OpenAI's Dall-E model. The application uses Cloudinary to store and serve the images, and Tailwind CSS for a modern and minimal design. The front-end of the application was built with React using Vite, while the back-end was built with Node.js using Express and MongoDB for the database.


### Demo

You can view a live demo of this project [here](https://dinna-dall-e-nine.vercel.app/).

## Installation

To install and run the project on your local machine, follow these steps:

1.  Clone the repository: `git clone https://github.com/username/dalle.git`
2.  Install dependencies for the front-end: `cd dalle && npm install`
3.  Start the front-end development server: `cd client && npm run dev`
4.  Initialize an empty package.json file in server: `cd server && npm init -y` 
5.  Install dependencies for the back-end: `npm install cloudinary cors dotenv express mongoose nodemon openai`
6.  Add ``"type": "module"``
7.  Add in scripts: ``"start": "nodemon index"``
8.  Start the back-end server: `npm start`

Note: Make sure to create a `.env` file in the `server` directory and add your own MongoDB URL, OpenAI API key, and Cloudinary credentials.

## Features

-   Dynamic image layout
-   Modern and minimal design with hover effect showcasing user's prompt, their name, and download button
-   Search functionality
-   New images generated through "Surprise Me" button
-   Integration with OpenAI API to generate new images
-   Cloud-based image storage and serving through Cloudinary
-   Responsive design with Tailwind CSS
-   File-saving functionality using the FileSaver package

## Dependencies

-   cloudinary
-   cors
-   dotenv
-   express
-   mongoose
-   nodemon
-   openai
-   react
-   react-dom
-   react-router-dom
-   tailwindcss
-   vite


### Known Issues

-   There is an issue where the generated images are not displayed on the home page after sharing it to the community.


## License

This project is licensed under the MIT License. 