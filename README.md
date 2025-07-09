# Leads Tracker Chrome Extension

A simple and efficient Chrome extension that helps you save important URLs (leads) for later reference. Save the current tab or manually input URLs, and access them anytime with just a click.

![Extension Icon](icon.png)

## Features

- Save current tab URL with one click
- Manually input and save URLs
- Persistent storage using Chrome's local storage
- Clean and intuitive user interface
- Quick access to saved leads in new tabs
- Double-click to delete all saved leads

## Installation

1. Clone this repository:
```bash
git clone [your-repository-url]
cd [repository-name]
```

2. Install dependencies:
```bash
npm install
```

3. Build the project:
```bash
npm start
```

4. Load the extension in Chrome:
   - Open Chrome and navigate to `chrome://extensions/`
   - Enable "Developer mode" in the top right
   - Click "Load unpacked" and select the extension directory

## Usage

1. Click the extension icon in your Chrome toolbar
2. To save the current tab: Click "SAVE TAB"
3. To manually save a URL: Enter the URL in the input field and click "SAVE INPUT"
4. To delete all saved leads: Double-click "DELETE ALL"
5. Click any saved URL to open it in a new tab

## Development

This project uses:
- Vanilla JavaScript
- Chrome Extensions API
- Vite for building

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request