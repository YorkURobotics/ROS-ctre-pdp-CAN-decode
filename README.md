# ROS CTRE Power Distribution Panel CAN Decode & Control

A ROS node to decode the CAN frames from the CTRE Power Distribution Panel. 

Development is still in progress. 

# TODO
- Add a service to clear sticky faults, and reset total energy
- Extremely high CPU usage (100% on a single thread). Troubleshoot that. Looks like its related to the way I did sleep in the program
- Refactor code to reorganize it better
- Temp data seems to be a bit high - will need to verify that
