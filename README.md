\*\*Bot\*\*Ctrl**

This app sends one byte commands via Bluetooth.

Ascii byte codes sent for buttons: q (Left Half turn), e (Right Half turn), w (Forward), z (Reverse), a (Left), d (Right), h (Stop), 1 (F1), 2 (F2), etc... The F button codes are ASCII chars as are the the others.   Send the line BUTTONBUZZ to make the device vibrate and BOTBEEP to make the app beep. The App keeps the last 100 messages set. There is also a command to make the app say text sent by your robot - SAYIT~Hello World. The Speak button allows for voice control of your robot. It translates the words "Forward", Reverse, Back, Left, Right, Stop and Halt into the correct button command. Any words that it does not know are sent to the robot with a leading '*' and a trailing '.'   e.g. You say "hello", the app will send "*hello." via the serial bluetooth stream.   

ai2.appinventor.mit.edu/?galleryId=4644705354907648


