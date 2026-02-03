Architecture Overview: A Cloud-Native AI Pipeline

System Architecture
The system follows a Client-Server model with an integrated AI Inference Engine.

Component Breakdown
Data Acquisition Layer (Mobile App):

Developed for high-speed image capture.

Metadata extraction (GPS and Timestamp).

Processing Layer (Cloud):

Preprocessing: Histogram equalization to enhance low-light street photos.

Inference Engine: A YOLOv8 (You Only Look Once) model optimized for real-time object detection.

Persistence Layer:

PostgreSQL: Stores reporting history and geolocation data.

AWS S3: Stores the raw images for future model retraining.

Presentation Layer (UI/UX):

A React-based dashboard featuring a Map API to visualize "trash hotspots" for municipal action.

Tech Stack
Languages: Python (Backend/AI), JavaScript (Frontend).

Frameworks: TensorFlow or PyTorch, FastAPI, React.

Deployment: AWS (utilizing those potential credits!).
