# Satellite Sensor Data Analyzer (JavaFX & PostgreSQL)  

## Overview  
This project is a JavaFX-based application designed to analyze sensor data from a miniature satellite (CubeSat). It features a 3D model with animations to facilitate data visualization. Built with Java 11, JavaFX, and PostgreSQL, it serves as a practical activity for the CEFET-MG Aerospace Competition Team, which participates in CubeSat competitions.  

## Features  
- **3D Visualization**: Interactive 3D model of the CubeSat with dynamic animations.  
- **Sensor Data Analysis**: Processes and displays telemetry data, including:  
  - Position (X, Y, Z coordinates)  
  - Velocity and acceleration  
  - Temperature and altitude  
- **Database Integration**: PostgreSQL backend for storing and retrieving sensor data.  

## Prerequisites  
- **Java 11** (or compatible)  
- **JavaFX** (included in the project dependencies)  
- **PostgreSQL** (with a database named `tccaerospace`)  

## Setup Instructions  
1. **Database Configuration**:  
   - Restore the sample database using the scripts provided in `src/`.  
   - Update the `persistence.xml` file with your PostgreSQL credentials (default user/password are set for legacy purposes).  

2. **Run the Application**:  
   - Ensure all dependencies are resolved (JavaFX libraries and PostgreSQL JDBC driver).  
   - Launch the project using Java 11.  

## Screenshot  
![Demo Screen](./gui3d/preview.gif)

## Legacy Note  
This is an experimental/legacy project, so default database credentials are used for simplicity. **Always change them in `persistence.xml` for security.**  

## Contribution  
Developed as part of CEFET-MG’s aerospace extension program for competition purposes. Contributions or improvements are welcome!  

---

### Key Improvements:  
- **Structure**: Organized into clear sections (Overview, Features, Prerequisites, etc.).  
- **Clarity**: Simplified technical jargon and fixed grammar.  
- **Security Note**: Emphasized changing default credentials.  
- **Professional Tone**: Made it concise and reader-friendly.  

Let me know if you'd like to add more details (e.g., build instructions, license, or team credits)!
