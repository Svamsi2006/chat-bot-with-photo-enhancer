# AI Photo Enhancement Chatbot

A professional photo enhancement application with AI-powered chat capabilities. This application allows users to enhance their photos and interact with an AI assistant for image-related queries.

## Features

- 🖼️ **Image Enhancement**
  - Automatic color correction
  - Contrast and brightness adjustment
  - Sharpness enhancement
  - Before/After comparison

- 💬 **AI Chat Interface**
  - Gemini API integration for intelligent responses
  - Dark theme with modern UI
  - Smooth animations and transitions
  - Real-time image processing feedback

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone [your-repository-url]
   cd enhancephoto
   ```

2. **Create Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Environment Configuration**
   - Create a `.env` file in the root directory
   - Add your Gemini API key:
     ```
     GEMINI_API_KEY=your_api_key_here
     ```

5. **Run the Application**
   ```bash
   python app.py
   ```
   - Open your browser and navigate to `http://localhost:5000`

## Usage

1. **Upload Images**
   - Click the upload button or drag and drop images
   - Supported formats: PNG, JPG, JPEG, WebP
   - Maximum file size: 5MB

2. **Image Enhancement**
   - Uploaded images are automatically enhanced
   - View before/after comparison
   - Download enhanced images

3. **Chat with AI**
   - Ask questions about image processing
   - Get recommendations for further enhancements
   - Receive detailed explanations about the enhancement process

## Technical Details

- **Backend**: Flask
- **Frontend**: HTML5, CSS3, JavaScript
- **Image Processing**: Pillow (PIL)
- **AI Integration**: Google Gemini API
- **Environment**: Python 3.8+

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
