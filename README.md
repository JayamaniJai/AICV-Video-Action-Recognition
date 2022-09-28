# AICV-Video-Action-Recognition
X3D for Video Recognition

I have choosen X3D model to find action from video containing multiple people(eg. normally cctv footage have multiple people performing mutiple actions). All of them are performing different actions. To detect and localize each person in the video and classify activities being performed by each individual is broad research area, X3D works better to overcome Spatio-Temporal Detection.

X3D achieves state-of-the-art performance while requiring 4.8x fewer flops and 5.5x fewer params with multiply-adds and parameters for similar accuracy compared to SlowFast model.
<img width="860" alt="Screenshot 2022-09-28 at 5 30 44 PM" src="https://user-images.githubusercontent.com/36875428/192743984-9bafa66e-0c91-4821-a534-fcf0d0716130.png">

i have explored different kinf of action recognition models(SlowFast,4D CNNs, single frame CNN, Mobile Video Networks (MoViNets)) and like libraries PyTourchVideos, Tenserflow Lite, Keras.

Due to time contraint,only did experiment on slowfast and X3D models using PytourchVideos library.Both models pretrained on the Kinetics 400 dataset and tested using smaple vidoes from kinetics 400 dataset.

X3D model perform well and provide similar accuracy 73 to 80 %, the processing time is prety much fast in cpu.
