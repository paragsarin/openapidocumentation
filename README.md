# OpenAPI Documentation Generator

A simple, web-based tool to generate beautiful HTML documentation from OpenAPI/Swagger specifications.

## 🚀 Live Demo

Visit the live application: [https://paragsarin.github.io/openapidocumentation/](https://paragsarin.github.io/openapidocumentation/)

## ✨ Features

- **Multiple Input Options**: Upload JSON files or download from URLs
- **OpenAPI Support**: Compatible with both OpenAPI v2 (Swagger) and v3 specifications
- **Clean Documentation**: Generates professional, readable API documentation
- **Interactive Navigation**: Quick navigation between API endpoints and data models
- **Export Functionality**: Export generated documentation as standalone HTML
- **Sample Files**: Includes sample OpenAPI specifications for testing

## 📋 How to Use

### Option 1: Upload File
1. Download one of the sample files or use your own OpenAPI specification
2. Click "Choose File" and select your JSON file
3. Click "Generate Documentation"
4. View your formatted API documentation

### Option 2: Download from URL
1. Enter the URL of your OpenAPI specification
2. Click "Download & Generate"
3. The tool will fetch and generate documentation automatically

## 📁 Sample Files

This repository includes sample OpenAPI specifications:

- **[sample-openapi-v2.json](sample-openapi-v2.json)** - OpenAPI v2 (Swagger) example with user management API
- **[sample-openapi-v3.json](sample-openapi-v3.json)** - OpenAPI v3 example with product management API

## 🛠️ Technical Details

- **Frontend**: Pure HTML, CSS, and JavaScript
- **No Backend Required**: Runs entirely in the browser
- **CORS Handling**: Includes fallback for CORS-restricted URLs
- **Responsive Design**: Works on desktop and mobile devices

## 📖 Supported Features

- API endpoint documentation with HTTP methods
- Request/response schemas
- Parameter descriptions
- Data model definitions with clickable references
- Authentication schemes (OpenAPI v3)
- Server configurations
- Tags and grouping

## 🔧 Local Development

1. Clone this repository
2. Open `generate-api-docs.html` in your web browser
3. No build process or dependencies required!

## 📝 OpenAPI Specification Format

The tool supports standard OpenAPI/Swagger JSON format:

```json
{
  "openapi": "3.0.3",
  "info": {
    "title": "Your API",
    "version": "1.0.0"
  },
  "paths": {
    // Your API endpoints
  }
}
```

## 🤝 Contributing

Feel free to submit issues, feature requests, or pull requests to improve this tool.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙋‍♂️ Support

If you encounter any issues or have questions, please open an issue on GitHub.

---

**Made with ❤️ for the API documentation community**
