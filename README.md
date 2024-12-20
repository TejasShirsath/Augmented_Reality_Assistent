# Augmented Reality Assistant

The Augmented Reality Assistant is a virtual assistant inspired by JARVIS from Iron Man. Developed using Python, OpenCV, Google's Generative AI (Gemini), and Tesseract OCR, this project provides a real-time, interactive assistant with a range of functionalities.

## Features

<table>
  <thead>
    <tr>
      <th>Feature</th>
      <th>Project.py</th>
      <th>server.py</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Virtual Assistant</td>
      <td>✅</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Real-Time Information</td>
      <td>✅</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Hand Gesture Interaction</td>
      <td>✅</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Text Detection</td>
      <td>✅</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Face Detection</td>
      <td>✅</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Google Maps Integration</td>
      <td>✅</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Temperature</td>
      <td>✅</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Location</td>
      <td>✅</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Coordinates</td>
      <td>✅</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Time</td>
      <td>✅</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Mic Connection Status</td>
      <td>✅</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Internet Connection Status</td>
      <td>✅</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Access Through Multiple Devices</td>
      <td>❌</td>
      <td>✅</td>
    </tr>
  </tbody>
</table>

## Technologies Used

- **Python**: For the backend logic and server-side scripting.
- **OpenCV**: For computer vision tasks.
- **Google Generative AI (Gemini)**: For generating responses and explanations.
- **Tesseract OCR**: For optical character recognition to detect text from images.
- **Requests**: For making HTTP requests to APIs.
- **pyttsx3**: For text-to-speech conversion.
- **SpeechRecognition**: For speech-to-text conversion.
- **Flask**: For hosting the project on HTTP (server.py).

## Getting Started

### Prerequisites

- [Python](https://www.python.org/downloads/)
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) (Install Tesseract-OCR and add it to your system's PATH)
- [Google Generative AI API Key](https://ai.google.dev/gemini-api/docs/api-key) (Gemini API key)
- [OpenWeatherMap API Key](https://openweathermap.org/api) (For weather data)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/TejasShirsath/Augmented_Reality_Assistant.git
    cd Augmented_Reality_Assistant
    ```

2. Install requirements:

    ```bash
    pip install -r requirements.txt
    ```

3. Configure environment variables:

    Create a `.env` file in the project root directory and add the following variables:

    ```
    GENAI_API_KEY=your_google_generative_ai_api_key
    WEATHER_APP_ID=your_openweathermap_api_key
    ```

4. Update paths in `Project.py`:

    - **Cascade Path**: Update the `cascade_path` variable with the path to `haarcascade_frontalface_default.xml`.
    - **Tesseract Path**: Update the `tesseract_path` variable with the path to `tesseract.exe`.

5. Run the project:

    **For desktop application (Project.py):**
    ```bash
    python Project.py
    ```

    **For web-based application (server.py):**
    ```bash
    python server.py
    ```

## Usage

AR assistant have the potential to greatly enhance our daily lives, providing us with relevant information and helping us perform tasks more efficiently. The future of AR technology is bright, with continued advancements in AI and computer vision expected to drive the growth of AR assistants. As AR technology continues to evolve, it will play an increasingly important role in shaping the future of how we interact with the digital world.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
