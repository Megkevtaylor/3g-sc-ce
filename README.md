# Voiceflow AI Voice Chat

A web-based voice chat interface that integrates with Voiceflow's AI chatbot platform. This application allows users to interact with a Voiceflow chatbot using voice input, creating a seamless voice-based conversation experience.

🔗 **Live Demo:** [https://megkevtaylor.github.io/3g-sc-ce/](https://megkevtaylor.github.io/3g-sc-ce/)

## Features

- Voice input recognition using Web Speech API
- Real-time voice-to-text transcription
- Integration with Voiceflow chatbot
- Visual feedback for voice input status
- Modern and responsive UI
- Cross-browser compatibility (optimized for Chrome)

## Setup

1. Clone this repository:
```bash
git clone https://github.com/Megkevtaylor/3g-sc-ce.git
cd 3g-sc-ce
```

2. Replace the Voiceflow Agent ID in `index.html`:
Find the following line in the code and replace with your Voiceflow Agent ID:
```javascript
ID: "Xs04Hsrstrw7QrH", // Replace with your Agent ID
```

3. Serve the files using a local web server or deploy to your hosting platform.

## Deployment

This project is deployed using GitHub Pages. To deploy your own version:

1. Fork this repository
2. Enable GitHub Pages in your repository settings
3. Select the `gh-pages` branch as the source
4. Your site will be available at `https://[your-username].github.io/3g-sc-ce/`

## Usage

1. Open the webpage in a Chrome browser
2. Click the "Start Voice Input" button
3. Speak your message
4. The transcript will appear on screen and be sent to the Voiceflow chatbot
5. View the chatbot's response in the widget

## Requirements

- Modern web browser (Chrome recommended for best speech recognition support)
- Voiceflow account and Agent ID
- Microphone access

## Technical Details

- Uses Web Speech API for voice recognition
- Integrates with Voiceflow's widget API
- Built with vanilla JavaScript, HTML, and CSS
- No external dependencies required

## License

MIT License

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request 