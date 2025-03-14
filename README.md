# DusGPT

A responsive web-based clone of Google's Gemini AI interface with chat functionality, markdown support, and code highlighting.

## Features

- **Real-time Chat Interface**

  - Dynamic message loading
  - Typing effect for responses
  - Loading animations
  - Chat history persistence

- **Theme Support**

  - Light/Dark mode toggle
  - Theme persistence across sessions
  - Smooth theme transitions

- **Code Handling**

  - Syntax highlighting for multiple languages
  - Code block copy functionality
  - Language label display
  - Code formatting

- **Markdown Support**

  - Full markdown rendering
  - Support for tables, lists, and blockquotes
  - Inline code formatting
  - Links and emphasis

- **User Interface**
  - Responsive design
  - Suggestion prompts
  - Clear chat functionality
  - Error handling
  - Custom scrollbar

## Technologies Used

- **Frontend**

  - HTML5
  - CSS3
  - Vanilla JavaScript

- **External Libraries**
  - [Highlight.js](https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github-dark.min.css) - Code syntax highlighting
  - [Boxicons](https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css) - Icon pack
  - [Marked](https://cdn.jsdelivr.net/npm/marked/marked.min.js) - Markdown parsing

## Setup

1. Clone the repository

```bash
git clone <repository-url>
```

2. Add your Google API Key

```javascript
const GOOGLE_API_KEY = "your-api-key-here";
```

3. Open `index.html` in your browser

## Project Structure

```
├── assets/
│   ├── gemini.svg
│   └── profile.png
├── index.html
├── style.css
├── script.js
└── README.md
```

## API Integration

The project uses Google's Gemini API for generating responses:

```javascript
const API_REQUEST_URL = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${GOOGLE_API_KEY}`;
```

## Local Storage

The application stores:

- Chat history
- Theme preference
- User settings

## Responsive Design

- Desktop-first approach
- Mobile-friendly interface
- Breakpoint at 980px
- Adaptive suggestion boxes

## License

[Add your license information here]

## Credits

- Design inspired by Google's Gemini AI
- Icons by [Boxicons](https://boxicons.com/)
- Font: Open Sans from Google Fonts

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## Known Issues

- MIIT

## Future Improvements

- Voice input support
- Image recognition
- Multiple conversation threads
- Export chat history
- Custom themes

---

**Note:** This is a clone project created for educational purposes only.
