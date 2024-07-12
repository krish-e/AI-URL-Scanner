# AI URL Scanner

## Description
This web application allows users to upload images (single, multiple, or even a zip file), extract all URLs from the provided images, and even checks if the found URLs are valid. The results are displayed directly in the browser in table format.

## Features
- **Image Upload:** Supports single image, multiple images, and zip file uploads.
- **URL Extraction:** Utilizes OpenAI API's Vision to extract URLs from images.
- **URL Validation:** Checks the validity of the extracted URLs.
- **Result Display:** Displays the extracted and validated URLs in the browser as a table.

## Installation

### Prerequisites
- Python 3.8+
- pip
- Virtual environment (optional but recommended)

### Setup

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/ai-url-scanner.git
    cd ai-url-scanner
    ```

2. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Start the web application:**
    ```bash
    python app.py
    ```

2. **Open your web browser and navigate to:**
    ```
    http://127.0.0.1:5000
    ```

3. **Upload your images:**
    - You can upload a single image, multiple images, or a zip file containing images.

4. **View Results:**
    - It takes time to process multiple images.
    - After processing, the application will display all extracted URLs and their validity status.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

