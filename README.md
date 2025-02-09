<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hand Sign Detection - README</title>
</head>
<body>
<div class="container">
    <h1>🖐 Hand Sign Detection</h1>
    <p><span class="badge">Version 1.0</span></p>
    <div class="section">
        <h2>📌 Introduction</h2>
        <p>Hand Sign Detection is a <b>computer vision-based project</b> that recognizes hand gestures in <b>real-time</b> using a webcam. It leverages <b>MediaPipe</b> for hand landmark detection and <b>Scikit-Learn's Random Forest classifier</b> for sign classification. The project is designed to assist in sign language recognition and human-computer interaction.</p>
    </div>
    <div class="section">
        <h2>🎯 Features</h2>
        <ul>
            <li>✔ <b>Real-Time Detection</b>: Uses a webcam to capture and classify hand gestures instantly.</li>
            <li>✔ <b>Data Collection & Labeling</b>: Easily collect images for different hand signs and organize them.</li>
            <li>✔ <b>Hand Landmark Extraction</b>: Uses MediaPipe to detect 21 hand landmarks efficiently.</li>
            <li>✔ <b>Machine Learning Classification</b>: Trains a Random Forest model for accurate gesture recognition.</li>
            <li>✔ <b>Scalable & Modular</b>: Organized scripts for easy modifications and expansions.</li>
        </ul>
    </div>
    <div class="section">
        <h2>🚀 Installation & Setup</h2>
        <p>To run the project locally, follow these steps:</p>
        <pre><code># Clone the repository
git clone https://github.com/yourusername/Hand-Sign-Detection.git
          
# Navigate into the project directory
cd Hand-Sign-Detection

# Install required dependencies
pip install -r requirements.txt

# Run the application
python app.py
</code></pre>
    </div>
    <div class="section">
        <h2>📂 Project Structure</h2>
        <ul>
            <li><b>collect_images.py</b> - Captures and stores hand sign images for training.</li>
            <li><b>prepare_data.ipynb</b> - Processes images and extracts hand landmarks.</li>
            <li><b>train_model.py</b> - Trains a machine learning model on the processed data.</li>
            <li><b>app.py</b> - Runs real-time detection using the trained model.</li>
        </ul>
    </div>
    <div class="section">
        <h2>🔧 Technologies Used</h2>
        <ul>
            <li><b>Python</b> - Core language for scripting and model development.</li>
            <li><b>OpenCV</b> - For capturing video and processing images.</li>
            <li><b>MediaPipe</b> - For efficient hand landmark detection.</li>
            <li><b>Scikit-Learn</b> - For training and evaluating the machine learning model.</li>
            <li><b>NumPy</b> - For numerical operations and data handling.</li>
        </ul>
    </div>
    <div class="section">
        <h2>🛠 How It Works</h2>
        <p>The system follows these steps:</p>
        <ol>
            <li>📸 <b>Data Collection</b>: Capture images for each hand sign.</li>
            <li>🔍 <b>Data Preprocessing</b>: Extract key hand landmarks.</li>
            <li>📊 <b>Model Training</b>: Train a machine learning model on labeled data.</li>
            <li>🎥 <b>Real-Time Prediction</b>: Use a webcam to detect and classify hand signs.</li>
        </ol>
    </div>
    <div class="section">
        <h2>💡 Future Enhancements</h2>
        <ul>
            <li>🔹 Implement a deep learning model for improved accuracy.</li>
            <li>🔹 Add support for more hand gestures.</li>
            <li>🔹 Create a graphical user interface (GUI) for better user interaction.</li>
        </ul>
    </div>
    <div class="section">
        <h2>📞 Contact</h2>
        <p>If you have any questions or suggestions, feel free to reach out:</p>
        <ul>
            <li>📧 Email: <a href="mailto:your.email@example.com">your.email@example.com</a></li>
            <li>🐙 GitHub: <a href="https://github.com/yourusername" target="_blank">yourusername</a></li>
        </ul>
    </div>
</div>

</body>
</html>
