![image](https://github.com/user-attachments/assets/543718c1-4057-4bd3-9f4e-1d1cdb5277cb)
## Live Link :: https://3djournals.netlify.app/

# 3D Journal Web App

## Overview

The **3D Journal Web App** is an interactive journaling experience built using **React Three Fiber**, enabling users to write and navigate through a virtual book in 3D. The project leverages **React Three Fiber**, **Jotai** for state management, and **TailwindCSS** for styling.

[Live Demo](https://3djournals.netlify.app/)

## Features

- 📖 **3D Interactive Book** - A fully immersive journaling experience with realistic page-turning animations.
- 📝 **Persistent Journal Entries** - Save and load journal entries using local storage.
- 🎨 **Customizable Pages** - Write on different pages with smooth text rendering.
- 🌅 **Dynamic Environment** - Includes lighting, shadows, and a smooth floating effect.
- 📜 **Thematic UI** - Inspired by classical literature and philosophy.

## Tech Stack

- **React** - Core framework.
- **Vite** - Fast build tool.
- **React Three Fiber** - 3D rendering with Three.js.
- **Jotai** - State management.
- **TailwindCSS** - Styling.
- **Three.js** - 3D graphics.

## Installation

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn

### Steps

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/3D-Journal-Web.git
   cd 3D-Journal-Web
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
   or
   ```sh
   yarn install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```
   or
   ```sh
   yarn dev
   ```
4. Open the app in your browser at `http://localhost:5173/` (default Vite port).

## Usage

### Writing in the Journal
- Click on a page to open and write.
- Use the dropdown to navigate between pages.
- Text is saved automatically in **localStorage**.

### Navigation
- Click buttons at the bottom to flip pages.
- Use mouse controls to rotate and zoom the book.

## Project Structure
```
3D-Journal-Web/
│── src/
│   ├── components/
│   │   ├── Book.jsx          # Renders the 3D journal
│   │   ├── Experience.jsx    # Main 3D scene setup
│   │   ├── UI.jsx            # Controls and page selection
│   ├── utils/
│   │   ├── storage.js        # Handles localStorage for journal entries
│   ├── App.jsx               # Main application component
│   ├── main.jsx              # React entry point
│   ├── index.css             # Styles
│── public/
│── package.json
│── vite.config.js
│── tailwind.config.js
```

## Deployment

The app is deployed using **Netlify**. To deploy manually:
```sh
npm run build
```
Then upload the `dist/` folder to a hosting service of your choice.

## Contributing

1. Fork the repo.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes.
4. Commit (`git commit -m 'Add new feature'`).
5. Push (`git push origin feature-name`).
6. Open a pull request.

## License

This project is licensed under the MIT License.

