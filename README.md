DoctorGuide - AI-Powered Wellness
DoctorGuide is a modern, premium web platform that leverages Google's Gemini AI to match patients with the most suitable medical specialists based on their symptoms.

🚀 Getting Started
Prerequisites
Node.js (v18 or higher recommended)
npm or yarn
Installation
Clone the Repository

git clone [repository-url]
cd DoctorGuide
Install Dependencies

npm install
🔑 Setting up Gemini AI
This project requires a Google Gemini API Key to function correctly.

Go to Google AI Studio and create a free API Key.
In the project root directory, create a file named .env.
Add your API key to the .env file:
VITE_GENAI_API_KEY=your_actual_api_key_here
🏃 Running Locally
Start the development server:

npm run dev
The application will be available at http://localhost:5173.

📂 Project Structure
src/
├── Components/    # Reusable UI components (NavBar, Footer)
├── Pages/         # Main page views (Home, Doctors, Suggest, Appointment)
├── Slicer/        # Redux state management (DoctorSlicer)
├── Utils/         # Utility functions (AI integration logic)
├── assets/        # Static assets
└── index.css      # Global styles and Tailwind design system
🛠️ Tech Stack
Frontend: React 18, Vite
Styling: Tailwind CSS v4 (with custom glassmorphism system)
State Management: Redux Toolkit
AI Engine: Google Generative AI (Gemini 2.0 Flash)
Icons: Lucide React
Notifications: React Toastify
🩺 Features
AI Triage: Describe symptoms in natural language and get matched with a specialist.

Expert Directory: Browse verified doctors with rich profiles and detailed descriptions.

Smart Booking: Select time slots and request appointments instantly.

Robust Error Handling: Real-time feedback via toast notifications for API and form issues.

Author : Manish Dange 
