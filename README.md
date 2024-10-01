brain-mri-metastasis-segmentation/
├── data/
│   └── train/                  # Training data
│   └── test/                   # Testing data
├── models/
│   └── nested_unet_model.h5    # Trained Nested U-Net model
│   └── attention_unet_model.h5 # Trained Attention U-Net model
├── app/
│   └── fastapi_app.py          # FastAPI backend code
│   └── streamlit_ui.py         # Streamlit frontend code
├── src/
│   └── preprocess.py           # Preprocessing script (CLAHE, normalization)
│   └── train.py                # Script to train both models
│   └── evaluate.py             # Script to evaluate the models
├── README.md                   # Project overview
├── requirements.txt            # List of dependencies
└── report.pdf                  # Brief report summarizing the task, challenges, results
