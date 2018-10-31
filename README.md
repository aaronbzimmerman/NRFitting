# NRFitting

## Preamble
The purpose of this repository is to collect and share code associated with analyzing the output of numerical simulations of binary black holes (BBHs). Initially we will be interested in fitting quantities which oscillate, but which also change the frequency and amplitude of these oscillations. At early times in a simulation, these quantities may be modelled by oscillators whose parameters slowly vary, using adiabatic or two-timescale approximations. At late times in a simualtion, the frequency and amplitude of oscillations may be changing to rapidly it is hard to say that the underlying model of an oscillator makes sense.

Our initial efforts will be in developing methods to extract cycle-averaged frequencies and other parameters, subtract biasing due to the slow modulation of the oscillator model, and/or create robust fits for these oscillator models.
