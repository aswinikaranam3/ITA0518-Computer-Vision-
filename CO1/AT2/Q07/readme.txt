                IMAGE WITH POOR CONTRAST
                        │
              Uneven Illumination
                        │
        ┌───────────────┼────────────────┐
        │                                │
   IMAGE FORMATION MODEL          EFFECT ON IMAGE
        │                                │
 f(x,y) = i(x,y) × r(x,y)         Low visibility
 (Illumination × Reflectance)     Washed out regions
        │                         Dark shadows
 Uneven lighting i(x,y)           Loss of details
 causes variation
        │
        ▼
            CONTRAST PROBLEM
                        │
        ┌───────────────┼────────────────┐
        │                                │
        CAUSES                         EFFECTS
        │                                │
 Non-uniform light               Low dynamic range
 Shadows & highlights            Poor feature detection
 Sensor limitations              Difficult analysis
                        │
                        ▼
               CORRECTIVE MEASURES
                        │
   ┌───────────────┬───────────────┬───────────────┐
   │               │               │               │
 Histogram       Filtering     Illumination     Image Capture
 Equalization    (smoothing)   Correction       Improvement
   │               │               │               │
 Enhance contrast Remove noise  Normalize light  Proper lighting
 Stretch levels   Improve clarity Homomorphic    Uniform exposure
                                      filtering
                        │
                        ▼
                 ENHANCED IMAGE
                        │
      Better contrast + improved visibility
