# Wiretap Capacity

Capacity-achieving input distributions for the Wiretap channel with peak amplitude constraint

This folder contains one .mat file for each value of the variance of the additive Gaussian noise at the eavesdropper \sigma_2^2 = {1.5, 10}.

Each .mat file contains 5 variables:

var1: variance of the additive Gaussian noise at the legitimate receiver

var2: variance of the additive Gaussian noise at the eavesdropper

A: values of the input peak amplitude constraint

Capacity: values of the capacity (in nats per channel use) corresponding to the values in variable A

opt_pos_input: matrix that reports the positions of the support points of the capacity-achieving distribution. Each row corresponds to a value of the peak amplitude constraint A.
Since the optimal input distribution has even symmetry, only nonnegative values are reported. Since A is always part of the solution, A will always be the value stored in the last column.

opt_prob_input: matrix that reports the probabilities of the support points of the capacity-achieving distribution. Each row corresponds to a value of the peak amplitude constraint A. Since the optimal input distribution has even symmetry, only the probabilities of nonnegative valued amplitudes are reported.
