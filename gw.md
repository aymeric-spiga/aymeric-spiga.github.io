---
layout: default
mathjax: true
---

### Brunt Vaisala

Exner function 
$$ \Pi  = \left( \frac{P}{P_0} \right)^{\kappa} \qquad \kappa = R/c_p $$

Potential temperature 
$$ \theta = T \Pi^{-1} $$

Vertical gradient of potential temperature *in an isotherm profile*

$$ \theta_z = - T \kappa \Pi^{-1}  \left( \frac{P}{P_0} \right)^{-1} \frac{P_z}{P_0} $$

$$ \theta_z = \kappa \theta \frac{\rho g}{P} $$

$$ \theta_z = \kappa \Pi^{-1} \frac{g}{R} $$

$$ \frac{N^2}{g} = \frac{\theta_z}{\theta} = \frac{g}{c_p T} $$

$$ N^2 = \frac{g^2}{c_p T} $$

### Link between temperature and density perturbations

Fritts and Alexander 2003 equation 12

$$ \frac{\theta'}{\bar{\theta}} = \frac{1}{c_s^2} \frac{P'}{\bar{\rho}} - \frac{\rho'}{\bar{\rho}} $$

Sound waves are faster; neglect compressibility terms

$$ c_s \rightarrow \infty \qquad \Rightarrow \qquad \frac{\rho'}{\bar{\rho}} = - \frac{\theta'}{\bar{\theta}} $$

### Saturation

Temperature profile is close to neutral. Assume linear formalism and WKB (background state varies slowly over a wave cycle)

$$ \bar{\theta}_z + {\theta'}_z = 0$$ 

Use definition of static stability on the first term

$$ {\theta'}_z = -\frac{N^2 \bar{\theta}}{g} $$

Inject a complex monochromatic Fourier mode

$$ i m \theta' = -\frac{N^2 \bar{\theta}}{g} $$ 

Put apart phase considerations

$$ \frac{|\theta'|}{\bar{\theta}} = \frac{N^2}{m g} $$ 

### Vertical wavenumber

Assume medium-frequency waves (consider intrinsic frequency); Fritts and Alexander 2003 equation 32

$$ N \ll \hat{\omega} \ll f \qquad \Rightarrow \qquad m = \frac{k_H N}{\hat{\omega}} = \frac{N}{\bar{u}-c}$$

### Conclusion

Combine all results

$$ \frac{|\rho'|}{\bar{\rho}} = \frac{|\theta'|}{\bar{\theta}} = \frac{N}{g} (\bar{u}-c) = \frac{\bar{u}-c}{\sqrt{c_p T}} $$

