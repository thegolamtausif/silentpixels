<<<<<<< HEAD
# Silent Pixels Steganography Web App

A Flask-based web application for hiding and extracting secret messages in images and videos using steganography and RC4 encryption.

## Features
- Hide (encode) text messages in images and videos
- Extract (decode) hidden messages from images and videos
- RC4 encryption for message security
- Simple web interface

## Project Structure
```
app.py / flask_app.py      # Main Flask application
static/                   # Static files (images, icons, etc.)
templates/                # HTML templates
uploads/                  # Uploaded files
requirements.txt          # Python dependencies
README.md                 # Project documentation
.gitignore                # Git ignore rules
```

## Setup & Usage
1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/silent-pixels.git
   cd silent-pixels
   ```
2. **Create a virtual environment (optional but recommended):**
   ```
   python -m venv .venv
   .venv\Scripts\activate
   ```
3. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```
4. **Run the app:**
   ```
   python app.py
   ```
   or
   ```
   python flask_app.py
   ```
5. **Open your browser:**
   Visit [http://127.0.0.1:5000](http://127.0.0.1:5000)

## Notes
- Place images/videos to encode in the upload form.
- Decoded messages will be shown on the result page.
- For Windows, use PowerShell or Command Prompt for commands.

## License
MIT
=======
# silentpixels
A Flask-based web application for hiding and extracting secret messages in images and videos using steganography and RC4 encryption.
>>>>>>> 2f98754952cf540466982d72e9a54146e1035850
