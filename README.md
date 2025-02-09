<!DOCTYPE html>
<html lang="en">
<body>

<div class="container">
    <h1>🖐 Hand Sign Detection</h1>
    <details open>
        <summary>📌 Introduction</summary>
        <p>Hand Sign Detection is a <b>computer vision-based project</b> that recognizes hand gestures in <b>real-time</b> using a webcam. It leverages <b>MediaPipe</b> for hand landmark detection and <b>Scikit-Learn's Random Forest classifier</b> for sign classification.</p>
    </details>
    <hr>
    <details>
        <summary>🎯 Features</summary>
        <ul>
            <li>✔ <b>Real-Time Detection</b>: Uses a webcam to capture and classify hand gestures instantly.</li>
            <li>✔ <b>Data Collection & Labeling</b>: Easily collect images for different hand signs and organize them.</li>
            <li>✔ <b>Hand Landmark Extraction</b>: Uses MediaPipe to detect 21 hand landmarks efficiently.</li>
            <li>✔ <b>Machine Learning Classification</b>: Trains a Random Forest model for accurate gesture recognition.</li>
            <li>✔ <b>Scalable & Modular</b>: Organized scripts for easy modifications and expansions.</li>
        </ul>
    </details>
    <hr>
    <details>
        <summary>🚀 Installation & Setup</summary>
        <pre><code># Clone the repository
git clone https://github.com/madhavc9/Hand-Sign-Detection.git

# Navigate into the project directory
cd Hand-Sign-Detection

# Install required dependencies
pip install -r requirements.txt

# Run the application
python app.py
</code></pre>
    </details>
    <details>
        <summary>📂 Project Structure</summary>
        <ul>
            <li><b>collect_images.py</b> - Captures and stores hand sign images for training.</li>
            <li><b>prepare_data.ipynb</b> - Processes images and extracts hand landmarks.</li>
            <li><b>train_model.py</b> - Trains a machine learning model on the processed data.</li>
            <li><b>app.py</b> - Runs real-time detection using the trained model.</li>
        </ul>
    </details>
    <hr>
    <details>
        <summary>🔧 Technologies Used</summary>
        <ul>
            <li><b>Python</b> - Core language for scripting and model development.</li>
            <li><b>OpenCV</b> - For capturing video and processing images.</li>
            <li><b>MediaPipe</b> - For efficient hand landmark detection.</li>
            <li><b>Scikit-Learn</b> - For training and evaluating the machine learning model.</li>
            <li><b>NumPy</b> - For numerical operations and data handling.</li>
        </ul>
    </details>
    <details>
        <summary>🛠 How It Works</summary>
        <hr>
        <ol>
            <li>📸 <b>Data Collection</b>: Capture images for each hand sign.</li>
            <li>🔍 <b>Data Preprocessing</b>: Extract key hand landmarks.</li>
            <li>📊 <b>Model Training</b>: Train a machine learning model on labeled data.</li>
            <li>🎥 <b>Real-Time Prediction</b>: Use a webcam to detect and classify hand signs.</li>
        </ol>
    </details>
    <details>
    <hr>
        <summary>💡 Future Enhancements</summary>
        <ul>
            <li>🔹 Implement a deep learning model for improved accuracy.</li>
            <li>🔹 Add support for more hand gestures.</li>
            <li>🔹 Create a graphical user interface (GUI) for better user interaction.</li>
        </ul>
    </details>
    <hr>
    <details>
        <summary>📞 Contact</summary>
        <p>If you have any questions or suggestions, feel free to reach out:</p>
        <ul>
            <li>📧 Email: <a href="mailto:ranmadhav@gmail.com">your.email@example.com</a></li>
            <li>🐙 GitHub: <a href="https://github.com/madhavc9" target="_blank">yourusername</a></li>
        </ul>
    </details>

</div>

</body>
</html>
