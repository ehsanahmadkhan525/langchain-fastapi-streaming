# Langchain-FastAPI-Streaming

This project demonstrates how to utilize Langchain and FastAPI to stream GPT-generated text in real-time, serving it to a dynamic JavaScript frontend.

## Features

- **Real-time Streaming**: Stream GPT-generated text in real-time.
- **FastAPI Backend**: Powered by FastAPI for high-performance asynchronous processing.
- **JavaScript Frontend**: Dynamic frontend to display streamed text.

## Prerequisites

- Python 3.8+
- Git
- Virtualenv

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/ehsanahmadkhan525/langchain-fastapi-streaming.git
cd langchain-fastapi-streaming
```

### 2. Create a Virtual Environment

Create a virtual environment to manage dependencies:

```bash
python3 -m venv venv
```

### 3. Activate the Virtual Environment

Activate the virtual environment:

- **On Windows**:

  ```bash
  venv\Scripts\activate
  ```

- **On macOS/Linux**:

  ```bash
  source venv/bin/activate
  ```

### 4. Install Requirements

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Running the Application

Start the FastAPI server by running:

```bash
python3 app.py
```

This will start the server on `https://localhost:8000`.

## Accessing the Application

Open your web browser and navigate to `https://localhost:8000` to access the application.

## Contributing

Feel free to submit issues or pull requests if you would like to contribute to the project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy streaming with Langchain and FastAPI!
