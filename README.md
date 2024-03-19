# TPoS_1024
✅ code for audio preprocessing  <br>


## Run
### Train audio encoder  
Locate downloaded weights in TPoS_1024/`pretrained_models`.  
🗂️ [Pre-trained weight](https://drive.google.com/drive/folders/11kDpSAp6wKyDU13rVT66dB0H2vJwXk5D)  

<br>

```bash
.
├── README.md
├── audio_encoder  
│   ├── datasets_final.py
│   ├── model_final.py
│   └── train_audio_encoder.py
│ 
├── configs
├── vggsound_curation
├── vggsound_test_curation
├── ldm
│   ├── data    
│   ├── lr_scheduler.py
│   ├── models
│   ├── modules
│   ├── sound
│   └── util.py
│ 
├── pretrained_models
│   ├── audio_encoder_23.pth
│   ├── map_model_23.pth
├── vggsound_curation 
└── inference.sh 

```

```
cd audio_encoder
python3 train_audio_encoder.py
```
