# WildSentry
Uses neural networks and reinforcement learning to detect wildfires, collect information about the environment, and deploy an agent-based model on how best to stop the spread. 


WildSentry employs a three-step process to identify and mitigate wildfires:

1. Initial wildfire detection involves satellite imagery analysis using ResNet.
2. Upon detecting a wildfire, the image undergoes additional scrutiny with YOLO to pinpoint crucial areas, such as potential fuel sources like trees and the wildfire's precise location.
3. An artificial fire simulation-trained reinforcement learning algorithm determines the most effective strategy for extinguishing the fire.

Please note this is a work in progress! Code will be updated accordingly. 
