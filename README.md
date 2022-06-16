# lsl_in_unity_coroutines

Simple Unity 3D project with changing images on a canvas using [LabStreamingLayer](https://github.com/sccn/labstreaminglayer). This project is based on a very basic example meant for audio and video latency testing of EEG recordings in VR experiments using the LSL library for data streaming [lsl_in_unity](https://github.com/mvidaldp/lsl_in_unity). The scene and controller were modified to perform latency test on images being displayed via coroutine on a canvas in a 3D environment. 

Sample of images changing from an object's image (condition 1) to a fixation cross to a person's image (condition 2):

![Changing Background](https:// raw.githubusercontent.com/mvidaldp/lsl_latency_analysis/master/img/background.gif)

To customize the playing audio, the changing colors or the exposition or repetition times, as well as how the data is sent via LSL, modify the script: [Assets/Scripts/Controller.cs](https:// github.com/mvidaldp/lsl_in_unity/blob/master/Assets/Scripts/Controller.cs)

Use the LSL App [LabRecorder](https:// github.com/labstreaminglayer/App-LabRecorder/releases) while running the build or playing the scene on the editor to see and record the LSL data streams.

For the further latency analysis check out this repo: https: //github.com/mvidaldp/lsl_latency_analysis
