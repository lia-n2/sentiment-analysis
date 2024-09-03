# sentiment-analysis

## Project Overview

In this project, we build a sentiment analysis tool that processes YouTube comments and provides a sentiment score and summary for each video. 

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/
    cd machine-learning-resume-project
    ```

2. **Create a virtual environment and activate it**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up environment variables**:
    - Create a `.env` file in the root directory and add your YouTube API key:
    ```env
    YOUTUBE_API_KEY=your_youtube_api_key
    ```

## Usage

1. **Run the Flask API**:
    ```bash
    python app.py
    ```

2. **Open the frontend**:
    - Navigate to `http://localhost:5000` in your web browser.
    - Enter the URL of a YouTube video and click "Analyze".

## Project Structure

- `app.py`: The main Flask application.
- `model.py`: Code for loading and using the TensorFlow model.
- `static/`: Static files for the frontend.
- `templates/`: HTML templates for the frontend.
- `requirements.txt`: List of required Python packages.
