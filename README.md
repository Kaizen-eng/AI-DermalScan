# AI-DermalScan
A deep learning-based system for detecting and classifying facial aging signs such as wrinkles, dark spots, and puffy eyes

# AI DermalScan: Facial Skin Aging Detection App
This repository contains the source code and documentation for the AI DermalScan project, a deep learning-based system for detecting and classifying facial aging signs.

# Project Overview
The primary objective of this project is to develop a robust system that can identify and localize common facial aging signs, such as wrinkles, dark spots, puffy eyes, and clear skin. The system utilizes a pretrained deep learning model, EfficientNetB0, and a web-based frontend to provide a user-friendly experience.

### Key Features
* Facial Aging Sign Detection: Detects and classifies facial features into four categories.
* Deep Learning Model: Employs a pretrained EfficientNetB0 model for accurate and efficient classification.
* Web-Based Interface: A user-friendly frontend for image uploads and real-time visualization of annotated results.
* Annotated Output: Displays bounding boxes and percentage predictions on the uploaded images.
* Backend Pipeline: A seamless Python backend that processes images, runs model inference, and returns results.

### Technical Stack
| Area | Tools / Libraries |
| :--- | :--- |
| Image Ops | OpenCV, NumPy, Haarcascade |
| Model | TensorFlow/Keras, EfficientNetB0 |
| Dataset | Labeled facial images dataset |
| Frontend | Streamlit or HTML, CSS |
| Backend | Python |

# Getting Started
### Prerequisites
To run this project, you need to have the following installed on your machine:

* Python 3.8+
* pip (Python package installer)

### Installation
1. Clone this repository:

git clone [https://github.com/your-username/AI-DermalScan.git](https://github.com/your-username/AI-DermalScan.git)
cd AI-DermalScan


2. Create and activate a virtual environment:

# On Windows
python -m venv venv
.\venv\Scripts\activate

# On macOS/Linux
python3 -m venv venv
source venv/bin/activate


3. Install the required packages (create a requirements.txt file listing all dependencies):

pip install -r requirements.txt


# Project Milestones & Status
|Milestone | Focus Area | Status | Deliverables Completed |
| :--- | :--- | :--- | :--- |
| 1 | Data Preparation & Preprocessing | **Complete** | Cleaned and labeled dataset, Class Distribution Plot. |
| 2 | Model Training and Evaluation | Pending | Trained CNN Model (.h5 file), Accuracy & Loss curves. |
| 3 | Frontend and Backend Integration | Pending | Responsive Web UI, Integrated Backend Script.|
| 4 | Finalization and Delivery | Pending | Final Documentation (README), Export Functionality. |

## License
This project is licensed under the MIT License.
