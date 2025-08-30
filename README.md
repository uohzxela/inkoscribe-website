# inkoscribe Website

This repository contains the official website for [inkoscribe](https://inkoscribe.com) - a private, local audio transcription tool for macOS.

## About inkoscribe

inkoscribe provides real-time speech-to-text transcription that runs entirely on your Mac. No cloud uploads, no servers, complete privacy.

### Key Features
- **100% Private**: Your voice data never leaves your Mac
- **Real-time**: Instant, word-by-word transcription as you speak
- **Easy Installation**: Ready to use in seconds with Homebrew
- **macOS Optimized**: Designed for macOS 13+ (M1, M2, M3+)

## Installation

```bash
brew tap uohzxela/inkoscribe
brew install inkoscribe
```

## Usage

**System Audio** (for meetings, calls, videos):
```bash
inkoscribe -s sys
```

**Microphone** (for your voice):
```bash
inkoscribe -s mic
```

## Website Development

This is a static HTML website hosted at [inkoscribe.com](https://inkoscribe.com).

### Local Development

Simply open `index.html` in your browser to view the website locally.

### Deployment

The website is automatically deployed when changes are pushed to the main branch.

## Contact

- **Author**: [Alex Jiao](https://uohzxela.github.io/)
- **Email**: uohzxela@gmail.com
- **Main Project**: [github.com/uohzxela/inkoscribe](https://github.com/uohzxela/inkoscribe)

## License

© 2025 Alex Jiao
