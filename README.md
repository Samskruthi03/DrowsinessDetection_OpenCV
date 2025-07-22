# AI Powered Drowsiness Detection System

A real-time drowsiness detection application using computer vision and machine learning techniques to enhance driving safety by monitoring eye movements and alerting users when drowsiness is detected.

## Project Overview

This project implements an AI-based solution to detect driver drowsiness using image processing and machine learning. The system analyzes real-time video feed to monitor eye movements and facial features, providing timely alerts to prevent accidents caused by drowsy driving.

## Features

- **Real-time Detection**: Continuous monitoring of eye movements through webcam
- **High Precision**: Advanced machine learning algorithms for accurate drowsiness prediction
- **Safety-focused**: Designed specifically for driving safety applications
- **OpenCV Integration**: Utilizes computer vision for efficient image processing
- **Alert System**: Immediate notifications when drowsiness is detected

## Technologies Used

- **Python**: Core programming language
- **OpenCV**: Computer vision and image processing
- **Machine Learning Libraries**: For predictive modeling and classification
- **Image Processing**: Real-time video analysis and feature extraction

## Prerequisites

Before running this project, make sure you have the following installed:

bash
Python 3.7+
OpenCV
NumPy
Pandas (if used for data processing)
Matplotlib (for visualizations)



## How It Works

1. **Video Capture**: The system captures real-time video from the user's webcam
2. **Face Detection**: Identifies and tracks the user's face in the video stream
3. **Eye Tracking**: Locates and monitors eye regions for movement patterns
4. **Feature Extraction**: Analyzes eye aspect ratios and blink patterns
5. **Drowsiness Classification**: Uses machine learning to classify drowsiness levels
6. **Alert Generation**: Triggers alerts when drowsiness is detected

## Technical Implementation

The system employs several computer vision techniques:

- aar Cascades or Dlib for face detection
- Eye Aspect Ratio (EAR) calculation for drowsiness detection
- Frame-by-frame analysis for real-time processing
- Threshold-based classification for alert triggering

## Use Cases

- Automotive Safety: Integration with vehicle safety systems
- Fleet Management: Monitoring commercial drivers
- Personal Safety: Individual use for long-distance driving
- Research Applications: Academic studies on driver behavior

## Performance

- **High Accuracy**: Achieved advanced precision in drowsiness detection
- **Real-time Processing**: Efficient frame-by-frame analysis
- **Low Latency**: Quick response time for immediate alerts

##  Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Samskruthi Joshi**
- LinkedIn: [linkedin.com/in/joshisamskruthii](https://linkedin.com/in/joshisamskruthii)
- Email: joshisamskruthii@gmail.com

## Acknowledgments

- OpenCV community for excellent computer vision tools
- Machine learning research community for drowsiness detection methodologies
- Safety organizations promoting drowsy driving awareness

## 📞 Contact

For questions, suggestions, or collaboration opportunities, feel free to reach out!

---

⚠️ **Safety Note**: This system is designed to assist in drowsiness detection but should not be the sole safety measure. Always ensure proper rest before driving and follow all traffic safety guidelines.
