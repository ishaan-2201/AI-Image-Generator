# AI Image Generator

This project is an AI Image Generator application built using React. It allows users to generate images based on textual descriptions using the OpenAI API.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [License](#license)

## Features

- User-friendly interface to input descriptions.
- Image generation based on user prompts using OpenAI's image generation API.
- Loading indicator while images are being generated.
- Default image displayed before generation.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **OpenAI API**: Used for generating images based on text prompts.
- **CSS**: For styling the application.

## Getting Started

To get a local copy up and running, follow these steps:

1. **Clone the repository :**

   ```bash
   git clone https://github.com/yourusername/AI-Image-Generator.git
   cd AI-Image-Generator
   ```

2. **Install dependencies :**

   ```bash
   npm install
   ```

3. **Create a .env file in the root directory and add your OpenAI API key :**

   ```bash
   VITE_API_KEY=your_openai_api_key_here
   ```

4. **Start the development server :**

   ```bash
   npm run dev
   ```

5. **Open your browser and go to http://localhost:3000 to view the application.**

## Usage

1. Type a description of the image you want to generate in the input field.

2. Click the "Generate" button.

3. Wait for the loading indicator to disappear and view your generated image.

## Environment Variables

Make sure to include the following environment variable in your .env file:

```bash
VITE_API_KEY: Your OpenAI API key.
```
