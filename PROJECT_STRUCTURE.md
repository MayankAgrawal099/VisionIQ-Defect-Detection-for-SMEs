# VisionIQ Project Structure

## Recommended Project Organization

```
Final 2/
├── src/                          # Source code (core application)
│   ├── __init__.py
│   ├── app.py                    # Flask application
│   ├── config.py                 # Configuration
│   ├── camera.py                 # Camera handling
│   ├── yolo_detector.py          # YOLO detection
│   ├── database.py               # MongoDB operations
│   └── logger.py                 # Logging configuration
│
├── scripts/                      # Utility scripts
│   ├── train_custom_model.py     # Model training
│   ├── train_fewshot.py          # Few-shot training
│   ├── clear_history.py          # Clear database
│   ├── test_camera.py            # Camera testing
│   └── split_dataset.py          # Dataset splitting
│
├── models/                       # Trained models (optional)
│   └── .gitkeep
│
├── bottle_defect_dataset/        # Training dataset
│   ├── data.yaml
│   ├── images/
│   │   ├── train/
│   │   ├── val/
│   │   └── test/
│   └── labels/
│       ├── train/
│       ├── val/
│       └── test/
│
├── logs/                         # Application logs
│   ├── visioniq.log             # Main log
│   ├── errors.log               # Error log
│   └── detections.log           # Detection log
│
├── templates/                    # HTML templates
│   ├── base.html
│   ├── index.html
│   ├── dashboard.html
│   └── history.html
│
├── static/                       # Static assets
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
│
├── docs/                         # Documentation
│   ├── README.md
│   ├── TRAINING_GUIDE.md
│   ├── FEW_SHOT_LEARNING_GUIDE.md
│   ├── CLEAR_ALL_DATA.md
│   └── ...
│
├── tests/                        # Tests (optional)
│   └── .gitkeep
│
├── uploads/                      # Upload directory
├── requirements.txt              # Dependencies
└── .gitignore                    # Git ignore
```

## Current Structure (To Be Reorganized)

Current files are in the root directory. This structure keeps everything organized and maintainable.
