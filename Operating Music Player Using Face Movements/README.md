# Operating-Music-Player-Using-Face-Movements

This project is deeply centered on predicting the facial landmarks of a given face. Dlib’s prebuilt model
which is essentially an implementation of face detection, not only does a fast face-detection but also
allows us to accurately predict 68 2D facial landmarks.
Here, we use the head movements to operate music player.

Here, the play, pause, un-pause, stop, next buttons are associated with the keyboard keys, and the head
movements trigger these keys which in turn lead to a music being played, paused and stopped. The
movement of the head is again monitored by taking the nose as a tracking point and the direction in which
it moves is calculated accordingly from the initial position – anchor point (point of the nose tip when
activation occur). 
