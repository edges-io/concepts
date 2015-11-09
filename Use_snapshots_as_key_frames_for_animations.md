# Use snapshots as key frames for animations

Usually key frames for animation is presented on a timeline. 

A different approach is to have key frames hold the current information of a frame/pose and only provide information about the transitions betweem the keyframes.

Using this approach key frames are presented as snapshots (with images) of the key frames and transitions contain information about duration and interpolation between the key frames.


![alt text](https://raw.githubusercontent.com/edges-io/concepts/master/images/key_frames_with_transitions.png "Key frames as snapshots")
