# Wiretap Capacity

Capacity-achieving input distributions for the Vector Gaussian Wiretap channel with peak amplitude constraint

This folder contains one .mat file for each value of the variance of the additive Gaussian noise at the eavesdropper $\sigma_2^2 = {1.5, 10}$.

Each .mat file contains 6 (or 7) variables:

var1: variance of the additive Gaussian noise at the legitimate receiver

var2: variance of the additive Gaussian noise at the eavesdropper

A: values of the input peak amplitude constraint

Capacity: values of the capacity (in nats per channel use) corresponding to the values in variable A

N: number of dimensions (N = 1 if not specified)

opt_pos_input: matrix that reports the positions of the support points of the capacity-achieving distribution. Each row corresponds to a value of the peak amplitude constraint A.
Since the optimal input distribution has even symmetry, only nonnegative values are reported. Since A is always part of the solution, A will always be the value stored in the last column.

opt_prob_input: matrix that reports the probabilities of the support points of the capacity-achieving distribution. Each row corresponds to a value of the peak amplitude constraint A. Since the optimal input distribution has even symmetry, only the probabilities of nonnegative valued amplitudes are reported.

# Example of Secrecy-Capacity-Achieving Output Distributions

Evolution, as the input peak amplitude constraint $\textsf{R}$ increases, of the output probability density function of the legitimate user and the malicious receiver:

(for $N = 2$, $\sigma_1^2 = 1$, and $\sigma_2^2 = 1.5$)

https://user-images.githubusercontent.com/63358798/182670018-f6bd2fde-4821-4db6-aba4-1163b7460538.mp4

(for $N = 2$, $\sigma_1^2 = 1$, and $\sigma_2^2 = 10$)

https://user-images.githubusercontent.com/63358798/182670069-ffcaddb1-e456-4dca-b46b-e276a8b69696.mp4
