                 SELF-DRIVING CAR SYSTEM
                          │
                    Visual Input
                          │
                IMAGE ACQUISITION
                          │
        Cameras, LiDAR, Radar capture data
                          │
        ┌───────────────┬────────────────┐
        │                                │
  High Quality Input               Poor Quality Input
 (High resolution, lighting)      (Noise, blur, low light)
        │                                │
  Clear image details              Loss of important data
        └───────────────┬────────────────┘
                        │
                IMAGE PREPROCESSING
                        │
      Noise removal • Contrast enhancement • Resizing
                        │
                        ▼
              COMPUTER VISION FEATURES
                        │
   ┌───────────────┬───────────────┬───────────────┬───────────────┐
   │               │               │               │               │
Edge Detection  Object Detection  Lane Detection  Motion Detection
Road boundaries  Vehicles, people  Lane tracking   Moving objects
                        │
                        ▼
                FEATURE EXTRACTION
                        │
         Important information identified
                        │
                        ▼
                 DECISION MAKING
                        │
   ┌───────────────┬───────────────┬───────────────┐
   │               │               │
 Braking        Steering        Speed Control
Obstacle avoid   Lane follow     Traffic response
                        │
                        ▼
                RELIABLE NAVIGATION
                        │
   ┌───────────────┬───────────────┬───────────────┐
   │               │               │
 Safety         Accuracy       Real-time response
                        │
                        ▼
              SAFE AUTONOMOUS DRIVING
