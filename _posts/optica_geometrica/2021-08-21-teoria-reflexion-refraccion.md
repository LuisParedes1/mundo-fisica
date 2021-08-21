---
title: Reflección y Refracción
layout: posts
---


Resumen Reflexion y Refraccion

# Indice de refraccion

$$n = \frac{c}{v}$$

Siendo:

* $c$ la velocidad de la luz $c = 3* 10^{8}m/s$
* $v$ la velocidad de la luz en el medio
* $n$ indice de refraccion

![2ff29681370fc6e1bda9d2ce1ba34061.png](/assets/teoria/08_optica_geometrica/images/1d441e8070f74df190034ee4c9aba36b.png){: .align-center}



# Reflexion

![8394fc8af6984c843ed44949898d766c.png](/assets/teoria/08_optica_geometrica/images/5d9a1234e7ff4971b9cd634b212b0452.png){: .align-center}

1. El rayo incidente, el reflejado y la normal están en un plano
2. El ángulo que forma el rayo incidente con la normal es idéntico al que forma el rayo reflejado con la normal.

![7cec044f8fec3957004ae4ea002c3db5.png](/assets/teoria/08_optica_geometrica/images/b1877805eb834c62a48369dc12fe09c7.png){: .align-center}

* $\theta_1$ ángulo de incidencia
* $\theta_2$ ángulo de reflexión



# Refraccion

![66c8f294a15d5da6785594cb069b715d.png](/assets/teoria/08_optica_geometrica/images/cbb48cfa167041ff991538f9db7631ff.png){: .align-center}

1. El rayo incidente, el reflejado y la normal están en un plano
2. El ángulo que forma el rayo incidente con la normal y el ángulo que forma el rayo refractado con la normal cumplen la ley de Snell.

![063c08fd807aea1c2d9ddcc7794d7899.png](/assets/teoria/08_optica_geometrica/images/c285a48bd3c44120af781ffff5916e7d.png){: .align-center}

# Ley de Snell

$$
\begin{equation}
n_1 sen(\theta_1) = n_2 sen(\theta_2)
\label{eq:ecuacion_Snell}
\end{equation}
$$



## Angulo Critico 

A partir de este angulo incidencia, se produce una reflexion total. 


Cuando $\theta_1 = \theta_{critico}$ (en Ec: $\ref{eq:ecuacion_Snell}$) la luz bordea la superficie.



En el angulo critico $\theta_1 = \theta_{critico}$, se cumple que $\theta_2 = 90 ^{\circ}$, por tanto

$$\theta_{critico} = arcsen(\frac{n_2 \cdot sen(\theta_2)}{n_1}) = 
										arcsen(\frac{n_2 }{n_1})$$

![e22b3e90d0a176ead76f2d004832dc7f.png](/assets/teoria/08_optica_geometrica/images/9e0271031b534765a7f0f30be5b09dd6.png){: .align-center}

Nota:

* Para que se produzca la reflexion, necesariamente $n_2 < n_1$
puesto que $-1<sen(\theta)< 1$ entonces $-\frac{\pi}{2} < arcsen(\frac{n_2 }{n_1}) < \frac{\pi}{2}$.
* Si $\theta_1 > \theta_{critico}$ se produce una reflexion total.


# Prismas

Operando con la ley de Snell (Ec: $\ref{eq:ecuacion_Snell}$) para los rayos que atraviesan el prisma

![e7dcce23a7a5b8cc0b23235130e6bd4f.png](/assets/teoria/08_optica_geometrica/images/3c84780e21d34566b25a2fc04f6e39a6.png){: .align-center}


* $\gamma$: Es el angulo del prisma
* $\delta$: Es el angulo de desviacion
* $n$ es el indice de refraccion del prisma

El minimo angulo de dispersion es 

$$
\begin{equation}
sen(\frac{\gamma + \delta_{min}}{2})=nsen(\frac{\gamma}{2})
\end{equation}
$$

> Nota: En el angulo minimo de desviacion, se cumple
> $\theta_1 = \frac{\gamma + \delta_{min}}{2}$, 
>
>  Tambien:
>  $2\theta_1=\gamma + \delta_{min}$
> cuando $\theta_4 = \theta_1$, porque es la condicion de minimo de desviacion.


# Referencias Bibliograficas

* [Fisica para estudiantes de Ingenieria - FIUBA - Unidad  10 - Óptica Geométrica](https://campus.fi.uba.ar/pluginfile.php/375387/mod_resource/content/1/Unidad%2010%20-%20Optica%20Geometrica%20Rev.01.pdf)
