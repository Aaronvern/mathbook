# MathBook

MathBook is a cutting-edge tool designed to solve math problems interactively. By leveraging advanced AI, users can upload images of equations, expressions, or graphical problems and instantly receive detailed solutions. It's perfect for students, educators, and math enthusiasts.

## Features

- **Image-to-Solution**: Upload an image of a math problem and receive detailed solutions.
- **AI-Powered Analysis**: Uses advanced AI models like LLaVA for image understanding and Gemini for computations.
- **User-Friendly Interface**: Simplifies math learning for everyone, blending practicality with technology.

---

## Backend

The backend processes images, extracts mathematical data, and provides accurate solutions. It is powered by:

- **LLaVA Model**: For image-to-text processing.
- **Gemini API**: For solving and interpreting mathematical problems.
- **MongoDB**: To store user-uploaded images and responses.

### API Endpoints

- `/calculate`: Accepts image files and optional variable assignments.

### Technologies

- **FastAPI**: Backend framework.
- **Redis**: For caching.
- **MongoDB**: Database for flexible data storage.

---

## Frontend

The frontend offers an interactive interface for users to upload and view solutions.

### Key Features

- **Canvas Drawing**: Draw math problems directly on the screen.
- **Color Picker & Controls**: Select brush sizes and colors.
- **LaTeX Renderer**: Converts API responses to LaTeX for dynamic rendering.

### Technologies

- **React**: Frontend framework.
- **TailwindCSS**: Styling.
- **Mantine**: UI components.
- **Axios**: For API communication.

---

---

## Security & Optimization

- **Authentication**: API keys or OAuth.
- **Rate Limiting**: Prevent misuse.
- **Data Encryption**: TLS/SSL for secure data transfer.

---

## Getting Started

### Prerequisites

- **Node.js**
- **Python 3.9+**
- **Docker**
- **Redis**
- **MongoDB**

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Aaronvern/mathbook.git
   cd mathbook
2. Install backend dependencies:
  ```bash
  cd mathbook_be
  pip install -r requirements.txt
3. Install frontend dependencies:
  ```bash
  cd ../math book fe
  npm install
4. Start the services:
  ```bash
  # Backend
  cd ../math book be
  python app.py

  # Frontend
  cd ../math book fe
  npm run dev


## Contributing
Contributions are welcome! Feel free to submit issues or pull requests for improvements.

