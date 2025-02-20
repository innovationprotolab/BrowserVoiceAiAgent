# BrowserVoiceAiAgent

BrowserVoiceAiAgent is a lightweight JavaScript-based AI agent that integrates with your browser through a bookmarklet. With just a click of a button, you can activate voice recognition and perform various actions in your browser using voice commands. This project is designed to make browsing more intuitive and hands-free by leveraging the power of voice recognition and AI.
# Features

    Voice Recognition: Activate voice recognition with a single click.

    AI-Powered Actions: Perform browser actions based on voice commands (e.g., navigation, searching, opening tabs, etc.).

    Bookmarklet Integration: Easy to set up and use directly from your browser's bookmarks.

    Customizable: Add your own custom commands and actions to suit your needs.

# How It Works

    Bookmarklet Setup: Add the provided JavaScript code as a bookmark in your browser.

    Voice Activation: Click the bookmarklet to start voice recognition.

    Voice Commands: Speak commands to perform actions like opening URLs, searching the web, or navigating pages.

    AI Integration: The AI processes your voice input and executes the corresponding browser actions.

# Download

https://www.youtube.com/watch?v=hDZ7gbpLW0g

You can download the JavaScript code directly from this repository or copy it from the installation section below.
# Supported Commands (Examples)

    Open a website: "Open YouTube," "Open Wikipedia."

    Search the web: "Search for AI voice recognition tools."

    Navigate pages: "Go back," "Go forward."

    Custom Commands: Add your own commands by modifying the handleCommand function.

# Customization

You can extend the functionality by adding more commands to the handleCommand function. For example:
javascript
Copy

else if (command.includes('play music')) {
    window.open('https://www.spotify.com', '_blank');
} else if (command.includes('check weather')) {
    window.open('https://www.weather.com', '_blank');
}

# Requirements

    A modern browser with support for the Web Speech API (Chrome, Edge, or Firefox recommended).

    Microphone access enabled.

# Limitations

    Voice recognition accuracy depends on your microphone quality and browser support.

    Commands are currently limited to English (can be modified by changing the recognition.lang property).

# Contributing

Contributions are welcome! If you have ideas for new features or improvements, feel free to open an issue or submit a pull request.
Contact Us

If you have any questions, feedback, or need assistance, feel free to reach out:

    Email: joshojosh7@gmail.com  

    GitHub Issues: innovationprotolab
    

# License

This project is open-source and available under the MIT License.

# Enjoy hands-free browsing with BrowserVoiceAiAgent!
