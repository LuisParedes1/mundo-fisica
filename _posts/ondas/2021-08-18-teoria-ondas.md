---
title: Ondas
layout: posts
---

Resumen de Ondas

# Ecuacion de Ondas

Toda onda cumple con la ecuacion diferencial

$$
\frac{d\xi^2}{dt^2} = c^2 \cdot \frac{d\xi^2}{dx^2}

$$

Siendo

- c la velocidad de propagacion de onda en el medio.

# Ondas Mecanicas

Las ondas mecanicas son aquellas que se desplazan a travez de un medio. Se describen senosoidalmente como:

$$
\begin{equation}
	Y(x,t)= Acos(kx-\omega t + \phi_o )
\end{equation}

$$

$$
\begin{equation}
	Y(x,t)= Acos(k[x-\omega t] + \phi_o )
\end{equation}
$$

$$
\begin{equation}
	Y(x,t)= Acos(\frac{2\pi}{\lambda}[kx-c \, t] + \phi_o )
\end{equation}
$$

Donde

* $k$: Numero de onda
* $\lambda$: Longitud de onda (Periodo Espacial)
* $A$: Amplitud de onda
* $\omega$: Pulsacion o frecuencia angular
* $f$: Frecuencia
* $T$: Periodo temporal
* $c$: Velocidad de propagacion de onda
* $\phi_o$: Fase inicial

> Cualquiera de las ecuaciones son equivalentes.

## Conceptos

### Longitud de onda $\lambda$

La longitud de onda $\lambda$ es la distancia entre dos perturbaciones iguales, es decir cada longitud $\lambda$ se repite el valor que toma la perturbacion (en un instante dado).

$$
\begin{split}
	Y(x+\frac{2\pi}{k},t) &= Acos(k (x+\frac{2\pi}{k}) -\omega t + \phi_o ) \\
								&= Acos(kx - \omega t + \phi_o + {k}\frac{2\pi}{k}) ) \\
								&= Acos(kx - \omega t + \phi_o + 2\pi ) \\
								&= Acos(kx - \omega t + \phi_o ) \\
								&= Y(x,t)			
\end{split}
$$



Siendo $\lambda = \frac{2\pi}{k}$ entonces  $Y(x+\lambda,t) =  Y(x,t)$.

La longitud de onda representa la distancia que la onda avanza en un periodo ($\lambda = c \cdot T$).



### Frecuencia $f$

La frecuencia solo depende de la fuente emisora de onda.


### Velocidad de propagacion de onda $c$

La velocidad de propagacion de onda solo dependen del tipo de onda y del medio en que se propaga.



## Fase de Onda

Se define como el conjunto de puntos del espacio que vibran en "fase", es decir con la misma elongacion, velocidad y aceleracion.

La fase es el argumento de la funcion sinusoidal


$Y(x,t)= A cos(\Phi)$

$$
	\Phi(x,t) = kx-\omega t + \phi_o
$$

La distancia entre dos frentes de onda consecutivos es igual a la longitud de onda $\lambda$.
> 
> En efecto, si $\Delta \Phi = 2\pi$, entonces 
> 
> $$\Delta \Phi =\Phi(x_2,t) - \Phi(x_1,t)= (kx_2-\omega t + \phi_o) - (kx_1-\omega t + \phi_o)$$
> 
>   La frecuencia es la misma durante el tiempo ($\omega = 2\pi f$) y ambos tienen la misma fase inicial (por ser la misma onda). Por tanto
>
>  $$  \begin{split} 
  		k (x_2-x_1) &= 2 \pi \\
		\frac{2 \pi}{\lambda}(x_2-x_1) &= {2 \pi} \\
		(x_2-x_1) &= \lambda
 		\end{split}
> 	$$


## Desplazamiento de una particula del medio

Para una onda armonica, la perturbación que estemos considerando para <mark>un punto fijo del espacio</mark> varía en la forma de un movimiento armónico simple.

$$
\begin{equation*}
\begin{split}
    Y(x_o,t) &= Acos(kx_o-\omega t + \phi_o ) \\
            &= Acos( [kx_o + \phi_o] - \omega t ) \\
            &= Acos( \beta - \omega t ) \\
\end{split}
\end{equation*}
$$



Con $\beta = [kx_o + \phi_o]$ constante en el tiempo.



## Velocidad de oscilacion de una particula del medio

La misma se puede derivar para obtener la velocidad con que oscila <mark>una particula del medio</mark> en que se desplaza.

$$
		V(x,t)=  \frac{\delta \,Y(x,t)}{\delta t} = A \omega  \, sen(kx-\omega t + \phi_o )
$$

Como $sen(kx-\omega t + \phi_o )$ oscila entre $-1$ y $1$, entonces:

$$
		|V_{\tiny MAX}(x,t)|= A \omega  
$$

> La diferencia entre velocidad de propagacion $c$ y velocidad de oscilacion de una particula del medio, es que la primera es propia de la onda y la segunda propia de la particula del medio.


## Aceleracion de oscilacion de una particula del medio

$$
		a(x,t) = \frac{\delta \,V(x,t)}{\delta t}= -A \omega^2  \, cos(kx-\omega t + \phi_o )
$$



# Relaciones Importantes

$$
\begin{equation}
	c = \lambda \cdot f
\end{equation}

$$

$$
\begin{equation}
	\omega = 2 \pi f
\end{equation}

$$

$$
\begin{equation}
	T = \frac{1}{f}
