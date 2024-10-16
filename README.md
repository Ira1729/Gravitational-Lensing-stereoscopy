# Gravitational-Lensing-stereoscopy
Gravitational lensing has allowed us to see galaxies behind clusters of galaxies that provide gravitational
lensing with a large distance between lenses. A remarkable image has been obtained with the James Webb
Space Telescope (JWST) (Lea, 2023;Kelly, 2022), showing three images lensed by galactic cluster RX J2129
of a galaxy containing Type Ia supernova AT 2022riv (cf. (Morgan, Chartas, Malm et al., 2001)). Due
to their different path lengths, two of the three images are 320 days and 1000 days after the first. This
allowed the time course of the lensed supernova to be ascertained. But it also allows stereoscopy, as little
displacement of stars in the distant galaxy is expected over these astronomically short periods. Thus, the
prospect presents itself of making stereo pairs from the three images of a distant galaxy.

The code is written to convert the three images into stereo pairs, the process involves measuring initial disparity in images, converting the added images to same size, converting to greyscale and finding their centroid. 
Then we proceed to find the minimum norm by using an algorithm
following MSE (mean squared error method).
