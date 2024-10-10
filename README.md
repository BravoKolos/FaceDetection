# Face Detection App

## Overview
This application utilizes the (https://www.clarifai.com/) to detect faces in images. Built with Node.js, the app allows users to upload images, and it processes these images to identify and display detected faces.

## Features
- Upload images for face detection
- Display detected faces with bounding boxes
- Simple user interface for easy interaction

## Technologies Used
- **Node.js**: JavaScript runtime for server-side programming.
- **Express.js**: Web framework for Node.js to build web applications.
- **Clarifai API**: A powerful API for image and video recognition.
- **Knex**: Used for database interactions, such as creating tables, inserting records, and running queries.
- **body-parser**: Helps to handle different types of requests, such as JSON and URL-encoded data.
- **bcrypt-nodejs**: Used for hashing user passwords before storing them in a database to ensure security.
- **cors**: Frontend and Backend communication
- **HTML/CSS**: For the frontend user interface.
- **node-fetch**: Interact with the Clarifai API, to send images for processing.

## Getting Started

### Prerequisites
- Node.js - (https://nodejs.org/) (version 14 or higher)
- NPM - (https://www.npmjs.com/) (Node package manager)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/BravoKolos/FaceDetection.git
   cd FaceDetection
