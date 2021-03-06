Boids Birds
===========

![Boid Birds gif](https://media.giphy.com/media/M8uBtxH3bIyFigw18K/giphy.gif)

Boids Birds is a WebGL2 project that implements Boids algorithm, which is a 
famous algorithm that simulates flocking behavior observed in animals such as
birds. In addition to implementing the base algorithm, there is also a small
2D animation system that was implemented for frame based animation. The animation
system was used to give visual flare to the project by leveraging pixel art 
assets from the famous Nintendo Entertainment System game called Duck Hunt.

The project also utilizes WebVR so that a user on a mobile device can experience 
space in Virtual Reality. The application can be set to VR by tapping/clicking the
"Start VR" button in the bottom left sife of the screen. The VR mode works best 
with Chrome mobile web browser.

How To Run Project
==================

The best way to run the project is by using a local HTTP server. The 
steps to run this project will use Python's local web server package.

Navigate to the directory where the project has been cloned. Then, run
the following python command:

```
python3 -m http.server
```

Once the server is running locally, connect to the server on the port
that the server is using:

```
localhost:<port number>
```

Controls
========

* Click/tap the canvas to spawn a new duck/boid in the center of the screen.

* Click/Tap the "Start VR" button to change enter into VR mode. Works best on 
mobile Android devices.
