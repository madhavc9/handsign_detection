<!DOCTYPE html>
<html lang="en">
<body>

<div class="container">
    <div align="center">
  <img src="/HSD_bg.png" alt="HSD Logo" width="600">
  <h3 align="center">🖐 Hand Sign Detection</h3>
  <p align="center">
    An intelligent system that recognizes and interprets hand gestures in real time.<br>
    <a href="https://drive.google.com/file/d/1bWEiTgkWuQyqGnEvBQNt_22UAcB_Ac7-/view?usp=sharing" target="_blank"><strong>Explore the documentation »</strong></a><br>
    <a href="https://drive.google.com/file/d/1SZsXn98AHjcwl0WnsVWaI8YshWj3CLYl/view?usp=sharing" target="_blank"><strong>Video Demonstration »</strong></a><br>
  </p>
</div>
    <hr>
<details open>
    <summary>📌 Introduction</summary>
    <br>
    <p>Hand Sign Detection is an intelligent system that recognizes and interprets hand gestures in real time, enabling seamless gesture-based communication. By analyzing hand movements, it identifies specific signs, making it highly useful for applications such as sign language recognition, assistive technologies, and human-computer interaction.</p>
    <p>Designed for speed and accuracy, this system provides instant feedback, ensuring a smooth user experience. Whether used for accessibility, educational purposes, or interactive controls, Hand Sign Detection enhances non-verbal communication by bridging the gap between gestures and meaningful interpretation.</p>
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
    <hr>
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
    <hr>
    <details>
        <summary>🛠 How It Works</summary>
        <ol>
            <li>📸 <b>Data Collection</b>: Capture images for each hand sign.</li>
            <li>🔍 <b>Data Preprocessing</b>: Extract key hand landmarks.</li>
            <li>📊 <b>Model Training</b>: Train a machine learning model on labeled data.</li>
            <li>🎥 <b>Real-Time Prediction</b>: Use a webcam to detect and classify hand signs.</li>
        </ol>
    </details>
    <hr>
    <details>
        <summary>📸 Check Captured Screenshot</summary>
        <p>Below is an example screenshot of the Hand Sign Detection system in action:</p>
        <br>
        <div align="center">
            <img src="madhav_hsd.png" alt="Captured Screenshot" width="600">
        </div>
    </details>
    <hr>
    <details>
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
            <li>📧 Email: <a href="mailto:ranmadhav@gmail.com">ranmadhav@gmail.com</a></li>
            <li>🐙 GitHub: <a href="https://github.com/madhavc9" target="_blank">madhavc9</a></li>
        </ul>
    </details>
</div>
 <hr>
    <footer>
        <p align="center">Feel free to reach out for questions or contributions! 🚀 Happy Coding! </p>
    </footer>
</body>
</html>
