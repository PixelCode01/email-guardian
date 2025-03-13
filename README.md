# Email Guardian

Email Guardian is a Chrome extension designed to protect users from phishing emails by scanning links and attachments within popular webmail services like Gmail, Outlook, and Yahoo Mail. This extension leverages AI models and third-party APIs to analyze email content and provide users with a security assessment.

## Features

- **Automatic Email Scanning**: Automatically scans emails for phishing threats and security risks.
- **Real-Time Analysis**: Provides real-time analysis and displays results in an overlay popup.
- **VirusTotal Integration**: Scans links using VirusTotal API to detect malicious URLs.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/PixelCode01/email-guardian.git
   ```
2. Navigate to the project directory:
   ```bash
   cd email-guardian
   ```
3. Load the extension in Chrome:
   - Open Chrome and go to `chrome://extensions/`
   - Enable "Developer mode"
   - Click "Load unpacked" and select the `email-guardian` directory

## Usage

1. Open your webmail service (Gmail, Outlook, Yahoo Mail).
2. The extension will automatically scan emails as you open them.
3. To manually scan an email, click the "Scan Email" button injected into the webmail interface.
4. Review the analysis results displayed in the overlay popup.

## Contributing

We welcome contributions to improve Email Guardian! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Description of your changes"
   ```
4. Push your changes to your fork:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request on the main repository.

## License

This project is currently not licensed. Please contact the repository owner for more information.

## Technologies Used

- **JavaScript**: Core programming language for the extension.
- **Chrome Extensions API**: Used for creating and managing the extension.
- **Gemini AI**: For analyzing email content.
- **VirusTotal API**: For scanning links in emails.

## Contact

For questions or support, please reach out via [GitHub Issues](https://github.com/PixelCode01/email-guardian/issues)
