Antony Gozes

People Detection and Follow

Dependencies :

Python 3.6.4
NumPy 1.14.0
OpenCV-Python 3.4.1
pedestrian.xml - must be in the program domain ( included here ).


Notes :

User Interface -

right click on video screen - save screenshot of the current frame, the screenshot is saved in the program domain.

left click on video screen - redetect people with the current frame.


Other Options -

record video - in the code the boolean variable 'write_output_video' can be modified to record video of the session,
the video is saved in the program domain.

video source - the string type variable 'video' is holding the video name or path
( can be converted to integer for other sources like camera ).

exit from session - press esc to exit.