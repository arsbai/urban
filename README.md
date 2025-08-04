A computer vision system designed for urban street analysis that intelligently identifies and classifies pedestrians and cyclists in street scenes, serving urban flow, traffic, and street vitality research.

Features
Pedestrian and Cyclist Differentiation: Accurately distinguishes between pedestrians and bicycle riders
Motorcycle Rider Identification: Detects motorcycle riders with specialized handling logic
Street Vitality Analysis: Supports research on street-level activity and urban mobility patterns

Technical Implementation
The system is built on deep learning object detection frameworks (GluonCV) and employs several key technical innovations:
Bounding Box Relationship Analysis: Calculates spatial relationships between detected objects
Vertical Alignment Detection: Special algorithms to determine if a person is positioned on a vehicle
Centroid Distance Normalization: Distance between detection centers normalized by object size for scale-invariant assessment
