This app determines the size of the red nose from a proportion of the size of the face rectangle provided by the output of the haar cascades algorithm.

The position of the nose is determined by finding the midpoint of the bottom corners of 2 eyes, and then offsetting downwards by a fixed proportion of the face's size.

We previously attempted to use the angle between the eyes to determine the correct placement of the nose, but the simpler method worked better.

The app detects faces when held in all 4 orientations by flipping and transposing the input matrix. However, the detection seems a little unstable, even when the camera is held still. We were unable to identify the cause of this issue.

PS. we didn't do everything the day before the deadline, honest! Just some final touches :)