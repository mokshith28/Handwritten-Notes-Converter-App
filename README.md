# Notes Converter - OCR Mobile App
![Picture1](https://github.com/user-attachments/assets/c55ad43f-692f-4986-8ad7-34af07b59c04)
![Picture2](https://github.com/user-attachments/assets/31aa1913-ea33-4fc6-ad11-7c37065b5368)

A React Native OCR application built with Expo that extracts text from handwritten notes and images using Google Vision API.

## Features

- 📷 Camera integration for capturing images
- 🖼️ Gallery image selection
- 🔍 AI-powered text extraction using Google Vision API
- 💾 Save and manage scanned text
- 📋 Copy text to clipboard
- 🌐 Multi-language support (English, Hindi, Kannada)

## Setup Instructions

### Prerequisites
- Node.js (v16 or higher)
- Expo CLI
- Google Vision API key

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Major-Project
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   # Copy the example environment file
   cp .env.example .env
   
   # Edit .env and add your Google Vision API key
   EXPO_PUBLIC_GOOGLE_VISION_API_KEY=your_api_key_here
   ```

4. **Get Google Vision API Key**
   - Go to [Google Cloud Console](https://console.cloud.google.com/)
   - Create a new project or select existing one
   - Enable the Vision API
   - Create credentials (API Key)
   - Copy the API key to your `.env` file

5. **Start the development server**
   ```bash
   npm start
   ```

## Project Structure

```
src/
├── components/         # Reusable UI components
├── config/            # Configuration constants
├── constants/         # App constants & enums
├── containers/        # Container components
├── hooks/             # Custom React hooks
├── services/          # API and business logic
├── store/             # State management
├── styles/            # Styling files
└── utils/             # Utility functions
```

## Environment Variables

Create a `.env` file in the root directory with:

```env
EXPO_PUBLIC_GOOGLE_VISION_API_KEY=your_google_vision_api_key
```

**⚠️ Important**: Never commit your `.env` file to version control. The API key should be kept secret.

## Technologies Used

- **React Native** - Cross-platform mobile development
- **Expo** - Development platform and tools
- **Google Vision API** - OCR and text recognition
- **React Hooks** - State management
- **Expo Camera** - Camera functionality
- **Expo Image Picker** - Gallery access

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Security

- API keys are stored in environment variables
- Sensitive data is not committed to version control
- Follow security best practices for API usage" 
