# Ascii_vid
<h1 align="center">🎥 ASCII Video Player in Python</h1>

<p align="center">
  A fun Python project that converts videos into ASCII art and plays them directly in your terminal.  
</p>

<hr/>

<h2>📌 Features</h2>

<ul>
  <li>Converts each frame of a video into ASCII art</li>
  <li>Plays video directly in the terminal</li>
  <li>Customizable terminal width</li>
  <li>Adjustable FPS (frames per second)</li>
  <li>Cross-platform support (Windows, Linux, macOS)</li>
</ul>

<hr/>

<h2>⚙️ Requirements</h2>

<p>Make sure you have the following installed:</p>

```bash
python 3.x
opencv-python
numpy
Install dependencies with:

pip install opencv-python numpy

<hr/> <h2>🚀 Usage</h2> <p>1. Clone the repository:</p>
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

<p>2. Run the program:</p>
python new.py

<p>3. Enter the required inputs when prompted:</p> <ul> <li><b>Video path</b>: path to your <code>.mp4</code> file</li> <li><b>Terminal width</b>: default is 80 characters</li> <li><b>FPS</b>: leave empty to use video’s FPS</li> </ul> <hr/> <h2>📺 Example</h2> <p>Example usage in terminal:</p>
Enter the path to the video file: vid.mp4
Enter terminal width (default 80): 100
Enter FPS (default: use video FPS): 


Output will be ASCII frames playing in your terminal.

<hr/> <h2>📝 Notes</h2> <ul> <li>Works best with darker terminal backgrounds.</li> <li>Larger width → better detail, but slower performance.</li> <li>Press <code>CTRL + C</code> to stop playback.</li> </ul> <hr/> <h2>📄 License</h2> <p>This project is licensed under the <a href="https://opensource.org/licenses/MIT">MIT License</a>.</p> ```