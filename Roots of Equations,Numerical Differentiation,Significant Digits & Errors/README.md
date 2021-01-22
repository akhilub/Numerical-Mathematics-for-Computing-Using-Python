Q.1 In the last 4 seconds of its survival, the velocity (v) profile of chandrayaan-2 showed
fluctuation as it approaches towards the moon surface, given by the following function of
time (t):

v = 5 cos(10t) + t<sup>-5</sup> - 2t<sup>-5</sup> -6t + 10

a) Report the Condition Number (C.N) of the function at t=2.2 s.

b) Utilize in-built analytical differentiation commands in python (under scipy library)
and 15 significant digits to find the acceleration (a) in the last 4 seconds. Plot both
velocity (v) and acceleration (a) w.r.t to time t. Using second derivative, find all
extrema (local maxima and minima) in velocity reached by chandrayaan-2 in this time
interval. Lastly, find the global minima in velocity.

c) Using 15 significant digits, calculate numerically the acceleration of chandrayaan-2 at
global minima using forward finite-divided difference approximation, backward finite-divided difference approximation and Centered finite-divided difference
approximation with step size (h) = 0.2.

d) Evaluate the effect of round off and truncation errors in acceleration (a) at global
minima using Centered finite-divided difference approximation achieved by
increasing the number of significant digits from 1 to 15 and step size from 2x10<sup>-1</sup>
to 2x10<sup>-15</sup> respectively. Consider value obtained for acceleration (a) at global minima
using in-build function of python in sub-question (b) as true value. Based on this, plot
a log of total error vs log of step size and locate point of diminishing returns with
respect to round off and truncation errors in evaluating acceleration (a) at global
minima.
