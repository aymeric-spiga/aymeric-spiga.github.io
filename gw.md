---
layout: default
mathjax: true
---

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

Fritts and Alexander 2003 equation 12

$$ \frac{\theta'}{\overline{\theta}} = \frac{1}{c_s^2} \frac{P'}{\overline{\rho}} - \frac{\rho'}{\overline{\rho}} $$

$$ \frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} = 1+\frac{e^{-2\pi}}{1+\frac{e^{-4\pi}}{1+\frac{e^{-6\pi}}{1+\frac{e^{-8\pi}}{1+\ldots} } } } $$

Les forces de pression horizontales se calculent comme la force de pression verticale dans la démonstration de l'équilibre hydrostatique. La force de pression s'exerçant sur une surface $S$ est normale à cette surface et vaut $P \, S$. Pour une parcelle d'air de volume $\delta x \, \delta y \, \delta z$ (figure \ref{fig:pres}), la force de pression totale dans la direction ($Ox$) vaut
\[ F_P^* = P(x) \, \delta y \, \delta z - P(x+\delta x) \, \delta y \, \delta z = - \frac{\partial P}{\partial x} \, \delta x \, \delta y \, \delta z \]
La force de pression {\em massique} est donc
\[F_P = \frac{F_P^*}{\rho \delta x \delta y \delta z}=-\frac{1}{\rho}\frac{\partial P}{\partial x}\]
On peut faire le même calcul sur ($Oy$). Finalement les deux composantes horizontales de la force de pression s'écrivent
\[\v F_P^H = -\frac{1}{\rho} \, \binom{\frac{\partial P}{\partial x}}{\frac{\partial P}{\partial y}}\] %  =-\frac{1}{\rho}\vl{grad}P\]
