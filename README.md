# Readme
This repo is a demonstration of material classification based on the Goldhammer-Herzfeld criterion. Herzfeld’s theory is based
on the classical (Lorentz) oscillator model of an atom. Herzfeld pointed out that electrons localized
around atomic nuclei constitute polarizable objects and that their internal dynamics in the dense
assembly of the element leads to local corrections to the polarizing tendency of any external field
impressed on the system.
He proposed that the corresponding element (viewed obviously as a collection of atoms)
becomes metallic when the frequency of the oscillator placed in this dense, dielectric medium
approaches zero; i.e. the valence electron is set free and the element—under those critical
conditions—acquires metallic status. Assuming long range interactions are isotropic, the relevant equation from the Lorenz&ndash;Lorentz or Claussius&ndash;Mosotti relation is then:

<img src="https://github.com/mtdg-wagner/goldhammer-herzfeld-elements/blob/master/CM_Relation.png" alt="C-M relation" width="400"/>

Where n is the index of refraction, epsilon is the dielectric constant, alpha is the atomic electronic polarizability, V is the molar volume, and R is the molar refractivity. When R/V = 1, n or epsilon diverge, which can only occur if the electrons are no longer bound to individual atoms (i.e. the system becomes metallic). 

Below, we reproduce one of the figures from the 2015 work of Friedrich Hensel, Daniel R. Slocombe and Peter P. Edwards [link](https://doi.org/10.1098/rsta.2014.0477) where they show this criterion's ability to separate metallic and non-metallic elements under ambient conditions on Earth. Our data's R/V values differ slightly from theirs probably due to a different source for the atomic polarizabilities or molar volumes. 

![HSE Fig 3](https://github.com/mtdg-wagner/goldhammer-herzfeld-elements/blob/master/RV_groups.png "Metallization of chemical elements")


# Files
* molar_refractivity.ipynb: Jupyter notebook containing data processing and plots
* Elemental_conductivities.xlsx: Ambient conductivity values for elements
* molar_refractivities.csv: Molar refractivities computed from Clausius&ndash;Mosotti relation, molar volumes, and R/V ratios. 

# Data sources
Atomic polarizability values are taken from the CRC Handbook of Chemistry and Physics 85th edition Chapter 10 page 168.
Molar volumes are taken from Mathematica's ElementData function via [periodictable.com](https://periodictable.com/Properties/A/MolarVolume.an.log.html).
Elemental conductivity values are available from Mathematica and [Angstrom Sciences](https://www.angstromsciences.com/elements-electrical-conductivity).

