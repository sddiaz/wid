# WiD - Write it Down

A responsive note-taking web application designed to work seamlessly across mobile and desktop devices.

## Overview

**WiD** stands for "Write it Down" - a full-featured note-taking app built as part of my journey to learn full-stack software development. The name "WiD" rolls off the tongue more smoothly and represents the core functionality of quickly capturing thoughts and ideas.

## Features

### 📝 Rich Text Editor
- **Font Customization**: Change fonts and font sizes
- **Text Formatting**: Bold, italic, underline, and strike-through
- **Advanced Features**: 
  - Undo functionality
  - Font color selection
  - Text highlighting
  - Bullet points, numbered lists, and checklists
  - Link insertion
  - Image importing
  - YouTube video and Google Maps embedding

### 💾 Note Management
- **Persistent Storage**: Browser-based saving with optional user accounts
- **Timestamps**: Automatic date and time tracking for all notes
- **Search**: Keyword search across all saved notes
- **Sharing**: Generate shareable links for notes

### 👤 User Authentication
- **Account System**: Secure user registration and login
- **Social Login**: Google and GitHub sign-in integration
- **Profile Management**: 
  - View and edit user profile
  - Account deletion capability
  - Email confirmation system
- **Security**: Password hashing and secure session management

## Technical Stack

### Frontend
- Responsive web design that scales to any screen size
- Modern UI/UX with appealing color palette
- Mobile-first approach for optimal user experience

### Backend & Services
- **Authentication**: Firebase Authentication
- **Database**: Firebase Firestore
- **Hosting**: Netlify
- **Password Management**: Secure hashing algorithms

## Development Process

### Design Phase
The project begins with whiteboard mockups and wireframes to establish:
- App structure and maintainability
- User flow and navigation
- Component hierarchy
- Responsive breakpoints

### Implementation Strategy
1. **Logic First**: Core functionality implementation
2. **Styling Second**: UI/UX integration after feature completion
3. **Testing**: Comprehensive testing across devices and browsers
4. **Deployment**: Production deployment with CI/CD pipeline

## Project Goals

This application serves as a comprehensive learning experience in:
- Full-stack web development
- Responsive design principles
- User authentication and security
- Database design and management
- Modern web technologies and best practices

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Installation
```bash
# Clone the repository
git clone https://github.com/sddiaz/wid.git

# Navigate to project directory
cd wid

# Install dependencies
npm install

# Start development server
npm start
```

### Environment Variables
Create a `.env` file in the root directory:
```
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
```

## Contributing

This is a personal learning project, but feedback and suggestions are welcome! Feel free to open issues or submit pull requests.

## License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with ❤️ as part of my full-stack development journey*
