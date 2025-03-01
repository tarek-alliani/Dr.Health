# Dr.Health - Medical Image-Analysis & Chat

Analyzing medical images and providing health-related advice. This app allows users to upload images (e.g., X-rays, MRI scans, or even fridge contents) and receive AI-generated insights or meal suggestions based on the uploaded content.

---

## Features
- **Image Analysis**: Upload medical or food-related images for AI-based analysis.
- **Health Advice**: Get AI-generated responses to health-related questions.
- **Dark/Light Mode**: Toggle between themes for better user experience.
- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop.
- **Real-Time Chat**: Interactive chat interface with message history.

---

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **AI Integration**: Google Gemini API (`gemini-1.5-flash`)
- **Styling**: CSS Variables for dynamic theming
- **Deployment**: Static web hosting (e.g., GitHub Pages, Netlify, Vercel)

---

## How It Works
1. Users can:
   - Type health-related questions.
   - Upload images (e.g., medical scans, fridge contents).
2. The app sends the input to Google's Gemini API.
3. The AI analyzes the input and provides:
   - Health advice for medical images.
   - Meal suggestions for fridge images.
4. Responses are displayed in a chat-like interface.

---

## Setup Instructions
1. Clone the repository:
```bash
git clone https://github.com/tarek-aliani-1/Dr.Health.git
```
2. Replace API_KEY in the script with your Google Gemini API key:
```javascript
const API_KEY = 'your-api-key-here';
```
3. Open index.html in your browser or deploy to a static hosting service.

## Features
### Light/Dark Mode
### Image Analyse
### Professional Health Ai
### Multi-language support

## License
This project is licensed under the MIT License. See LICENSE for details.
