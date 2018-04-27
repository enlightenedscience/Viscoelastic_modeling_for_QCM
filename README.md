# Viscoelastic_modeling_for_QCM
Code for modeling viscoelastic properties of film deposited on quartz crystal microbalance.

The Voinova equations model changes in density, viscosity, and shear modulus of an adlayer film deposited on a quartz crystal microbalance. 

The Voinova equations come from eqns (24) and (25) in the paper by Voinova: Vionova, M.V., Rodahl, M., Jonson, M. and Kasemo, B., 1999. Viscoelastic acoustic response of layered polymer films at fluid-solid interfaces: continuum mechanics approach. Physica Scripta,
59(5), p.391.
The paper can be found here: https://arxiv.org/pdf/cond-mat/9805266.pdf

An implementation of these equations in Matlab can be found here: https://github.com/88tpm/QCMD/blob/master/Mass-specific%20activity/Internal%20functions/voigt_rel.m

The attached python code numerically solves a system of 2 simultaneous nonlinear equations for viscosity and shear modulus given values of frequency shift and energy dissipation.
