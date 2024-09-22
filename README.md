# FaceShift

FaceShift is an integrated project that enables face-swapping using AI across multiple platforms, including web, desktop, and mobile applications. The project contains both frontend and backend files, with settings for the main web page.

## Project Structure

FaceShift/
├── backend/
│   ├── app.py                # Flask API file
│   ├── model.py              # AI model for face-swapping
│   └── utils.py              # Utility functions for face detection
├── frontend/
│   ├── public/               # Public assets (HTML, images, icons)
│   ├── src/
│   │   ├── App.js            # Main React application file
│   │   ├── components/       # React components (buttons, previews, etc.)
│   │   └── styles/           # CSS files for styling
├── electron/
│   ├── main.js               # Main file for Electron application
│   └── preload.js            # Preload script for native UI settings
├── mobile/
│   ├── App.js                # Main application file for mobile
│   └── components/           # Mobile-specific components
└── website/
    ├── index.html            # Main landing page
    ├── styles.css            # Styles for the web page
    └── install-guide.html     # Installation guide for users
