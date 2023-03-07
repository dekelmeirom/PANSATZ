# PANSATZ
This code was used to produce the results presented in the paper "PANSATZ: Pulse-based Ansatz for Variational Quantum Algorithms", which can be found on the arXiv at https://arxiv.org/abs/2212.12911

The code creates a pulse based ansatz, which pulses durations is its main parameter. The ansatz is used to find the ground energy of $H_2$, $HeH^+$ and $LiH$ molecules using the variational quantum eigensolver (VQE).
<br>
The ansatz in the code is built for fixed frequency superconducting quantum computer.
<br>
There are code examples to both simulate such device using properties from real devices and to access real hardware offered by IBM through the cloud. In both cases, a VQE algorithm is run and optimizes the pulses parameters in order to obtain schedules with shorter duration compared to gate based variational algorithms, which in turn creates less noise in the computation and allows the algorithm to converge to more accurate results.
In order to compare the PANSATZ results to the results obtains using the hardware efficient ansatz (HEA), a code to solve the same problem using HEA is also included.

Note that most of the results presented in the paper were produced using a computationally strong server, as simulating pulse dynamics is much more computationally expensive than simulating circuit built from quantum gates. Therefore, most of the final results are not presented in those notebooks, but can be reproduced using this code.

If you need access to the final results, or have more questions about the paper, you can contact us - 
<br>
Dekel Meirom - dekelmeirom@gmail.com
<br>
Steven H. Frankel - frankel@technion.ac.il

