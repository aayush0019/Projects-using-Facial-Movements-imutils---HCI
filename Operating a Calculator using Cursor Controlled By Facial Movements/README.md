# Operating-a-Calculator-using-Cursor-Controlled-By-Facial-Movements 

Activation: The application is activated by using EAR (eye aspect ratio). On blinking both the eyes
the EAR reduces and the application is activated.

Anchor Point and Movement of the Cursor: An anchor point is selected from the landmarks
generated on the face. There are five anchor points on a human face: Left eye center, Right eye center,
Nose-tip, Left mouth corner, Right mouth corner and Chin. We selected nose tip for the same. As the
nose moves (left, right, up, down) the cursor moves in the same direction and we can compute the
distance by the amount it has moved from its initial position (anchor point).

Selection: The selection of any unit on the calculator is done by using the mouth aspect ratio (MAR).
Once the MAR increases beyond a threshold, the value on the cursor is gets selected.
