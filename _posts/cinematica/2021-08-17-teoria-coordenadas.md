---
title: Coordenadas
layout: posts
---

Resumen de coordenadas

# Coordenadas Cartesianas

El vector posición lo expresamos, como una terna ordenada de números reales o como una expresión en función de los versores que indican la referencia de tres ejes concurrentes al origen.

El vector indica un punto en relación con el origen de coordenadas. $\vec{r}_{\tiny P-O}$

$$\vec{r}_{\tiny P-O} = x_p \hat{i} + y_p \hat{j} + z_p \hat{k}$$

El módulo de este vector es la distancia que existe entre P y O:

$$ | \vec{r}_{\tiny P-O}| = \sqrt{(x_p)^2 + (y_p)^2 + (z_p)^2} $$

$x_{\tiny P} \, , y_{\tiny P} \, , z_{\tiny P}$ : son coordenadas del punto, y que variarán en función del tiempo en la medida que la partícula se mueva.

##

# Coordenadas Polares

$$\vec{r}_{\tiny P-O} = \pm |\vec{r}_{\tiny P-O}|ĕ_r$$

El vector se escribe como módulo del vector en la dirección radial con el signo más si es un vector que apunta del centro hacia afuera como el versor radial $ĕ_r$ o el signo menos si apunta hacia adentro contrario a $ĕ_r$.

Lo interesante es que ***tenemos un versor que acompañará la posición del punto material***, y esta propiedad es muy útil para describir movimientos curvilíneos en general.

El versor radial se puede escribir en cartesianas, es decir podemos dar la transformación de polar a cartesiano de este versor.

$$ĕ_r = cos (\theta) \, \hat{i} +  sen(\theta) \, \hat{j}$$

Tenemos que entender que el versor $ĕ_r$ es variable en $\theta$, que es el ángulo que forma el versor con el eje $“+x”$, cuando deseamos transformar la notación polar en notación cartesiana.

![a251a44018a718791e2c7a02d834a88e.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/01_cinematica/images/d913857302c44037ac00c36ab68ee0dd.png){: .align-center}


El versor $ĕ_θ$ es normal al versor radial, matemáticamente se puede calcular mediante la derivada (usando la regla de la cadena) del versor $ĕ_r$.

![091ceb85f68491c904ecf16e520bbf8f.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/01_cinematica/images/8a2b309d879643cb862c8cafbe46291e.png){: .align-center}

![b2d8c1f1242c0d95e07a1ad47bc78c9c.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/01_cinematica/images/fb97555330094d47aaae18f58d78b806.png){: .align-center}

Recordando que el módulo de la velocidad angular $(w)$ es $\frac{d \theta}{dt}$ y llamando a $ĕ_\theta = -sen (\theta) \, \hat{i} +  cos(\theta) \, \hat{j}$

![8a7771aef6b28a6be4dab58642b3e8bf.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/01_cinematica/images/1918d83c4b9d4310b0dfe898a5fe7399.png){: .align-center}

Esta ecuación nos está indicando que la derivada de un versor es perpendicular a dicho versor y además su módulo es igual a la velocidad angular del movimiento del punto que estamos estudiando.

##

## Versores Polares

$$ĕ_r = cos (\theta) \, \hat{i} +  sen(\theta) \, \hat{j}$$

$$ĕ_\theta = -sen (\theta) \, \hat{i} +  cos(\theta) \, \hat{j}$$

* $ĕ_r \perp ĕ_\theta$
* $\frac{d ĕ_r}{dt} = w \, ĕ_\theta$
* $ĕ_r$ es un versor que acompañará la posición del punto material.

##

# Coordenadas Intrinsecas

**La velocidad es tangente a la trayectoria.** 

Esta propiedad la utilizamos para encontrar el versor tangente y expresar la velocidad de la partícula $“P”$.

![5dc604e10b382b4078dd4f5d295c13f2.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/01_cinematica/images/447ca84be49a48019a1dc396fe5ec74d.png){: .align-center}

$$\vec{v}_{\tiny P-O} = |\vec{v}_{\tiny P-O}|ĕ_t$$

El versor tangente, es el vector velocidad dividido por su módulo.

$$ĕ_t = \frac{\vec{v}_{\tiny P-O}}{|\vec{v}_{\tiny P-O}|}$$

* $|\vec{v}_{\tiny P-O}|$ : es el módulo del vector velocidad.
* $ĕ_t$ : es el versor tangencial a la trayectoria o versor tangente.

La expresión en coordenadas cartesianas de este versor es: 
$$ĕ_t = cos (\varphi) \, \hat{i} +  sen(\varphi) \, \hat{j}$$

##

Otra vez, **como para polares**, en este sistema, se verifica que el ángulo φ, es una variable que se toma desde el eje de abscisas y que depende del tiempo en la medida que se mueve el punto “P”.

![dfe2a7886b0de71d0eaa3bb6ac8dc00a.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/01_cinematica/images/7a285cf0c5c8493e8ce2958da3bd4690.png){: .align-center}

## Versores Intrinsecos

$$ĕ_t = cos (\varphi) \, \hat{i} +  sen(\varphi) \, \hat{j}$$

$$ĕ_n = -sen (\varphi) \, \hat{i} +  cos(\varphi) \, \hat{j}$$

* $ĕ_r \perp ĕ_n$
* $\frac{d ĕ_t}{dt} = w \, ĕ_n$
* $ĕ_t$ es un versor **tangente a la trayectoria**, por tanto tiene la misma dirección que la velocidad en ese instante $\vec{v}_{\tiny P-O}$

##

### Obtener vectores intrinsecos y normal

![d9c6e444290c8caec7bc59eccc0ff49b.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/01_cinematica/images/cc80a1a2518d4a4497ca753b4bcc3b72.png){: .align-center}

![89e5dc1edd280a8fc98c77e3c24c342c.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/01_cinematica/images/941b9e5faee141ed95f403b276fff37a.png){: .align-center}


# Radio de Giro

![ce8c8fd36ddfe94a2a72a4756ad66a20.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/01_cinematica/images/94cc14242528475e86c61c4b471b9caf.png){: .align-center}

$$a_n = \omega^2 \cdot R_g = \frac{v^2}{R_g}$$

Recordar $v=\omega \cdot r$