Molecular and Atomic Orbitals in Quantum Chemistry
====================================================

Introduction
------------
Molecular and atomic orbitals are fundamental concepts in quantum chemistry. They describe the distribution of electrons around atoms and molecules. Gaussian orbitals are often used to approximate these orbitals due to their computational efficiency.

Atomic Orbitals
----------------
Atomic orbitals represent the probability distribution of an electron in an atom. They are characterized by quantum numbers: principal quantum number (n), azimuthal quantum number (l), magnetic quantum number (m), and spin quantum number (s). The notation for an atomic orbital is represented as:

.. math::
    \psi_{n,l,m}(r, \theta, \phi)

where:
- :math:`n` represents the principal quantum number,
- :math:`l` represents the azimuthal quantum number,
- :math:`m` represents the magnetic quantum number,
- :math:`r`, :math:`\theta`, and :math:`\phi` represent the spherical coordinates.

Molecular Orbitals
-------------------
Molecular orbitals describe the distribution of electrons in molecules. They are formed by the linear combination of atomic orbitals (LCAO). In the context of Gaussian orbitals, molecular orbitals are often expressed as linear combinations of atomic orbitals using the superposition principle:

.. math::
    \Psi_i = \sum_{j} c_{ij}\psi_{j}

where:
- :math:`\Psi_i` represents the molecular orbital,
- :math:`c_{ij}` represents the coefficients of atomic orbitals,
- :math:`\psi_{j}` represents the atomic orbitals.

Gaussian Orbitals
------------------
Gaussian orbitals are mathematical functions used to approximate atomic and molecular orbitals. They are characterized by parameters such as the center, width, and exponent. The general form of a Gaussian orbital is given by:

.. math::
    \phi(\mathbf{r}) = N\cdot e^{-\alpha |\mathbf{r} - \mathbf{R}|^2}

where:
- :math:`N` is the normalization constant,
- :math:`\alpha` is the exponent,
- :math:`\mathbf{r}` represents the position vector,
- :math:`\mathbf{R}` represents the center of the orbital.



Explanation of Notation
------------------------


Usage in Computational Chemistry
---------------------------------


