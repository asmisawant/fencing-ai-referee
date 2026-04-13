🧠 AI Fencing Referee Assist System

This project explores the use of computer vision and machine learning to assist referees in fencing, one of the fastest Olympic sports where decisions are made within milliseconds.

🔍 Problem

Fencing bouts—especially saber—can have actions separated by less than 100ms, making accurate refereeing extremely difficult. Human referees face fatigue, limited visibility, and complex rule interpretation.

💡 Solution

This project builds a CNN + RNN-based video classification system to automatically determine:

Left touch
Right touch
Simultaneous touch

The system acts as a referee assist tool to improve decision accuracy.

⚙️ Methodology
Collected ~1700 fencing clips from YouTube
Segmented videos into 3-second clips
Labeled dataset:
Left / Right / Simultaneous
Model pipeline:
CNN → feature extraction
RNN → temporal sequencing
Classification output
📊 Results
Achieved ~70% agreement with human referees
Strong performance on attack classification
Struggles with:
Parry-riposte detection
Blade motion understanding
🚀 Future Work
Integrate pose estimation + blade tracking
Improve temporal modeling
Expand to foil and épée
📁 Project Structure
notebooks/      → Model development
paper/          → Research paper
🛠 Tech Stack
Python
TensorFlow / PyTorch (depending on your code)
OpenCV
Google Colab
📄 Paper

Full research paper available in /paper

🙋‍♀️ Author

Asmi Sawant
UC Berkeley MET (EECS + Business)
