# LiveStream-WebRTC-Flask-OpenCV

**My [medium story](https://medium.com/@supersjgk/building-a-live-streaming-app-using-flask-opencv-and-webrtc-8cc8b521fa44) contains the following:**
* The detailed tutorial on how to build this app from scratch.
* How to customize the app for your own needs.
* Instructions to follow.
* Troubleshooting tips.

#### Prerequisistes
* Webcam/ IP camera
* A server machine and a client machine (smartphone, pc, etc.) connected to the same network.

  `pip install Flask`

  `pip install opencv-python-headless`

  `pip install aiortc`

#### To run
* Server Side<br>

  `git clone https://github.com/supersjgk/LiveStream-WebRTC-Flask-OpenCV` <br>

  `cd src`<br>

  `python server.py` OR `python3 server.py`

* Client Side<br>
To view the live stream from a Server's webcam/IP camera in a client machine, simply open a web browser and type `http://127.0.0.1:<port>/` (client on same machine) OR `http://<server_IP_address>:<port>/` (client on different machine). 

#### Note
* Camera access should be enabled on Server
* Client machine should be connected to the same network as the server machine.
* Set host and port according to your needs. Port should not be running any other processes (details to fix conflicting ports in story)


