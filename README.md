# uTV

This is the public test set.

1) Download all the included apks.
2) Install all the apps except for uTV_Remote which will be installed on controlling/host phone.
3) Open uTV_Receiver app and note down the ip address and port no and start the service.
4) Enter the recorded ip address and port no in the remote app and connect.
5) Check the connection by pressing any button and see the top right indicator. (If green successful, if red connection error, if orange trying to connect)
6) Make sure that both the phones are on the same wifi network for the remote to work.
7) Set uTV_Home as the default browser.


# uTV_Remote and uTV_Receiver

These apps are for controlling the whole ssytem wirelessly. The receive initiates a background service that receives the inputs from remote app and handles system inputs.
Power button, mute button and home button are currently the only system input buttons. Rest input is handled individually by the compatible apps.


# uTV_Home

This is the basic launcher made to demonstrate the utilization of the receiver input for a comfortable navigation experience. The app is currently in alpha state and is made available for public testing at the moment. The launcher has a custom notification system which can be used by a number of apps.
The source codes will be available once the app is finalized to understant the ecosystem working.


# uTV_Music

This is the basic music app made to demonstrate the utilization of the receiver input, mainly the media control buttons. The app doesn't have any advanced features. It displays all tracks and doesn't group them based on artists or album. The app currently has a delay during launch and can be minimized by pressing home button, back button kills the app and the music playback. This app also implements the uTV_Home custom notification system which notifies of the currenlt being played track.
The source codes will be available once the app is finalized to understant the ecosystem working.
