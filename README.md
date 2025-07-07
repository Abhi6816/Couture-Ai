CoutureAI - AI-Powered Fashion Design Generator
CoutureAI is an AI-based fashion design tool that transforms natural language clothing descriptions into stylish and realistic outfit images. It is powered by the FLUX.1-dev model from Black Forest Labs (via Hugging Face Inference API) and built using Node.js for backend and HTML/CSS/JS for frontend.

FEATURES:
Generate fashion images from text descriptions using AI
Beautiful, responsive, and modern frontend UI
Loader animation for better user experience
Download option for generated images
Integrated with Hugging Face's FLUX.1-dev model
Uses Node.js (Express) to manage API requests

HOW IT WORKS:
User enters a fashion prompt (e.g., "White dress with gold chain straps and cowl neck").
The prompt is sent via a POST request from the frontend to the backend.
Backend sends the prompt to Hugging Face's model using the Inference API.
The generated image is received and displayed on the webpage.
User can download the image if desired.

TECHNOLOGIES USED:
Frontend:
HTML5
CSS3
JavaScript

Backend:
Node.js
Express.js

AI Model:
FLUX.1-dev by Black Forest Labs (via Hugging Face API)

INSTALLATION & SETUP:

Clone this repository:
git clone https://github.com/your-username/coutureai.git
cd coutureai

Install dependencies:
npm install express node-fetch cors

Create a .env file in the root directory and add:
HF_API_KEY=your_huggingface_api_key

Start the server:
node server.js
Open index.html in your browser to access the frontend.

SAMPLE PROMPTS:

A white flowy dress with gold chain straps and modest neckline
A knee-length frock with cowl neck and loose fit
An elegant red velvet gown with a high neckline and open back