\end{equation}
$$

$$
\begin{equation}
	k = \frac{2\pi}{\lambda}
\end{equation}
$$


# Velocidad de onda en distintos medios

|  Medio   |  Velocidad   | Datos |
| :---: | :---: | :---: |
| Cuerda Tensa | $c=\sqrt{\frac{T}{\mu}}$ |$T$: Tension <br> $\mu$ densiadad lineal <br> $\mu = \dfrac{dm}{dx}$ (masa por unidad de longitud)|
| Varilla Longitudinal| $c=\sqrt{\frac{Y}{\rho}}$ |$Y$: Modulo Young <br> $\rho$ densidad |
| Varilla Transversal| $c=\sqrt{\frac{G}{\rho}}$ |$G$: Modulo Rigidez <br> $\rho$ densidad |
| Fluidos Longitudinal | $c=\sqrt{\frac{B}{\rho}}$ |$B$: Modulo Volumetrico<br> $\rho$ densidad |



## Energia Media

$$<E> = \frac{1}{2} A^2 \omega^2 \rho \, dV = \frac{1}{2} A^2 \omega^2 \rho \,(dx \cdot dS)$$

## Potencia Media

$$
\begin{equation*}
\begin{split}
    <P> &= \frac{<E>}{dt} = \frac{1}{2} A^2 \omega^2 \rho \, (\frac{dx}{dt}\cdot dS) \\
        &= \frac{1}{2} A^2 \omega^2 \rho  \,c \cdot (dS)
\end{split}
\end{equation*} 
$$

## Intensidad

$$I = \frac{<P>}{dS} = \frac{<E>}{dt \, dS} = \frac{1}{2} A^2 \omega^2 \rho  \,c$$


* A: Amplitud
* $\omega$: pulsacion ($\omega = 2\pi f$)
* $\rho$: Densidad
* c: Velocidad de Propagacion 
* $dV$: Unidad de volumen
* $dS$: Unidad de Area (Superficie)
* $dt$: Unidad de tiempo

# Energia Media sobre Volumen

$$ 
\begin{equation}
	<E>/Vol = \frac{1}{2} A^2 \omega^2 \rho [J/m^3]
\end{equation}
$$

* A: Amplitud
* $\omega$: pulsacion ($\omega = 2\pi f$)
* $\rho$: Densidad


# Intensidad


$$
	I = \frac{Potencia \ que \ transporta \ la \ onda}{Superficie \ donde \ se \ distribuye \ la \ energía}
$$

$$
	I = \frac{<P>}{S}
$$


## Energía media por unidad de área y de tiempo = Potencia media sobre unidad de área = Intensidad
$$ 
\begin{equation}
	I = \frac{1}{2} A^2 \, \omega^2 \, \rho \, c  \ [W/m^2]
\end{equation}
$$

* A: Amplitud
* $\omega$: pulsacion ($\omega = 2\pi f$)
* $\rho$: Densidad
* $c$: Velocidad de propagacion



![f4f65c8bf4d058cb964ffa470c16d6c2.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/06_ondas/images/f277f113cefc41bca287b8427cea0799.png){: .align-center}

* La intensidad de la onda es inversamente proporcional al cuadrado de la distancia al generador.

$$\frac{I_1}{I_2} = \frac{R_2^2}{R_1^2}$$

$I \sim A^2$

* La amplitud de la perturbación es inversamente proporcional a la distancia al generado

$$\frac{A_1}{A_2} = \frac{R_2}{R_1}$$



# Sonido

Las ondas sonoras son ondas de compresión longitudinales en un medio material.


![7f3a4865d3115ecff2dddba8ed18cf2d.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/06_ondas/images/7caebc554c644a62bd43452cc58f252f.png){: .align-center}

> Los puntos muestran la posición de moléculas de aire. Cada punto tiene distinta presion

## Velocidad de Propagacion

$$
\begin{equation}
	c = \sqrt{\gamma \frac{P_o}{\rho_o}} = V = \sqrt{ \frac{B}{\rho_o}}
\end{equation}
$$

* $B = \gamma P_o$
* $\gamma$: coeficiente adiabático
* $P_o$: presión sin perturbar
* $\rho_o$: densidad sin perturbar

## Onda de desplazamiento (Longitudinal)

$$
	Y(x,t)= Acos(kx-\omega t + \phi_o )
$$

## Onda de Presion

$$
	P(x,t)-P_o= A_pcos(kx-\omega t + \phi_o )
$$

## Intensidad

$$ 
\begin{split}
	I &= \frac{1}{2} A^2 \, \omega^2 \, \rho_o \, c \\
	I &=  \frac{1}{2} A^2 \, \omega^2 \, \rho_o \, \sqrt{\gamma \frac{P_o}{\rho_o}}

\end{split}
$$


# Intesidad de decibeles

$$\beta = 10 \log{\frac{I}{I_o}}$$

* $I$ Intensidad relativo
* $I_o = 10^{-12}\frac{W}{m^2}$: Intensidad minima audible por el odio humano

# Referencias Bibliograficas

* [Fisica para estudiantes de Ingenieria - FIUBA - Unidad  9 - Ondas Mecánicas](https://campus.fi.uba.ar/pluginfile.php/384421/mod_resource/content/1/Unidad%209%20-%20Ondas%20mec%C3%A1nicas%20-%20Rev.01.pdf)

* Alonso y Finn. Física. Volumen I (Mecánica) y II (Campos y ondas). Addison Wesley Longman.