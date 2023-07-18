The objective of this project is to demonstrate your skills in creating an AI model that is proficient in
lip-syncing i.e. synchronizing an audio file with a video file. Your task is to ensure the model is accurately
matching the lip movements of the characters in the given video file with the corresponding audio file.
The input files used are:
Video - https://openinapp.co/5cwva
Audio - https://openinapp.co/o9vuj

Used Wav2Lip to lipsync using pretrained model downloaded using https://github.com/Rudrabha/Wav2Lip.

Prerequisites:
1. Python 3.6
2. Install necessary packages using pip install -r requirements.txt
   packages installed are:
   librosa==0.8.0
   numpy==1.17.1
   --upgrade pip
   opencv-python
   opencv-contrib-python
   torch==1.1.0
   torchvision==0.3.0
   tqdm==4.45.0
   numba==0.48


Lip-syncing videos using the pre-trained models (Inference) :
The result is saved in results/result_voice.mp4.

