# Material You NewTab

A beautiful, customizable new tab page browser extension with weather, search, bookmarks, AI tools, and more. Built with Material Design principles and supports 22+ languages.

![Extension Version](https://img.shields.io/badge/version-1.0.0-blue)
![Manifest Version](https://img.shields.io/badge/manifest-v3-green)
![Languages](https://img.shields.io/badge/languages-22+-orange)

## ✨ Features

### 🎨 **Beautiful Material Design Interface**
- Clean, modern Material You design language
- Customizable themes and color schemes
- Dark mode support (experimental)
- Adaptive icon shapes that match your theme
- Responsive design for all screen sizes

### 🔍 **Advanced Search**
- **Multiple Search Engines**: Google, DuckDuckGo, Bing, Brave, YouTube, Reddit, Wikipedia, Quora
- **Smart Search Suggestions**: Real-time autocomplete with CORS bypass proxy support
- **Voice Search**: Built-in speech recognition for hands-free searching
- **Search Mode Switching**: Easy toggle between different search engines
- **Custom Search Shortcuts**: Quick access to your favorite search platforms

### 🌤️ **Weather Integration**
- Real-time weather information with location detection
- GPS support for automatic location updates
- Temperature display (Celsius/Fahrenheit)
- Humidity levels and "feels like" temperature
- Min/Max temperature options
- Weather card customization (hide/show elements)
- WeatherAPI integration with custom API key support

### 📚 **Smart Bookmarks Management**
- Integrated bookmarks sidebar
- Search through bookmarks by name or URL
- Grid and list view options
- Alphabetical and chronological sorting
- Edit bookmarks directly within the extension
- Folder support with expandable navigation

### 🤖 **AI Tools Integration**
Quick access shortcuts to popular AI platforms:
- ChatGPT
- Google Gemini
- Microsoft Copilot
- Claude (Anthropic)
- Perplexity
- DeepSeek
- Meta AI

### 📱 **Google Apps Menu**
One-click access to Google services and applications with customizable shortcuts.

### ✅ **To-Do List**
- Daily task management
- Add, edit, and complete tasks
- Persistent storage across sessions
- Clean, minimal interface

### 🕒 **Digital Clock & Calendar**
- Digital and analog clock options
- 12/24-hour format support
- Date display with day/month localization
- Customizable greeting messages
- Time-based greetings (morning, afternoon, evening)

### 💬 **Motivational Quotes**
Daily inspirational quotes displayed below the search bar to keep you motivated.

### ⌨️ **Keyboard Shortcuts & Navigation**
- Quick search engine switching
- Keyboard navigation through search suggestions
- Customizable shortcut management
- Menu shortcuts for quick access

### 🌍 **Extensive Localization**
Full support for 22+ languages:
- English (en)
- Spanish (es)
- French (fr)
- Portuguese (pt)
- German (de)
- Italian (it)
- Russian (ru)
- Chinese Simplified (zh)
- Chinese Traditional (zh_TW)
- Japanese (ja)
- Korean (ko)
- Hindi (hi)
- Bengali (bn)
- Urdu (ur)
- Arabic (ar)
- Vietnamese (vi)
- Turkish (tr)
- Czech (cs)
- Hungarian (hu)
- Slovenian (sl)
- Nepali (np)
- Marathi (mr)
- Indonesian (idn)
- Uzbek (uz)
- Azerbaijani (az)

### 💾 **Data Management**
- **Backup & Restore**: Export and import your settings
- **Persistent Storage**: All preferences saved locally
- **Privacy-First**: No data collection or tracking
- **Customizable Text**: Add your own custom text below the clock

## 🚀 Installation

### Chrome Web Store (Recommended)
*Coming soon - Submit to Chrome Web Store*

### Manual Installation (Developer Mode)

1. **Download the Extension**
   ```bash
   git clone https://github.com/devrohanshah/browser-extension-newtab.git
   # or download and extract the ZIP file
   ```

2. **Enable Developer Mode**
   - Open Chrome and navigate to `chrome://extensions/`
   - Toggle "Developer mode" in the top right corner

3. **Load the Extension**
   - Click "Load unpacked"
   - Select the extension folder
   - The extension will be installed and activated

4. **Set as New Tab** (if needed)
   - Open a new tab - it should automatically use the extension
   - If not, check that the extension is enabled in `chrome://extensions/`

## 🛠️ Browser Compatibility

- **Google Chrome** - Full support
- **Microsoft Edge** - Full support
- **Chromium-based browsers** - Full support
- **Firefox** - Partial support (some features may be limited)
- **Brave Browser** - Full support

## ⚙️ Configuration

### Weather Setup
1. Open the settings menu (gear icon)
2. Navigate to Weather settings
3. Enter your WeatherAPI key from [WeatherAPI.com](https://www.weatherapi.com/)
4. Optionally set your location manually if GPS is not preferred

### Search Suggestions
1. Enable/disable in the settings menu
2. Configure proxy settings if suggestions aren't working
3. Choose your preferred search engines

### Language Settings
1. Click the language selector in settings
2. Choose from 22+ available languages
3. Interface will update immediately

### Customization
1. **Themes**: Choose from light/dark modes and color schemes
2. **Layout**: Toggle visibility of various components
3. **Text**: Add custom text and greetings
4. **Shortcuts**: Customize which tools and apps are displayed

## 🔧 Technical Details

### Built With
- **HTML5** - Structure and semantic markup
- **CSS3** - Modern styling with Material Design
- **Vanilla JavaScript** - No frameworks, pure JS for performance
- **Manifest V3** - Latest Chrome extension standards
- **Service Workers** - Background functionality

### Key Files
- `manifest.json` - Extension configuration
- `index.html` - Main new tab page
- `style.css` - All styling and themes
- `scripts/` - Modular JavaScript functionality
- `locales/` - Language files for i18n
- `images/` - Icons and graphics

### Permissions Used
- `storage` - Save user preferences
- `bookmarks` - Access browser bookmarks
- `tabs` - New tab functionality
- `activeTab` - Current tab access
- `geolocation` - Weather location services

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Adding Language Support
1. Create a new file in `locales/` (e.g., `your-language.js`)
2. Copy the structure from `locales/en.js`
3. Translate all strings to your language
4. Add the language to `scripts/languages.js`
5. Submit a pull request

### Bug Reports
Please include:
- Browser version and OS
- Steps to reproduce
- Expected vs actual behavior
- Console errors (if any)

### Feature Requests
- Check existing issues first
- Describe the feature clearly
- Explain the use case and benefits

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Weather data provided by [WeatherAPI](https://www.weatherapi.com/)
- Search suggestions powered by various search engine APIs
- Icons and design inspired by Google's Material Design
- Community translations from contributors worldwide

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/devrohanshah/browser-extension-newtab/issues)
- **Discussions**: [GitHub Discussions](https://github.com/devrohanshah/browser-extension-newtab/discussions)
- **Email**: rohankshah345@example.com

## 🗺️ Roadmap

- [ ] Firefox Add-ons store submission
- [ ] Additional search engines
- [ ] More AI tool integrations
- [ ] Calendar integration
- [ ] News feed widget
- [ ] Productivity timers
- [ ] More theme options
- [ ] Mobile browser support

---

**Made with ❤️ for a better browsing experience**

*If you find this extension useful, please consider giving it a ⭐ on GitHub!*
