# AI Jukebox

AI JukeBox is an intelligent music player that delivers personalized song recommendations based on user emotions, moods, and preferences. Powered by Spotify's API, Google Gemini LLM, and advanced sentiment analysis, it transforms music discovery into an interactive and conversational experience.

Features:

Emotion-Based Recommendations: Suggests songs and playlists aligned with the user's emotional state and mood.

Chatbot DJ: Natural language chatbot interface for conversational music selection and control.

Automated Playlist Generation: Creates, updates, and manages Spotify playlists based on mood, activity, or listening history.

Secure Spotify Integration: Uses OAuth 2.0 to fetch real-time Spotify data like liked songs, playlists, and playback history.

Tech Stack:
Frontend: React.js, HTML, CSS, Tailwind CSS, JavaScript

Backend: Flask (Python), Node.js (Express.js)

APIs: Spotify API, Google Gemini (LLM), Sentiment Analysis Tools

Authentication: OAuth 2.0 (Spotify)

Database: Corpus of user preferences to refine recommendations through continuous learning and adaptive logic.

How It Works:
Authenticate via Spotify OAuth 2.0 to securely access user data.

Interact via Chatbot using natural language commands like:

“Play some relaxing music for studying”
“Generate a happy mood playlist”

Recommendation Engine processes input using LLM and sentiment analysis to curate playlists.

Manage Playlists directly in your Spotify account with AI-curated suggestions.

Continuous Learning: The system refines recommendations based on user feedback and listening patterns.
