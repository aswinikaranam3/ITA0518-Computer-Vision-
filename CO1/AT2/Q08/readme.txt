            MEDICAL IMAGING SYSTEM
                        │
                 Image Acquisition
                        │
                 Quantization Process
                        │
        Convert continuous intensity → discrete levels
                        │
        ┌───────────────┼────────────────┐
        │                                │
   PROPER QUANTIZATION         IMPROPER QUANTIZATION
        │                                │
 Many intensity levels             Few intensity levels
 High bit depth (12/16-bit)        Low bit depth (4/8-bit)
 Smooth grayscale                  Loss of detail
        │                                │
        └───────────────┬────────────────┘
                        │
                 EFFECT ON IMAGE
                        │
   ┌───────────────┬───────────────┬───────────────┐
   │               │               │               │
 Loss of contrast  Banding effect  Hidden details  Noise impact
 Similar tissues   False edges     Missed lesions  Misinterpretation
                        │
                        ▼
           LOSS OF DIAGNOSTIC INFORMATION
                        │
   ┌───────────────┬───────────────┬───────────────┐
   │               │               │               │
 Tumor not visible Tissue overlap Wrong diagnosis Reduced accuracy
                        │
                        ▼
               CORRECTIVE MEASURES
                        │
   ┌───────────────┬───────────────┬───────────────┐
   │               │               │               │
 Increase bit depth  Use 12/16-bit  Contrast enhance  Calibration
 Preserve details    Medical standard Windowing       Proper scaling
                        │
                        ▼
              IMPROVED DIAGNOSTIC QUALITY
