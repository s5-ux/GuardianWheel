+------------------+
|   Driver Camera  |
+------------------+
          |
          v
+------------------+
| Face Detection   |
| OpenCV + Dlib    |
+------------------+
          |
          v
+------------------+
| EAR + PERCLOS    |
| Calculation      |
+------------------+
          |
          v
+------------------+
| Fatigue Detected?|
+------------------+
      |       |
     No      Yes
      |       |
      v       v
 Continue  Alert Driver
 Driving      |
              v
      +------------------+
      | Driver Booking   |
      +------------------+
              |
              v
      +------------------+
      | Nearby Driver    |
      | Allocation       |
      +------------------+
              |
              v
      +------------------+
      | GPS Tracking     |
      +------------------+
