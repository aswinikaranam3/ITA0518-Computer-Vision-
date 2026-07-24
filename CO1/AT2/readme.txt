                    MEDICAL IMAGING SYSTEM
                             │
                             ↓
                     IMAGE ACQUISITION
                             │
                             ↓
                        QUANTIZATION
                (Analog → Digital Conversion)
                             │
         ┌───────────────────┼───────────────────┐
         │                   │                   │
     Low Bit Depth     Poor Gray Levels     Rounding Errors
     (e.g., 8-bit)         │                   │
         │                 │                   │
         └──────────────┬──┴──────────────┬────┘
                        │                 │
                        ↓                 ↓
                 INFORMATION LOSS   INTENSITY DISTORTION
                        │                 │
        ┌───────────────┼───────────────┐ │
        │               │               │ │
   Banding Effect   Loss of Contrast  Detail Loss
        │               │               │
        └───────────────┼───────────────┘
                        │
                        ↓
        LOSS OF CRITICAL DIAGNOSTIC INFORMATION
                        │
        ┌───────────────┼────────────────────────┐
        │               │                        │
   Tumor not visible  Tissue differences   Edge details lost
   (missed diagnosis) not distinguishable  (poor segmentation)

                        │
                        ↓
                   IMPROVEMENTS
                        │
     ┌──────────────────┼──────────────────┐
     │                  │                  │
 Increase Bit Depth   Better ADC     Image Processing
   (12–16 bit)        (High precision)  (Enhancement)
     │                  │                  │
     └──────────────┬───┴──────────────┬───┘
                    │                  │
                    ↓                  ↓
          PRESERVE INTENSITY     BETTER DIAGNOSIS
