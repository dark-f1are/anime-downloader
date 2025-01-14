# Anime Downloader 🎬

A modern web application for searching and downloading anime episodes with a clean, responsive UI and comprehensive error handling.

## ✨ Key Features

- 🎯 Smart search with instant results
- 🌐 Proxy support for reliable downloads
- 📺 Multiple resolution options (1080p, 720p, 480p, 360p)
- 💾 Download options:
  - Individual episode downloads
  - Batch download capability
  - Copy links to clipboard
  - Export links to text file
- 🔄 Progress tracking with visual feedback
- 🔁 Automatic retry mechanism for failed downloads
- 📱 Fully responsive design
- 🌙 Dark theme UI with glass morphism effects
- 💨 Cache system for faster repeated searches
- ⚡ Concurrent downloads for better performance

## 🚀 Technical Features

- 🛠️ Vanilla JavaScript with modern ES6+ features
- 🎨 CSS Variables for easy theming
- 🔋 Local storage caching
- 🌐 CORS-aware proxy implementation
- 🔄 Async/await for clean asynchronous code
- 🎯 Rate limiting and request queuing
- 🎭 Error boundary and comprehensive error handling
- 📱 Mobile-first responsive design
- 🔍 Smart search with debouncing
- 💾 Efficient state management

## 🎮 Usage Guide

1. **Search for Anime**
   - Enter the anime title in the search box
   - Select from search results with cover images
   - View detailed anime information

2. **Configure Download**
   - Set episode range (start & end)
   - Choose preferred resolution
   - Select download method:
     - `Get Links`: View individual episode links
     - `Download All`: Start batch download
     - `Copy Links`: Copy to clipboard
     - `Export Links`: Save as text file

3. **Download Management**
   - Track download progress with visual indicator
   - Retry failed downloads individually
   - View resolution availability for each episode
   - Monitor proxy server status

## 🛡️ Error Handling

- Comprehensive error tracking per episode
- Visual feedback for failed downloads
- Automatic retry mechanism
- Proxy status monitoring
- Network error recovery
- Invalid input validation

## 📱 Responsive Design

- Adapts to all screen sizes
- Mobile-optimized interface
- Touch-friendly controls
- Optimized layouts for tablets
- Performance considerations for mobile devices

## 💾 Caching System

- Search results caching
- Download links caching
- Cache expiration management
- Storage optimization
- Automatic cache cleanup

## ⚠️ Important Notice

**Note:** Episodes of any anime released after **November 24, 2024** will not be available for download through this tool. Please check for updates or alternative sources for newer episodes.

## ❓ FAQ

### Technical Questions

**Q: Why are some episodes not downloading?**
A: This could be due to:
- Server availability
- Network connection issues
- Browser download restrictions
- CORS policy limitations

Try again later or check your network and browser settings.

**Q: Why isn't the "Download All" button working on my mobile device?**
A: Many mobile browsers automatically block popups for security reasons. To resolve this:
1. Enable popups in your browser settings
2. Use the "Export Links" button instead and download using an external downloader
3. Consider using the desktop version for batch downloads

**Q: What browsers are supported?**
A: The tool works best with:
- Google Chrome (recommended)
- Mozilla Firefox
- Microsoft Edge
- Safari (latest versions)

### Usage Questions

**Q: Can I download multiple episodes at once?**
A: Yes, you can:
1. Use the "Download All" button for batch downloads
2. Export all links to a text file for external downloaders

**Q: How do I report issues?**
A: You can:
1. Open an issue on GitHub
2. Include error messages and screenshots
3. Describe the steps to reproduce the problem

**Q: Is there a limit to how many episodes I can download?**
A: While there's no hard limit, we recommend downloading in smaller batches (10-20 episodes) for better reliability.

## ⚠️ Important Notes

- Requires modern browser with JavaScript enabled
- Some features need popup permissions
- Download speed depends on network connection
- Proxy server availability affects functionality
- Mobile browsers may limit concurrent downloads

## 👤 Author

**Dark Flare**
- GitHub: [@dark-f1are](https://github.com/dark-f1are)
- Live Demo: [Anime Downloader](https://dark-f1are.github.io/anime-downloader/)

---

⭐ Star this repo if you find it helpful!
