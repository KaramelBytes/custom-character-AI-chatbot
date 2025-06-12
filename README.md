# custom-character-AI-chatbot

[![Built with Claude 4](https://img.shields.io/badge/Built_with-Claude_4-FF7F3F?style=flat&logo=anthropic&logoColor=white)](https://claude.ai)
[![Developed with SWE-1](https://img.shields.io/badge/Developed_with-SWE--1-FF7F3F?style=flat&logo=openai&logoColor=white)](https://openai.com)
[![Debugged with o3](https://img.shields.io/badge/Debugged_with-o3-FF7F3F?style=flat&logo=openai&logoColor=white)](https://openai.com)
[![Crafted in Windsurf](https://img.shields.io/badge/Crafted_in-Windsurf-0084FF?style=flat&logo=windsurf&logoColor=white)](https://windsurf.ai)

A vibe-coded, lightweight, single-file web application for creating and chatting with AI-powered characters. Built with vanilla JavaScript and Google's Gemini AI, this application runs entirely in the browser with no server required.

## Purpose
This repository is a demo and exploration of creating a custom AI character chatbot app. It’s not a template for mass adoption or open-source collaboration—just a public display of what happens when you let vibes (and AI) guide your coding.

> **Not accepting contributions or issues.** If you vibe with it, fork away and make it your own!

## ✨ Features

### 🎨 Theme Support
- **System-Aware** - Automatically matches your system's light/dark mode preference
- **Manual Toggle** - Switch between themes with the button in the top-right corner
- **Persistence** - Your theme preference is saved between sessions
- **Accessibility** - High contrast and readability in both modes

- **Single HTML File** - No installation or build process needed
- **Modern UI** - Clean, minimalist sci-fi glassmorphism design
- **Character Creation** - Create and customize your own AI characters with avatars
- **Persistent Storage** - Characters and conversations are saved in your browser's localStorage
- **Responsive Design** - Works on desktop and mobile devices
- **Offline Capable** - Basic functionality works without an internet connection
- **Google AI Integration** - Powered by Google's Gemini AI (API key required)
- **Graceful Degradation** - Falls back to simple responses when API is unavailable
- **Smooth Animations** - Enjoy fluid transitions and interactions
- **Message Timestamps** - See when messages were sent with relative time display
- **Avatar Support** - Upload custom avatars for your characters
- **Dark/Light Mode** - Beautiful theme support that respects system preferences
- **Accessibility** - Improved contrast and readability in both light and dark modes

## 🚀 Getting Started

1. **Get a Google AI API Key**
   - Visit [Google AI Studio](https://makersuite.google.com/app/apikey) and sign in
   - Create a new API key
   - Copy your API key

2. **Configure the Application**
   - Open `character-chatbot.html` in a text editor
   - Find the line with `key: 'YOUR_GOOGLE_API_KEY_HERE'` (around line 1250)
   - Replace the placeholder with your actual API key
   - Save the file

3. **Open in Browser**
   - Double-click the HTML file or open it in your preferred web browser
   - No web server required - it works with the `file://` protocol
   - Look for the "Setup Required" notice in the top-right corner to verify your API key is working

## 🛠️ Usage

### Creating a Character
1. Click the "+ Add Character" button in the sidebar
2. Fill in the character details:
   - **Name**: Your character's name (required)
   - **Species**: Your character's species (e.g., Human, Elf, Robot)
   - **Personality**: Key personality traits (e.g., "Friendly, curious, and adventurous")
   - **Description**: Detailed background, appearance, and characteristics
   - **Greeting**: How the character introduces themselves
   - **Fallback Responses**: Optional alternative responses when AI is unavailable (one per line)
   - **Avatar**: Upload a square image (optional, under 100KB)
3. Click "Create Character"

### Chatting with Characters
1. Select a character from the sidebar
2. Type your message in the input field at the bottom and press Enter or click "Send"
3. The AI will respond in character based on your input
4. The conversation will be saved automatically

### Managing Characters
- **Switch Characters**: Click any character in the sidebar to switch conversations
- **Create New Characters**: Use the "+ Add Character" button to create more characters
- **Character Cards**: Each character is displayed with their avatar (or initials) and key details
- **Conversation History**: Each character maintains their own conversation history

## 🎨 UI/UX Features

- **Glassmorphism Design**: Modern, semi-transparent UI elements with blur effects
- **Responsive Layout**: Works on all screen sizes
- **Smooth Animations**: Subtle transitions for a polished feel
- **Visual Feedback**: Clear indicators for loading states and interactions
- **Dark Theme**: Easy on the eyes for extended use

## 🔧 Technical Details

- **Storage**: All data is saved in the browser's localStorage
- **No Backend**: Runs entirely client-side with no server required
- **File Size**: Single HTML file under 200KB
- **Dependencies**: None (vanilla JavaScript)
- **Browser Support**: Works in all modern browsers (Chrome, Firefox, Safari, Edge)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).