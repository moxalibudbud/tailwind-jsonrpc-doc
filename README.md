# API Documentation

A modern, responsive API documentation site built with Tailwind CSS and shadcn design system. This documentation covers a JSON-RPC 2.0 API with comprehensive method descriptions, parameters, examples, and error handling.

## Features

- 🔍 **Live Search** - Instantly search through API methods and descriptions
- 📱 **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- 🎨 **Modern UI** - Clean interface using Tailwind CSS and shadcn design patterns
- 📖 **Comprehensive Coverage** - Detailed documentation for all API endpoints
- ⚡ **Fast Performance** - Static HTML with vanilla JavaScript, no heavy frameworks

## API Methods Covered

### Session Management
- `Session.Login` - Authenticate users and create sessions
- `Session.Logout` - End user sessions securely

### User Management
- `User.Add` - Create new user accounts
- `User.Update` - Modify existing user information
- `User.Delete` - Remove user accounts
- `User.Get` - Retrieve user details
- `User.List` - Get paginated user listings

### System Operations
- `System.GetInfo` - Retrieve system information and status

## Getting Started

### Local Development

1. Clone this repository:
   \`\`\`bash
   git clone https://github.com/yourusername/api-documentation.git
   cd api-documentation
   \`\`\`

2. Open `index.html` in your browser or serve it with a local server:
   \`\`\`bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   \`\`\`

3. Navigate to `http://localhost:8000` to view the documentation

### GitHub Pages Deployment

This site is automatically deployed using GitHub Pages. Any changes pushed to the `main` branch will be reflected on the live site.

**Live URL:** `https://yourusername.github.io/api-documentation`

## Project Structure

\`\`\`
├── index.html          # Main documentation page
├── README.md          # This file
└── assets/           # (Optional) Additional assets like images or fonts
\`\`\`

## Customization

### Styling
The documentation uses Tailwind CSS for styling. Key design elements:
- **Colors:** Blue primary theme with proper contrast ratios
- **Typography:** System font stack for optimal readability
- **Layout:** Responsive sidebar navigation with main content area

### Adding New Methods
To add new API methods:

1. Add a new navigation item in the sidebar:
   \`\`\`html
   <a href="#method-name" class="block px-3 py-2 text-sm text-gray-700 hover:bg-gray-100 rounded-md">
     Method.Name
   </a>
   \`\`\`

2. Add the method documentation in the main content area following the existing pattern

### Search Functionality
The search feature automatically indexes:
- Method names
- Method descriptions
- Parameter names and descriptions
- Error codes and messages

## Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-method`)
3. Commit your changes (`git commit -am 'Add new API method'`)
4. Push to the branch (`git push origin feature/new-method`)
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

If you have questions about the API or find issues with the documentation:

1. Check the existing documentation for answers
2. Open an issue on GitHub
3. Contact the development team

## Inspiration

This repo is a copy of [https://github.com/mzernetsch/jrgen](https://github.com/mzernetsch/jrgen
) 

---

**Built with ❤️ using Tailwind CSS and shadcn design system**


