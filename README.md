# AR Filters with Mediapipe :dog::cat:

Create and customize augmented reality (AR) filters using the powerful and efficient MediaPipe framework. This project uses real-time facial tracking and overlay techniques to bring AR experiences to life.

## 🌟 Features

- Real-time facial tracking with MediaPipe Face Mesh.
- Customizable AR filters, including effects like face masks, glasses, and more.
- Open-source and developer-friendly codebase for creative experimentation.

## 🛠️ Tools and Technologies

- MediaPipe: For real-time facial landmark detection and tracking.
- OpenCV: For image processing and visualization.
- Python: To integrate and process the entire workflow.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.7+
- Required libraries in requirements.txt (install via pip)

```bash
pip install -r requirements.txt
```

## ⚙️ Installation

1. Clone this repository:

```bash
# Clone the repository
git clone https://github.com/prernarohra/AR-Filters-with-mediapipe.git

# Navigate to the project directory
cd AR-Filters-with-mediapipe
```
2. Run the application:

```bash
python apply_filter.py
```

## 📂 Project Structure

```bash
AR-Filters-with-mediapipe/  
├── filters/                # AR filter designs and implementations  
├── faceBlendCommon.py      # Utility file
├── apply_filter.py         # Main script to run the application 
├── create_points_labels.py # Point creating function
├── points_labels.txt       # Points/Labels
├── requirements.txt        # Dependencies  
└── README.md               # Documentation  
```

## 🚧 Possible Enhancements

- Add more AR filters (e.g., animated masks, seasonal themes).
- Enhance filter customization with GUI options.

## 🤝 Contributing

Contributions are welcome! If you have ideas for new filters or performance improvements, feel free to:

1. Fork the repo.
2. Create your feature branch: git checkout -b feature/NewFilter.
3. Commit your changes: git commit -m 'Add NewFilter'.
4. Push to the branch: git push origin feature/NewFilter.
5. Open a pull request.
