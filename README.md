# Rotation Optimization for 3D cone trajectory


## Develop Plan
1. Input `base_k`, rotation around k-space center, rotation around central axis. Rotate the `base_k` and match the calculation of the Siemens sequence.

2. Test if operation differentiable: gridding of full trajectory using `MIRtorch` or `torchkbnufft`, calculate summation and try back propogation.

3. Calculate more complex metrics


## Optimization Ideas
1. Optimize for point distribution on single shell and interleave between different shells.

2. Optimize the uniformity of gridding result in certain regions.
