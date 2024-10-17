# Apple Calculator

This is an advanced calculator powered by the Google Gemini API, designed to solve mathematical problems through an interactive drawing interface. Users can draw shapes or diagrams on the screen to visually represent math problems, such as finding the length of the hypotenuse in a right-angled triangle, and the calculator will compute the answer using the given values.

## Features

- **Interactive Problem Solving**: Solve mathematical problems by drawing on the screen, such as calculating the hypotenuse by sketching a triangle and inputting the side lengths.
- **Basic Arithmetic Operations**: Addition, Subtraction, Multiplication, and Division.
- **Google Gemini API Integration**: Provides enhanced AI capabilities.
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

- Draw shapes and input values for solving mathematical problems.
- For example, to find the hypotenuse of a right-angled triangle, draw the triangle, input the lengths of the legs, and press the "Run" button.
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
