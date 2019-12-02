# Track_msg
The message stored in Argo rosbag.

In Argo lightweight rosbag in ee904 server. I publish the topic
"/labels", message type "track_array_msgs/TrackArray".

This repo is for the use of it.

`track_array_msgs/TrackArray` is the array topic work as Markerarray, composed of 

argo_track_msgs/Track_msg[] labels

Another user-defined message `argo_track_msgs/Track_msg` to store labels ground truth in the bag.
Just include this two kind of messages to subscribe to the topic "/labels" in rosbag and get the ground truth.

[message info]
(https://hackmd.io/@dfl2h4FkRsCw7eiyFziYyQ/HJudE_anS?fbclid=IwAR1FcjaSMtrY0DEDgCQ9re5FzQl0tVHVMf9hzPBbPZqts9QUj83TUMSPEbc)
