\## My Understanding



To avoid the limitations of public-key cryptography, especially the possibility

of future quantum computers breaking current mathematical-based methods, BB84

provides a way for A and B to establish a shared secret key using quantum states.



The main things involved are the \*\*bit\*\* and the \*\*basis\*\*.



A encodes each bit (0 or 1) using a randomly selected basis:



\*\*Rectilinear (+) or Diagonal (×)\*\*. B also randomly chooses a basis to measure

each photon, so B does not initially know which basis A used.



After the transmission, A publicly announces only the bases. B compares them

with the bases chosen by B, and they keep the bits where their bases matched

while discarding the rest. These remaining bits form their raw shared key.



\### Security Against an Eavesdropper



If an eavesdropper (\*\*adversary\*\*) tries to intercept the photons, the

eavesdropper also has to guess the basis. Measuring with the wrong basis can

disturb the quantum state and introduce detectable errors.



The \*\*No-Cloning Theorem\*\* also prevents the eavesdropper from making perfect

copies of unknown quantum states without disturbing them.

