# Running Form Analyzer

A web-based tool that analyzes running form using AI to provide detailed feedback and recommendations for improvement.

## Features

- Real-time running form analysis using MediaPipe pose detection
- Detailed feedback on posture, stride length, and running mechanics
- Overall form score and specific recommendations
- Easy-to-use web interface
- Privacy-focused (all processing done server-side, no videos stored)

## Live Demo

Frontend: https://shredathletics.github.io/runningformanalyser
Backend: https://running-form-analyzer.onrender.com

## Local Development

1. Clone the repository:
```bash
git clone https://github.com/shredathletics/runningformanalyser.git
cd runningformanalyser
```

2. Open `index.html` in your browser to test the frontend.

3. For local backend testing, change the `RENDER_BACKEND_URL` in `index.html` to your local server URL.

## Usage

1. Visit the live demo URL
2. Upload a video of yourself running (supported formats: MP4, MOV, AVI)
3. Wait for the analysis to complete
4. Review your form score and detailed recommendations

## Technical Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Video requirements:
  - Format: MP4, MOV, or AVI
  - Maximum size: 100MB
  - Clear view of full body while running
  - Recommended length: 10-30 seconds

## Privacy

- Videos are processed server-side and not stored
- No personal data is collected or stored
- All analysis is done in real-time

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

