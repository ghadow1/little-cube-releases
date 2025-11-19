# little-cube-releases
A modern, privacy-focused desktop browser built with Electron and TypeScript. Download and use the newest kit on the block - simple native-ui little-cube browser build on .js and .ts running chromium 122.

## Technology Stack

![Electron](https://img.shields.io/badge/Electron-28.0.0-47848F?logo=electron&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.3.3-3178C6?logo=typescript&logoColor=white)
![Chromium](https://img.shields.io/badge/Chromium-122-4285F4?logo=google-chrome&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-lightgrey)

## Features

**Multi-AI Chat Integration**
- Support for Grok AI, OpenAI, and Claude (Anthropic)
- Unified interface for all AI models
- Conversation history management

**Unified Cloud Key Management**
- Securely manage API keys for multiple AI services
- Centralized key storage and configuration
- Easy switching between AI providers

**Privacy & Security**
- Advanced tracker blocking
- Anti-detection protection
- Browser fingerprint modification
- Per-tab session isolation
- Privacy mode with automatic session clearing

**Developer Tools**
- Native Chrome DevTools integration
- Element inspector
- Network monitor
- Storage viewer
- Console debugging

**Workspace Management**
- Local folder integration
- File browser
- Bookmark management
- Persistent workspace settings

**Customizable Settings**
- Default search engine selection (DuckDuckGo, Google, Bing, Brave, AI models)
- Default AI operator selection
- JavaScript, Images, and Plugins controls
- Popup and tracker blocking
- Download management

## Quick Start

### Prerequisites

- Node.js 18+ and npm
- macOS or Windows

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd little-cube

# Install dependencies
npm install
```

### Development

```bash
# Start in development mode
npm start

# Development with auto-reload
npm run dev
```

### Building

```bash
# Build for macOS
npm run dist:mac

# Build for Windows
npm run dist:win

# Build for all platforms
npm run dist:all
```

For detailed build instructions, see [BUILD.md](./BUILD.md).

## System Requirements

**Operating System:** macOS 10.13+ or Windows 10+

**Architecture:** x64 (Intel/Apple Silicon on macOS)

**Runtime:** Node.js 24

**Engine:** Chromium 122

## Project Information

**Version:** 2.0.0

**License:** MIT

## Documentation

- [Full Documentation](./docs/README.md) - Complete feature documentation
- [Build Guide](./BUILD.md) - Detailed build and distribution instructions
- [Quick Start Guide](./docs/QUICKSTART.md) - Getting started quickly

## Project Structure

```
little-cube/
├── src/
│   ├── main/              # Main process (Electron)
│   │   └── core/         # Core window and tab management
│   ├── renderer/          # Renderer process (UI)
│   │   ├── components/    # UI components (home, chat)
│   │   ├── core/          # Core renderer logic
│   │   └── styles/        # Stylesheets
│   └── preload/           # Preload scripts
├── build/                 # Build assets and icons
├── docs/                  # Documentation
└── dist/                  # Compiled output (generated)
```

## Key Features

### Multi-AI Chat Integration

Access Grok AI, OpenAI, and Claude from a unified interface. Switch between AI models seamlessly, manage conversation history, and configure API keys through the centralized cloud key management system.

### Privacy Protection

Advanced privacy features including tracker blocking, anti-detection protection, browser fingerprint modification, and per-tab session isolation. Privacy mode automatically clears session data on close.

### Workspace Management

Open local folders as workspaces, browse files directly in the browser, and manage bookmarks. Workspace preferences can be saved across sessions.

### Developer Tools

Full Chrome DevTools integration with element inspector, network monitor, storage viewer, and console debugging capabilities.

## Configuration

Settings are managed through the home page interface. Key configuration options include:

- Default search engine
- Default AI operator
- Privacy and security settings
- JavaScript, Images, and Plugins controls
- Workspace and bookmark preferences

## License

MIT License - see LICENSE file for details

## Contributing

Contributions are welcome! Please feel free to submit issues and enhancement requests.
