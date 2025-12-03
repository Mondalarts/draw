AI Sketch Guessing Game

This is a fun, single-page web application that uses the Gemini API's multimodal capabilities to either guess what you draw (Mode 1) or rate how accurately you drew a specific prompt (Mode 2).

The entire application, including the HTML, CSS (Tailwind CSS), and JavaScript logic, is contained within a single file: index.html.

🚀 Setup and Running Locally

To run this project, you only need two things:

A Gemini API Key

A Web Browser

Step 1: Get Your API Key

Go to the Google AI Studio documentation and obtain a Gemini API key: https://ai.google.dev/gemini-api/docs/api-key

Step 2: Configure the Project

Clone this repository or download the index.html file.

Open the index.html file in a text editor (like VS Code, Notepad++, etc.).

Locate the following section inside the <script> tag:

// --- IMPORTANT: API Configuration for GitHub Deployment ---
// REPLACE "YOUR_GEMINI_API_KEY_HERE" with your actual Gemini API Key.
const apiKey = "YOUR_GEMINI_API_KEY_HERE"; 


Replace "YOUR_GEMINI_API_KEY_HERE" with the key you obtained in Step 1.

Step 3: Launch the Game

Open the modified index.html file directly in your web browser (e.g., Chrome, Firefox) by double-clicking it.

The game is now fully operational!

🎮 How to Play

The game features two modes:

Mode 1: Free Draw & Guess: Draw anything you like, then click "Guess My Drawing." The AI will attempt to identify the object you drew.

Mode 2: Prompted Draw & Rate: The game gives you a challenge word (e.g., "ELEPHANT"). Draw it, click "Submit for Rating," and the AI will critique your drawing and give it a percentage score based on accuracy.

🛠️ Technology Used

HTML5

CSS: Tailwind CSS (loaded via CDN)

JavaScript

Google Gemini API: Used for multimodal vision and language capabilities (gemini-2.5-flash-preview-09-2025) to analyze the canvas drawing.
