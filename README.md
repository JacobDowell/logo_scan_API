DowellLogoScan/
│
├── main.py               # The main entry point to start the FastAPI server
├── api/                  # Folder for organizing API routes
│   ├── init.py       # Makes this folder a Python package
│   ├── auth.py           # Contains authentication-related endpoints
│   ├── upload.py         # Contains upload-related endpoints
│   └── search.py         # Contains search-related endpoints
├── config/               # Folder for configurations
│   ├── init.py
│   └── db.py             # Contains MongoDB connection setup
├── models/               # Folder for response models and data models
│   ├── init.py
│   ├── responses.py      # Response models for structured JSON responses
│   └── extractor.py      # Feature extraction logic
├── static/               # Folder for main html, upload html and search html
    └── index.html        # main Site
    └── search.html       # Search ( Comparison) Site
    └── upload.html       # Upload Site
└── config.json           # Configuration file for MongoDB and other settings
└── requirments.txt       # Pakages nee to run this application


#Run Command 
uvicorn main:app
