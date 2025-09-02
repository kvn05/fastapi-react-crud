# FastAPI + React Single Page Application

A full-stack single-page application (SPA) built with **FastAPI** for the backend API and **React** for the frontend user interface.

## 📚 Tutorial

This project was built following the comprehensive tutorial on TestDriven.io: [Developing a Single Page App with FastAPI and React](https://testdriven.io/blog/fastapi-react/)

## 🚀 Getting Started

Follow these steps to run the application locally on your development machine.

## 📋 Prerequisites

Ensure you have the following installed on your system:

- **Python 3.13+** (or any compatible Python 3.x version)
- **pip** (Python package installer)
- **Node.js** (Latest LTS version recommended)
- **npm** (Node Package Manager, comes with Node.js)

## 🛠️ Installation & Setup

The application consists of two parts that need to be run simultaneously. You'll need two terminal windows.

### 🐍 Backend Setup (FastAPI)

1. Clone this repository and navigate to the backend directory:
```bash
cd backend
```

2. Create and activate a virtual environment:
```bash
python -m venv env
# On Windows
.\venv\Scripts\activate
# On macOS/Linux
source env/bin/activate
```

3. Install Python dependencies:
```bash
pip install -r requirements.txt
```

4. Start the FastAPI server:
```bash
python main.py
```

The API will be available at `http://localhost:8000`
- 📖 API Documentation (Swagger UI): `http://localhost:8000/docs`

### ⚛️ Frontend Setup (React)

1. In a new terminal, navigate to the frontend directory:
```bash
cd frontend
```

2. Install JavaScript dependencies:
```bash
npm install
```

3. Start the React development server:
```bash
npm run dev
```

The React application will be available at `http://localhost:5173`

## 🌟 Features

- FastAPI backend with automatic API documentation
- React frontend with modern development setup
- Full-stack integration between backend and frontend
- RESTful API design
- Responsive user interface

## 📁 Project Structure

```
.
├── backend/          # FastAPI backend
│   ├── main.py       # FastAPI application entry point
│   └── requirements.txt
└── frontend/         # React frontend
    ├── src/          # React source files
    ├── package.json
    └── ...
```

## 🤝 Contributing

Feel free to contribute to this project by submitting issues or pull requests.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
