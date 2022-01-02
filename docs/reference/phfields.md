# Photon Fields

The relevant photon fields for the interactions of the UHECRs are mainly the Cosmic Microwave Background ([CMB](https://en.wikipedia.org/wiki/Cosmic_microwave_background)) and the ultraviolet to optical to infrared background light (also called Extragalactic Background light, [EBL](https://en.wikipedia.org/wiki/Extragalactic_background_light)).

## Cosmic Microwave Background

The energy spectrum of CMB photons is that of a black body with temperature $T_0 = 2.7255 \pm 0.0006$ K [^Fixsen2009], with the result that at redshift $z=0$ shapes as:

$$
n_\gamma(\epsilon) = \frac{1}{\pi^2 (\hbar c)^3} \frac{\epsilon^2}{\exp(\epsilon / k_B T_0) - 1}
$$

where $\epsilon$ is the energy of the photon in the *laboratory frame*. 

The energy density of the CMB today is then $0.260$ eV/cm$^3$ which yields about 411 photons/cm$^3$.

???+ note

     At redshift $z$ the number of CMB photons is $(1 + z)^3$ larger than at $z = 0$ and their energies are $(1 + z)$ times higher. Then the energy spectrum at arbitrary z is given by:

The quantity $I_\gamma$ can be evaluated analytically, using the transformation $y = \exp(\epsilon / k_B T_0) - 1$, and it becomes [^Aloisio2013]:

$$
I_\gamma(\epsilon) = \frac{k_B T}{\pi^2 (\hbar c)^3} [-\ln(1-\exp(-\epsilon / k_B T_0)]
$$

[^Fixsen2009]: Fixsen D.J., 2009, ApJ, 707, 916 [[ADS](https://ui.adsabs.harvard.edu/abs/2009ApJ...707..916F)]
[^Aloisio2013]: Aloisio R., Berezinsky V., Grigorieva S., 2013, APh, 41, 73 [[ADS](https://ui.adsabs.harvard.edu/abs/2013APh....41...73A/abstract)]
