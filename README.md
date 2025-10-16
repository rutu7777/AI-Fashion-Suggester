# AI-Fashion-Suggester
AI-powered outfit suggestion app that recommends clothing based on weather and user input using React, TensorFlow.js, and OpenAI.

🧰 Tools & Tech
Frontend: React 18 (Vite)

Styling: Tailwind CSS

Local ML: TensorFlow.js, @tensorflow-models/coco-ssd, @tensorflow-models/mobilenet

Backend: Node.js + Express

AI Chat: OpenRouter / OpenAI (via server proxy)

HTTP: axios

Dev helpers: concurrently, dotenv, cors

✨ Key Features
Upload an outfit photo → local image analysis (objects, style, dominant colors).

Weather-aware clothing suggestions (OpenWeatherMap).

AI stylist suggestions and detailed outfit analysis (OpenRouter text API).

Modern responsive UI with cards and quick actions.

Minimal, privacy-preserving setup — image analysis runs locally in the browser.

⚙️ Setup (step-by-step)

Clone Repo

Create .env

-Edit .env and add your keys:
-OPENROUTER_API_KEY=your_openrouter_key
-WEATHER_API_KEY=your_openweathermap_key
-PORT=3001    ( optional )


Install dependencies

npm install

Run (dev) — starts server + frontend

npm start

