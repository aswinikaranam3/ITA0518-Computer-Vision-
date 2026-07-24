                     IMAGE DISTORTION (Improper Image Formation)
                                      │
        ┌─────────────────────────────┼─────────────────────────────┐
        │                             │                             │
   Lens Issues                    Noise                        Sampling Issues
        │                             │                             │
 ┌──────┼──────┐               ┌──────┼──────┐              ┌───────┼────────┐
 │             │               │             │              │                │
Blur     Geometric Distortion  Thermal   Shot Noise     Aliasing      Low Resolution
 │        (Barrel/Pincushion)   Noise                     │                │
 │                                   │                   │                │
 ↓                                   ↓                   ↓                ↓
Unclear Image                  Grainy Image        Jagged Edges      Pixelation

        │                             │                             │
        └───────────────┬─────────────┴───────────────┬─────────────┘
                        │                             │
                Quantization Error              Illumination Issues
                        │                             │
               Low Bit Depth                   Non-uniform Light
                        │                             │
                        ↓                             ↓
                  Banding Effect               Over/Under Exposure

                                      │
                                      ↓
                                IMPROVEMENTS
                                      │
        ┌─────────────────────────────┼─────────────────────────────┐
        │                             │                             │
   Improve Optics                Reduce Noise               Proper Sampling
        │                             │                             │
 Better Lens                  Filtering (Median,        High Resolution
 Calibration                  Gaussian)                 Anti-aliasing
 Deblurring                   Better Sensors            Nyquist Rule

        │                             │                             │
        └───────────────┬─────────────┴───────────────┬─────────────┘
                        │                             │
                 Better Quantization           Illumination Fix
                        │                             │
                Increase Bit Depth             Uniform Lighting
                Better ADC                    Histogram Equalization

                                      │
                                      ↓
                                 FINAL RESULT
                           ✔ Clear & Accurate Image
