# Gemini 2.0 Flash Multimodal Live API Client

A desktop Electron application implementing the Gemini 2.0 Flash Multimodal Live API client. This project provides real-time interaction with Gemini's API through text, audio, video, and screen sharing capabilities.

This started as a simplified version of [Google's original React implementation](https://github.com/google-gemini/multimodal-live-api-web-console), created in response to [this issue](https://github.com/google-gemini/multimodal-live-api-web-console/issues/19), and has evolved into a desktop application written in Electron.

## Live Demo on GitHub Pages

[Live Demo]([https://viaanthroposbenevolentia.github.io/gemini-2-live-api-demo/](https://jayreddin.github.io/gemini-2-live-electron/client/index.html))

## Key Features

- Real-time chat with Gemini 2.0 Flash Multimodal Live API
- Real-time audio responses from the model
- Real-time audio input from the user, allowing interruptions
- Real-time video streaming from the user's webcam
- Real-time screen sharing from the user's screen
- Function calling
- Native desktop application built with Electron
- Cross-platform support (Windows, macOS, Linux)
- Mobile-friendly web interface

## Prerequisites

- Node.js 18 or higher
- Yarn package manager
- Google AI Studio API key

## Quick Start

1. Get your API key from Google AI Studio
2. Clone the repository

   ```bash
   git clone https://github.com/ViaAnthroposBenevolentia/gemini-2-live-electron.git
   ```

3. Install dependencies:

   ```bash
   cd gemini-2-live-electron
   yarn install
   ```

4. Start the application:

   ```bash
   yarn start
   ```

5. For production build:

   ```bash
   yarn build:win # or build:mac or build:linux
   ```

## Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.

## License

This project is licensed under the MIT License.
