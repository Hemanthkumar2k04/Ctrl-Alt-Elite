1. Video Data Processing (Team Member 1)
Input Data: Pre-recorded traffic videos.
Processing Steps:
Frame Extraction: Convert video into individual frames using tools like OpenCV.
Object Detection: Use YOLO or another computer vision model to detect vehicles in each frame.
Data Extraction: Count the number of vehicles, identify vehicle types (cars, trucks, etc.), and calculate their speed and direction.
Output Data: A structured dataset containing vehicle counts, types, speed, and movement patterns over time. This will be used for both training the AI model and feeding real-time data into the system when implemented with live cameras.
2. Traffic Simulation (Team Member 2)
Input Data: Parameters defining traffic scenarios (e.g., road layout, traffic volume, signal timings).
Processing Steps:
Simulation Setup: Use tools like SUMO or VISSIM to create a virtual model of the road network.
Simulate Traffic: Generate synthetic traffic data by simulating vehicles’ movements through intersections.
Data Logging: Capture data such as vehicle counts, queue lengths, average speeds, and intersection wait times.
Output Data: Simulated traffic data similar to the data extracted from videos, including vehicle counts, traffic densities, and queue lengths. This data will be used to train and test the AI model for traffic management.
3. Machine Learning Model Development (Team Member 3)
Input Data: Datasets from Video Data Processing and Traffic Simulation.
Processing Steps:
Data Preprocessing: Clean and normalize the data, handle missing values, and possibly augment the dataset.
Feature Engineering: Extract relevant features such as vehicle density, time of day, and road type to improve model performance.
Model Training: Train machine learning models (e.g., neural networks, decision trees) to predict traffic patterns and optimize signal timings.
Output Data: Trained machine learning models capable of predicting traffic patterns and suggesting optimal traffic signal timings based on the input data.
4. AI-Based Traffic Management System (Team Member 4)
Input Data: Outputs from the Machine Learning Model Development phase.
Processing Steps:
Model Integration: Integrate the trained models into the traffic management system.
Real-Time Processing: Implement real-time data feeds from cameras or simulations to make traffic signal decisions.
Optimization Algorithms: Use AI to dynamically adjust traffic signal timings to manage traffic flow effectively.
Output Data: Optimized traffic signal timings and traffic management decisions. This output will be used in the Software Development and Integration phase for execution and monitoring.
5. Software Development and Integration (Team Member 5)
Input Data: Real-time video feeds, simulated data, and outputs from the AI models.
Processing Steps:
API Development: Create APIs to facilitate data exchange between the video processing, AI models, and traffic management systems.
Data Integration: Ensure seamless integration of all components, enabling real-time data flow and model deployment.
Cloud Deployment: Deploy the AI models and systems on cloud platforms to handle large-scale data processing and to allow for scalability.
Output Data: A fully integrated backend system capable of receiving input data, processing it in real-time, and deploying AI-driven traffic management decisions.
6. User Interface and Visualization (Team Member 6)
Input Data: Processed traffic data and AI model outputs.
Processing Steps:
Dashboard Development: Develop real-time dashboards to display traffic data, signal statuses, and AI model predictions.
User Control Interface: Create a user-friendly interface for manual control and adjustments.
Visualization: Provide visual representations of traffic patterns, signal statuses, and AI-driven decisions.
Output Data: A user interface that allows for monitoring, visualization, and manual intervention in the traffic management process.
