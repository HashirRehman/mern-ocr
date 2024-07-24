# MERN OCR Image Text Extraction App

This application is a simple OCR (Optical Character Recognition) tool that allows users to upload an image and input some text. The app uses the Tesseract.js library to extract text from the uploaded image and save the extracted text along with the input text to a MongoDB database.

## Demo Video
Here is a [demo video](client/public/MERN-OCR-SAMPLE.mov) showing the application working.


## Features

- Upload an image and input text.
- Extract text from the uploaded image using Tesseract.js.
- Save the extracted text and input text to a MongoDB database.
- Display the extracted text on the client side.

## Technologies Used

- **Server:**
  - Node.js
  - Express
  - Multer (for handling file uploads)
  - Tesseract.js (for OCR)
  - Mongoose (for MongoDB interaction)
  - CORS (for handling cross-origin requests)
  - File System (fs) module (for file handling)
  
- **Client:**
  - React
  - Axios (for making HTTP requests)


## Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/HashirRehman/mern-ocr
   cd mern-ocr
   ```
2. Install server dependencies:
    ```
   cd server
   npm install
    ```
3. Install client dependencies:
   ```
   cd ../client
   npm install
   ```

### Running the Application

  1. Start MongoDB server (if not already running):
  ```
  mongod
  ```

  2. Start the server:
  ```
  cd server
  node server.js
  ```

  3. Start the client:
  ```
  cd ../client
  npm start
  ```
  4. Open your browser and navigate to http://localhost:3000 to use the application.

### Usage
  1. Upload an image file.
  2. Enter some text in the input field.
  3. Click the "Submit" button.
  4. The extracted text from the image will be displayed on the page.
