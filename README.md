# Response test.
Simple HTML / JavaScript application for measuring reponse time for a remote desktop.

Best be used in combination with [screenkey](https://github.com/wavexx/screenkey).

## How to use.
* Open the webpage on a remote machine.
* On your local machine, open screenkey.
* On your local machine, record the screen with 60+ FPS.
* Press the space bar a couple times.
* Use ffmpeg to extract the individual frames from the recording.
* Count the number of frames between input and the change of color.
