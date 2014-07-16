itf_talk
==========

itf_listen uses Google's text-to-speech API to convert a string of textt into several audio files.

Because the service is limited to strings of 100 characters, the node will cut up longer texts into pieces, download the separate MP3 files, and then play them in sequence.

Prerequisites
-------------
None

Usage
-----
Clone into your catkin workspace, to run:

rosrun itf_talk itf_talk.py

It will monitor the /itf_talk topic for input. 

Notes
-----
If at any time Google decides to shutdown / switch API's this code will probably require some changes.
