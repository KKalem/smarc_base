# smarc_base
Basic utils for controlling the AUVs and for dead reckoning

# smarc_line_following
Unpolished.

After cloning smarc_base, do 
$ git submodule --init --recursive
to get everything.

waypoints.csv contains the waypoints to follow. In world coordinates.

Run line follower with:
$ python3 line_planner.py

PIDs tuned for LoLo, probably won't work with SAM. Didn't try.

Change pose_topic in line\_planner.py to another 'Odometry' publisher if needed.
