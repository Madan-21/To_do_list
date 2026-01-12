# To_do_list

A Progressive Web App (PWA) to-do list application with offline functionality, built using HTML, JavaScript, and service workers.

## About

This is a modern to-do list application that works both online and offline. Built as a Progressive Web App, it features service worker caching for improved performance and offline accessibility, allowing users to manage their tasks even without an internet connection.

## Features

- ✅ Create, read, update, and delete tasks
- 📱 Progressive Web App (PWA) - installable on devices
- 🔄 Service Worker implementation for offline functionality
- 💾 Local caching for improved performance
- 📴 Works offline - access your tasks anytime
- 🚀 Fast loading with cache-first strategy
- 📲 Responsive design for all devices

## Tech Stack

- **HTML** (94.7%)
- **JavaScript** (5.3%)

### Key Technologies

- Service Workers - For offline functionality and caching
- Cache API - For storing resources locally
- PWA Manifest - For app installation
- Vanilla JavaScript - No framework dependencies

## Project Structure
```
To_do_list/
├── index.html          # Main HTML file
├── manifest.json       # PWA manifest configuration
├── service-worker.js   # Service worker for caching and offline support
├── sw.js              # Additional service worker functionality
└── README.md          # Project documentation
```

## Installation

1. Clone the repository:
```bash
   git clone https://github.com/Madan-21/To_do_list.git
```

2. Navigate to the project directory:
```bash
   cd To_do_list
```

3. Open `index.html` in your browser or serve it using a local server:
```bash
   # Using Python 3
   python -m http.server 8000
   
   # Or using Node.js with http-server
   npx http-server
```

4. Visit `http://localhost:8000` in your browser

## Usage

1. **Add Tasks**: Enter your task in the input field and click add
2. **Mark Complete**: Click on tasks to mark them as complete
3. **Delete Tasks**: Remove tasks you no longer need
4. **Offline Mode**: The app automatically works offline once you've visited it
5. **Install**: Click the install prompt to add the app to your home screen

## PWA Features

### Service Worker Caching

The application implements cache-busting strategies to ensure:
- Fast initial load times
- Offline functionality
- Automatic updates when online
- Reduced server load

### Manifest Configuration

The `manifest.json` file enables:
- App installation on mobile devices
- Custom app icon and splash screen
- Standalone app experience
- Theme customization

## Recent Updates

- ✨ Fixed caching issues
- 🔧 Improved service worker functionality
- ⚡ Enhanced cache busting mechanism
- 🎯 Better offline experience

## Browser Support

This PWA works on modern browsers that support:
- Service Workers
- Cache API
- PWA Manifest
- ES6+ JavaScript

Recommended browsers:
- Chrome/Edge (Version 80+)
- Firefox (Version 75+)
- Safari (Version 14+)

## Development

To modify the caching strategy or add new features:

1. Edit `service-worker.js` for cache management
2. Update `manifest.json` for PWA configuration
3. Modify `index.html` and JavaScript for UI changes

### Cache Strategy

The app uses a cache-first strategy:
```javascript
// Check cache first, then network
// Falls back to cache if offline
```

## Deployment

The app is deployed on GitHub Pages and has 12 successful deployments.

**Live Demo**: [View on GitHub Pages](https://madan-21.github.io/To_do_list/)

### Deploy Your Own

1. Push your code to GitHub
2. Go to repository Settings
3. Navigate to Pages section
4. Select the branch to deploy
5. Your site will be live at `https://yourusername.github.io/To_do_list/`

## Future Enhancements

- [ ] Add task categories/tags
- [ ] Implement due dates and reminders
- [ ] Add task priority levels
- [ ] Include task search and filter
- [ ] Add data synchronization across devices
- [ ] Implement user authentication
- [ ] Add task collaboration features
- [ ] Include statistics and productivity insights

## Known Issues

- Cache busting was improved in recent commits
- Service worker updates require page refresh

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## License

This project is open source and available under the MIT License.

## Author

**Madan-21**

## Acknowledgments

- Service Worker API documentation
- PWA best practices from Google
- MDN Web Docs for offline functionality guides

---

*Built with 📝 to make task management accessible anywhere, anytime*
