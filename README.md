# Apple Calculator

This is a clone of the Apple Calculator powered by the Google Gemini API. It is built using TypeScript, Python, and JavaScript, and consists of a frontend (`calc-fe-main`) and a backend (`calc-be-main`). The calculator provides basic arithmetic functionalities and integrates AI through the Google Gemini API.

## Features

- **Basic Arithmetic Operations**: Addition, Subtraction, Multiplication, and Division.
- **Google Gemini API Integration**: Enhanced capabilities through AI integration.
- **Responsive Design**: Adapts to different screen sizes.
- **Frontend and Backend Separation**: Powered by TypeScript, Python, and JavaScript.

## Technologies Used

- **Frontend**: TypeScript, Vite, JavaScript
- **Backend**: Python (with Flask or FastAPI)
- **Google Gemini API**: Provides AI functionalities

## Getting Started

### Prerequisites

- **Node.js**: Required to run the frontend.
- **Python 3.x**: Required to run the backend.
- **Google Gemini API Key**: You need to obtain an API key from Google.

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/senulahesara/Apple-Calculator.git
    ```

2. **Navigate to the frontend directory (`calc-fe-main`)**:
    ```bash
    cd Apple-Calculator/calc-fe-main
    ```

3. **Install frontend dependencies**:
    ```bash
    npm install
    ```

4. **Create a `.env.local` file** in the `calc-fe-main` directory and add the following:
    ```bash
    VITE_API_URL=http://localhost:8900
    ```

5. **Navigate to the backend directory (`calc-be-main`)**:
    ```bash
    cd ../calc-be-main
    ```

6. **Install backend dependencies** (use virtual environment if needed):
    ```bash
    pip install -r requirements.txt
    ```

7. **Create a `.env` file** in the `calc-be-main` directory and add your Google Gemini API key:
    ```bash
    GEMINI_API_KEY=your_api_key_here
    ```

### Running the Project Locally

1. **Run the backend**:
    ```bash
    python3 main.py
    ```

2. **Run the frontend**:
    ```bash
    cd ../calc-fe-main
    npm run dev
    ```

3. Open the application in your browser at `http://localhost:3000`.

## Usage

- Perform basic calculations using the Apple Calculator UI.
- AI-powered features are available through integration with the Google Gemini API.

## Environment Variables

- **Backend** (`.env`):
    ```
    GEMINI_API_KEY=your_api_key_here
    ```

- **Frontend** (`.env.local`):
    ```
    VITE_API_URL=http://localhost:8900
    ```

## Google Gemini API

You need to obtain an API key from the [Google Gemini API](https://cloud.google.com/gemini) and add it to your `.env` file in the backend.

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for improvements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
