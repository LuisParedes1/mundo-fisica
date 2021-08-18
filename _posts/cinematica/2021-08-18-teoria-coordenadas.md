---
title: Coordenadas
layout: posts
---

# Ecuaciones Horarias

$$
\begin{equation}
    x(t)= x_o + V_o\cdot t + \frac{1}{2} \cdot a \cdot t^2
\end{equation}
$$

$$
\begin{equation}
    v(t)= V_o + a \cdot t 
\end{equation}
$$

## Recordar

$$
    \vec{a} = \frac{d\vec{v}}{dt}
$$

$$
    \vec{v} = \frac{d\vec{r}}{dt}
$$

### IMPORTANTE

> * Para poder obtener la posición $\vec{r}_{(t)}$ en un determinado instante $t$, a partir de $$\vec{v}_{(t)}$$ debo tener la una posicion inicial ($\vec{r}_o$) de referencia, de lo contrario no se puede.
- Para poder obtener la velocidad $\vec{v}_{(t)}$ en un determinado instante $t$ a partir de $$\vec{a}_{(t)}$$ debo tener la una velocidad inicial ($\vec{v}_o$) de referencia, de lo contrario no se puede.

## Otras formulas

$$
V_f^2 = V_o^2 + 2 \cdot a \cdot x
$$


# Ecuaciones Angulares

## Posicion Angular

$\theta (t)$ es el ángulo con respecto del tiempo

## Velocidad Angular

$$w = \frac{d \theta (t)}{dt}$$

## Aceleracion Angular

$$\gamma = \frac{d^2 \theta (t)}{dt^2}$$

### Calcular la posicion angular a partir de velocidad angular en funcion del tiempo

Dada la posicion angular inicial, se puede integrar la velocidad angular para obtener $\theta (t)$

$$
\int_{\tiny \theta_o}^{\tiny \theta{(t)}} d\theta (t) =\int w \, dt
$$

$$\theta (t) - \theta_o = w \cdot t$$


# Relaciones importantes

## Velocidad

$$\vec{v}= \vec{\omega} \times \vec{r}$$

$$|\vec{v}| = |\vec{\omega}| \times |\vec{r}| \longleftrightarrow v = \omega \cdot r$$

* $v$ es la velocidad tangencial.
* $w$ es la velocidad angular.
* $r$ es el radio de curvatura o posicion de la particula.

## Aceleracion

$$
\begin{equation*}
    \vec{a}= ({\gamma} \cdot |r|) \, \hat e_r - (\omega^2 \cdot |r|)\hat e_n
\end{equation*}
$$

$$
\begin{equation*}
    \vec{a_t} = {\gamma} \cdot |r| \, \hat e_r
\end{equation*}
$$

$$
\begin{equation*}
    \vec{a_c} = - \, \omega^2 \cdot |r| \, \hat e_n
\end{equation*} 
$$

* $\vec{a}_t$ aceleracion tangencial
* $\hat e_r$ versor radial 
* $\vec{a}_n$ aceleracion centripeta
* $\hat e_r$ versor transversal 


## Aceleracion en Coordenadas Cartesianas

$$\vec{a} = \vec{\gamma} \times \vec{r} + \vec{\omega} \times \vec{\omega} \times \vec{r}$$

* Al hacer el producto vectorial obtengo el vector aceleracion en coordenadas cartesianas.