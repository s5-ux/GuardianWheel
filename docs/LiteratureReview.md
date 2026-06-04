# Literature Review

Several studies have explored driver fatigue detection using computer vision and machine learning techniques.

1. Facial Landmark Detection:
   Researchers have used facial landmarks to track eye movement, blinking patterns, and head posture. Dlib and OpenCV are commonly used libraries for landmark extraction.

2. Eye Aspect Ratio (EAR):
   EAR is widely used for detecting eye closure duration. A significant decrease in EAR indicates drowsiness.

3. PERCLOS Method:
   Percentage of Eye Closure (PERCLOS) measures the proportion of time the eyes remain closed over a specific duration. It is considered one of the most reliable indicators of fatigue.

4. Deep Learning Approaches:
   Recent systems utilize CNNs and attention-based models to classify driver states from video streams. However, these models require large datasets and computational resources.

5. Real-Time Driver Monitoring:
   Modern solutions focus on real-time monitoring using webcams and embedded systems. These approaches improve accessibility and deployment feasibility.

The literature suggests that combining EAR and PERCLOS with real-time computer vision provides an effective and practical solution for fatigue detection.
