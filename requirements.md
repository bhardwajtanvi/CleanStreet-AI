Project Name: CleanStreet AI – Real-time Hygiene Monitoring via Computer Vision

Project Overview
A civic-tech solution that leverages high-contrast street photography and AI to automate the detection and reporting of public hygiene issues (waste accumulation, overflowing bins, and litter) in urban environments.

Functional Requirements
Image Analysis: The system shall process night-time and low-light images to identify at least four categories of waste (Plastic, Organic, Paper, and Metal).

Geospatial Tagging: The application must capture GPS coordinates and timestamps for every anomaly detected.

Priority Ranking: The AI shall categorize the severity of the hygiene issue based on the volume of waste detected in the frame.

Admin Dashboard: A web interface for municipal workers to view "Hygiene Heatmaps" and assign cleanup tasks.

Non-Functional Requirements
Accuracy: The model should maintain at least 85% precision in low-light conditions common in night street photography.

Scalability: The architecture must handle concurrent image uploads from multiple users across a city.

Usability: The mobile interface must be designed for quick, "one-tap" reporting by citizens.
