
# **Statistical Mechanics**


>[!comment] Core Philosophy with Statmech Notebooks
>Programming
>Computation > Handwritten in real world

```ad-example
title: Global References


N. G. van Kampen, Stochastic Processes in Physics and
Chemistry (Elsevier, 2007).

G. B. Arfken, H. J. Weber, and F. E. Harris, Mathematical
Methods for Physicists: A Comprehesive Guide (Academic
Press, 2011).

F. Reif, Fundamentals of Statistical and Thermal Physics
(McGraw-Hill, Inc., 1965).

M. Plischke and B. Bergersen, Equilibrium Statistical Physics
(World Scientific Publishing Co. Pte. Ltd., 2006).

R. K. Pathria, Statistical Mechanics (ButterworthHeinemann, 1996)

```



>[!To do]
>For all the following tasks, convert them into chaptered-notes. Integrate the problem sets within the notes:

![](https://i.imgur.com/mUKHiQG.png)


## Introduction

Provide a scientific or mathematical definition of the probability of an event/experimental outcome.


Provide an example of how a statistical treatment of data can improve the quality of life or how a misinterpretation of statistics can lead to large-scale inconveniences.





## Review of counting and probability

>[!notes] References
> vK 1, AR7 Chapter 23, RF 1.3



Provide definitions of a permutation and a combination in terms of factorials and binomial coefficients.
Give an example of each.

A random or stochastic variable X consists of a set of outcomes rxx and a probability distribution function
or PDF px. Provide the essential properties of a PDF (non-negativity and normalizability) when the set
of outcomes form a discrete and when the set of outcomes form a continuum

Describe how to evaluate the moments or mean values of a random variable X in terms of its PDF.

Describe how the cumulant generating function can be used to obtain the first cumulant (mean) and the
second cumulant (variance).









## Random Walk References RF 1.1–1.2, 1.4–1.6

>[!notes] References
> RF 1.1–1.2, 1.4–1.6


The simple random walk can be thought of as a sequence of independent realizations of a binary random variable. Give other examples where such a random sequence, such as LRRLRLLLRLR. . . , can be
important.



Given a symmetric random walk (p  q  1©2) with an exact number of steps N, give the probability that
the walk has k steps to the right. Show how the binomial distribution arises in the random walk problem.






Give the Stirling approximation. Give the central limit theorem and the required conditions for it to hold.




Discuss how the PDF of displacements in the random walk approaches a Gaussian distribution.



Very educational to do: Obtain the diffusion equation from the continuum limit of a random walk














## Statistical mechanics approach

>[!notes] References
> RF 2.1–2.5, 6.1–6



Specifying physical states (microscopic outcomes). Give examples of how to specify the microscopic state of
a single classical particle and several classical particles in terms of phase space coordinates. Give examples
of how to specify the microscopic state of a quantum particle (like a particle in a box, harmonic oscillator,
and an electron in a Coulomb potential) in terms of quantum numbers.





Statistical ensembles (macroscopic outcomes). Describe the microcanonical, canonical, and grand canonical ensembles in terms of the fixed (known) macroscopic variables, and a description of the associated
equilibrium condition.





Postulate of a priori probabilities. In a given statistical ensemble, when a given macroscopic variable
is fixed and the system is in equilibrium, it is postulated that each of the microstates compatible with
the constraint (or accessible states) occur with a given probability. Describe how these probabilities are
assigned in the microcanonical, canonical, and grand canonical ensembles.





Probability calculations. With the probability of measuring each accessible state at equilibrium being equal,
probability distributions are ratios of quantum numbers (quantum) or phase space volumes (classical)

















## Thermodynamic functions

>[!notes] References
> RF 3.11–3.12, 5.5–5




RF 3.4–3.5: Boltzmann defines the entropy S in terms of the number Ω of microstates accessible to a large macroscopic system: S k ln Ω with k being Boltzmann’s constant. The entropy SE depends on the energy E of the system because Ω ΩE. The absolute temperature T can be defined in thermodynamics as kT 1 ∂ln Ω©∂E. We often see the abbreviation β kT 1 







RF 3.8–3.12: The entropy can also depend on some other external extensive parameters x, like volume, particle number, magnetization, and polarization (extensive parameters increase proportionally with system size). When a system is initially at equilibrium and the parameter x is changed, the system is displaced from equilibrium and a generalized force X develops to counteract that change. The quantity X is an intensive parameter that is conjugate to the quantity x. Examples of these conjugate pairs of generalized forces and displacements are temperature–entropy, pressure–volume, chemical potential–particle number, magnetic field–magnetization, and electric field–polarization. The thermodynamic relation showing this relationship is βX ∂ ln Ω©∂x.








Summarize the laws of thermodynamics in terms of the entropy S, and internal energy E¯ U. 









Fundamental equation. Consider a quasi-static change for a large thermodynamic system so that dS d¯Q©T (the change in entropy is only due to the heat exchanged and no work is involved). Use the laws of thermodynamics and the conjugate pairs above to obtain the “fundamental thermodynamic relation” by writing dE as a sum of generalized forces times displacements (RF eqs. 3.12.3 and 5.1.5). With S SE, x, one obtains the different equations of st









Thermodynamic potentials. Make a table listing the properties of the different thermodynamic potentials: internal energy E, enthalpy H, Helmholtz free energy F, and Gibbs free energy G. Give their natural independent variables, their first derivatives with respect to their natural variables, and the “Maxwell relation” derived from each. The Maxwell relations can be used to relate different response functions. 









Response functions. Tabulate the following response functions with their corresponding definitions in terms of derivatives and their physical meanings in terms of experiments: heat capacities at constant volume and pressure, isothermal compressibility, volume coefficient of expansion or thermal expansivity. These are the thermal and mechanical response functions. Considering different conjugate variable pairs will give chemical, electric, and magnetic response functions.








## Microcanonical and canonical ensembles


>[!notes] References
> RF 6.3–6.6, 7.2






Discuss why the microcanonical and canonical ensembles lead to identical macroscopic averages in the limit
of thermodynamic (N  ) systems.









As an application of the canonical ensemble, show that the magnetic susceptibility in a paramagnet is
proportional to the applied field and inversely proportional to temperature (Curie’s law).









In addition to the partition function Z acting as a normalizing factor for the Boltzmann weights, it can also
be used to calculate average values in the canonical ensemble. Show how to calculate the average energy,
average squared energy, standard deviation in energy, and average generalized forces X (e.g., the average
pressure), as derivatives of the partition function.










Derive the ideal gas equation of state by considering a canonical ensemble of a classical monatomic gas in
a closed container of volume V and temperature T.







The entropy obtained in this classical model of a gas is incorrect because atoms are not distinguishable
(as assumed in the classical description). We will see later in the quantum treatment of an ideal gas that
a proper counting of microstates that accounts for the indistinguishability of atoms leads to the correct
expression for the entropy of an ideal gas