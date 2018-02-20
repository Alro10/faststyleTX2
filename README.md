# faststyleTX2

This repository shows how to run fast style transfer on NVIDIA Jetson TX2.

# Dependencies 

Python 2.7
Tensorflow 1.0.0 (If training: with GPU support + CUDA + cuDNN recommended) (see this: https://github.com/AlexanderRobles21/installTensorFlowJetsonTX)
Numpy
OpenCV 3.3 (https://github.com/jetsonhacks/buildOpenCVTX2)
*This dependency can be easily switched to your favourite image I/O library by tweaking the wrapped functions in utils.py. Note it's still needed for stylize_jetsoncam.py

Download original repository:

$ git clone https://github.com/ghwatson/faststyle

Download stylize_jetsoncam.py from this repository and save in home/faststyle

# Run using onboard camara Jetson TX2!

$ python stylize_jetsoncam.py

 
