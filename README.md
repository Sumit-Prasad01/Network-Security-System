# Network Security System

A machine learning-powered system designed to detect and classify network intrusions, enhancing the security of digital infrastructure. This project integrates data pipelines, model training, web deployment, and containerization to create a robust end-to-end security solution.

## 🚀 Features

- Data ingestion and preprocessing from raw network logs.
- Machine learning model training and evaluation.
- Modular pipeline architecture using custom components.
- Web-based prediction interface (FastApi).
- Docker support for seamless deployment.
- Automated validation and schema checks.

## 📁 Project Structure

```
Network-Security-System/
├── app.py                   # Web application entry point
├── main.py                  # Main pipeline runner
├── push_data.py             # Script to push data for prediction
├── networksecurity/         # Core ML pipeline modules
├── final_model/             # Trained model artifacts
├── Network_Data/            # Raw or processed network data
├── valid_data/              # Validated input data
├── data_schema/             # Schema for data validation
├── prediction_output/       # Output predictions from the model
├── templates/               # HTML templates for web interface
├── Dockerfile               # Docker configuration
├── requirements.txt         # Project dependencies
├── setup.py                 # Installation script
├── .gitignore
└── README.md
```

## 🛠️ Installation

# Create a virtual environment and activate it
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
```

## 🧪 Running the Project

```bash
# Run the pipeline
python main.py

# Launch the web app
python app.py

# Push prediction data
python push_data.py
```

## 🐳 Docker Deployment

```bash
# Build the Docker image
docker build -t network-security-system .

# Run the container
docker run -p 5000:5000 network-security-system
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request


