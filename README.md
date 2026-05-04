deep-drought-uav/
│
├── dataset/
│   ├── images/
│   ├── masks/
│
├── outputs/
│   ├── predictions/
│
├── models/
│   ├── unet_drought.pth
│   └── unet_drought_final.pth
│
├── scripts/
│   ├── padding.py
│   ├── tiling.py
│   ├── mask_generation.py
│   ├── train_unet.py
│   ├── predict.py
│
├── README.md
├── requirements.txt



Project Flow:
Drone Image → Tiling → Mask (ExG) → U-Net → Prediction
