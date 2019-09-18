# -Color-multi-focus-image-fusion-using-Guided-and-Bilateral-filter-based-on-focus-region-detection-in
This code impliments a multi-focus color image fusion method based on focus region detection with edge preseve using bilateral filter and guided filter in discrete wavelet transform (2DWT). Firstly, a novel focus region detection method is estimated, which uses guided filter to refine the rough focus maps obtained by bilateral filter and difference operator. Then, An initial decision map is got via the pixel-wise maximum rule, and optimized to generate final decision map by using guided filter again. Finally, the fused image is obtained by the pixel-wise weighted-averaging rule with the final decision map via inverse transform.
