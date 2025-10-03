# 🎵 Hume AI Octave 2 Tester

A sleek, minimal HTML interface to test Hume AI's Octave 2 text-to-speech API.

## ✨ Features

- **Clean, modern UI** with gradient background and glassmorphism design
- **Multi-language support** (11 languages including English, Spanish, French, German, etc.)
- **Voice selection** (Male/Female/Default)
- **Speed control** (0.5x to 2.0x)
- **Audio playback** with download option
- **API key persistence** (saved locally)
- **Error handling** with user-friendly messages
- **Responsive design** works on all devices

## 🚀 Quick Start

1. **Get your API key** from [Hume AI](https://hume.ai)
2. **Open** `index.html` in your browser
3. **Enter** your API key (it will be saved locally)
4. **Type** your text and select options
5. **Click** "Generate Speech" and enjoy!

## 🌐 Live Demo

Simply open the `index.html` file in any modern web browser - no server required!

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - no dependencies
- **Fetch API** for HTTP requests
- **Blob handling** for audio file processing
- **LocalStorage** for API key persistence
- **Modern CSS** with flexbox and animations

## 📋 Supported Languages

- English (en)
- Spanish (es)
- French (fr)
- German (de)
- Italian (it)
- Portuguese (pt)
- Japanese (ja)
- Korean (ko)
- Chinese (zh)
- Hindi (hi)
- Arabic (ar)

## 🔧 API Configuration

The tool uses the Hume AI Octave 2 API endpoint:
```
POST https://api.hume.ai/v0/tts/inference
```

Required headers:
- `Authorization: Bearer YOUR_API_KEY`
- `Content-Type: application/json`

## 🎨 Customization

The interface is fully customizable via CSS variables and can be easily themed or extended with additional features.

## 📝 License

MIT License - feel free to use and modify as needed!

---

Built with ❤️ for testing Hume AI's amazing Octave 2 TTS model