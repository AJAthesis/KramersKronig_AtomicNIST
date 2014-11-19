KramersKronig_AtomicNIST
========================

The included Mathematica notebook demonstrates a numerical method for calculating the real part f1 of the atomic scattering form factor by using a Kramers-Kronig transformation on the imaginary part f2. These calculations are compared to the tabulated values from http://www.nist.gov/pml/data/ffast/index.cfm

The method employs an integration strategy that seems to work well for nearly all elements and energies, but does so at the expense of sometimes being slow and not always fully converging.

The main draw of this approach is that provides a straightforward starting point to performing Kramers-Kronig transformations on measured x-ray absorption data for any absorption edge. Although not implemented in this demonstration, it is simple to join appropriate x-ray absorption data with the tabulated values of f2 and then use this method to find f1 for the investigated material. 
