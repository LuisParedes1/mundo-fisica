---
title: Dinematica de Cuerpo Rigido
layout: posts
---

Resumen de Dinamica de Cuerpo Rigido

# Cuplas

Para que el efecto producido por la fuerza $\vec{F}$ no cambie, se agrega al sistema un par idénticamente nulo de igual intensidad o norma y de una dirección paralela a $\vec{F}$ que pasa por el CM.

![271f4e286945fbd19e579cb05983766b.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/e47f8905f2f24b0fa51ed8ad590fb845.png){: .align-center}

 $\vec{F}'$ es la fuerza  $\vec{F}$ trasladada al CM y ==$\vec{F}$ junto con  $-\vec{F}'$ forman lo que se denomina cupla o par de fuerzas.==
 
Trasladar, entonces, una fuerza al CM da por resultado la fuerza aplicada en otro punto (en este caso el CM) más una cupla.

# Segundo Principio de Newton para CR

$$
\begin{equation}
	\sum \vec{F}_{ext} = M \vec{a}_{cm}
\end{equation}
$$

# Ecuacion Fundamental de Rotacion

$$\sum \vec{T}^o_{ext} = \sum \vec{r}_{i/o} \times \vec{F}_{i} = I^o \vec{\gamma}$$

$$
\begin{equation}
	\sum \vec{T}^{\ cm}_{ext}  = I^{cm} \vec{\gamma}
\end{equation}
$$

# Momento de Inercia

El momento de inercia, puede pensarse como una inercia de rotación, como la resistencia que un cuerpo presenta a modificar su estado rotacional; es decir, a adquirir una aceleración angular.

Definimos entonces el momento de inercia con respecto al centro de masa de un cuerpo rígido de la siguiente forma:

$$I_{cm} = \int r^2 dm$$

El momento de inercia dependerá del eje respecto del cual efectuaremos el cálculo, ya que $r$ es la distancia de la particula bajo estudio, con respecto del eje de simetria.

![37de676ab5beaac856790b0717f07cce.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/26190806c9b64108835bb023d0539904.png){: .align-center}

# Teorema de Steiner

El Teorema de Steiner o de los ejes paralelos permite encontrar el momento de inercia respecto a un eje que no pasa por el CM con el momento de inercia de un eje que pasa por el CM, con la condición que los ejes sean paralelos entre sí.

$$I_e = I_{cm} + Md^2$$

* $M$ es la masa total del cuerpo.
* $d$ es la distancia entre ejes paralelos.

![0462cd8735823bd02d093769aea1cb28.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/c0940085c3044b0da7fe4e8623b1d8c5.png){: .align-center}

# Momento Cinetico

## Momento cinetico respecto a un eje $o$

A partir de $\vec{L}^o_{sist} = \vec{L}^o_{cm} + \vec{L}^{cm}_{sist}$


$$\vec{L}^e = \vec{r}_{cm/o} \times M\vec{v}_{cm/o} + I_{cm}\vec{\Omega}$$

* $$\vec{L}_{orbital} =\ \vec{r}_{cm/o} \times M\vec{v}_{cm/o}$$
* $$\vec{L}_{spin} = I_{cm}\vec{\Omega}$$

## Momento cinetico respecto al eje que pasa por el CM

$$\vec{L}^{cm} = {\vec{r}_{cm/cm}} \times M\vec{v}_{cm/cm} + I_{cm}\vec{\Omega}$$

$$\vec{L}^{cm} =I_{cm}\vec{\Omega}$$


## Momento cinetico respecto al eje que pasa por el CIR

$$\vec{L}^{cir} = I_{cir}\vec{\Omega}$$


# Energia Potencial

$$Ep_g = mgh_{cm}$$

# Energia Cinetica

A partir de $\vec{Ec}^o_{sist} = \vec{Ec}^o_{cm} + \vec{Ec}^{cm}_{sist}$


$$\vec{Ec} = \frac{1}{2}M\vec{v}_{cm/o}^2 + \frac{1}{2} I_{cm}\vec{\Omega}^2$$

* $$\vec{Ec}_{translacion} =\frac{1}{2}M\vec{v}_{cm/o}^2$$ Enercia Cinetica de Translacion.
* $$\vec{Ec}_{spin} = \frac{1}{2} I_{cm}\vec{\Omega}^2$$  Enercia Cinetica de Rotacion respecto del CR.

# Trabajo
$$
\begin{equation}
	W_{FNC}=\Delta Em
\end{equation}
$$

* La energía cinética para un CR tiene entonces dos términos, uno referido a laraslación y otro referido a la rotación.
* El trabajo de fuerzas interiores para un CR es 0 por la condición de rigidez.


# Apendice

## Rodando Deslizando

* Si existe deslizamiento del punto de contacto (no rota sin deslizar) la fuerza de rozamiento es dinamica, $\vec{f}_{roz}=\mu_d\vec{N}$.
* La velocidad de punto de contacto es distinto de 0. 
* El sentido de la fuerza de rozamiento "se opone al deslizamiento relativo de las superficies en contacto".
* El trabajo trabajo por deslizamiento está asociado a la distancia resbalada por la superficie del cuerpo. Es decir, se necesita conocer cuánto resbala el punto de apoyo CR respecto de la superficie de apoyo y no cuánto avanza el CM.


## Rodar sin deslizar

* La velocidad del punto de contacto es igual a 0.
* La fuerza de rozamiento que se pone de manifiesto es la estática. En principio no se conoce su sentido.
* Como no hay deslizamiento de una superficie con otra, el desplazamiento del punto de contacto es 0. 
Por esta razón <mark> el trabajo de la fuerza de rozamiento cuando el cuerpo “rueda sin deslizar” es nulo. </mark>
* Esto significa que si la única fuerza no conservativa que puede producir trabajo en el sistema es la fuerza de rozamiento, para este caso, se conserva la energía mecánica del sistema.