---
title: Redes de Difraccion
layout: posts
---

En una red de difraccion se superponene los fenómenos de interferencia y difraccion.

Una red de difracción plana está constituida por un gran número de ranuras iguales (mismo ancho $a$) y equidistantes (una distancia $d$) en un mismo plano. Cada ranura se denomina raya o línea de la red.

Se denomina constante de la red de difracción $C$ al recíproco de la distancia que separa los puntos homólogos de dos ranuras sucesivas. Es decir 

$$C=1/d$$

$C$: la constante de la red
$d$: la separación entre dos ranuras sucesivas.

## Maximos y Minimos

Las posiciones de los máximos son entonces independientes del número de ranuras y del ancho de cada ranura, ya que surgen de la interferencia.

### Maximo

$$Y_{\tiny MAX} = \dfrac{m\lambda D}{d} \, \, \, \, \, m \in \mathbb{Z}$$

### Minimo

$$
Y_{\tiny Min} = \dfrac{m\lambda D}{Nd}  \, \, \, \, \, m \in \mathbb{Z}
$$

m: Puede ser cualquier numero entero (menos el cero) no multiplo de N.

El ancho de los máximos principales es como en el fenómeno de interferencia de $2 \lambda D/Nd$.

Es decir, cuanto mayor sea el número de ranuras, más angostos serán los máximos principales.

![56adcefeb606230996ca1747d097262a.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/07_optica_fisica/images/3fe0f08c3df147fe8d016bd646b5c7f9.png){: .align-center}

## Intensidad

La intensidad, combinando los 2 fenómenos es:

$$I = I_o [\dfrac{  sen^2(\dfrac{\beta}{2})  } 
										{ (\dfrac{\beta}{2})^2 }]
					\, \,[\dfrac{sen^2(\dfrac{N\Delta \varphi}{2})  } 
										{ sen^2(\dfrac{\Delta \varphi}{2})}]
							$$
							
### ¿Qué máximo de interferencia no se ve cuando coincide con un mínimo de difracción?

Para obtenerlo escribimos las condiciones de máximo de interferencia y del mínimo de difracción y dividimos miembro a miembro.

$$
\begin{split}
Y_{max_{int}} &= Y_{min_{dif}}\\
\frac{d \cdot sen\theta}{a \cdot sen\theta} &= \frac{m \lambda}{n \lambda}\\
\frac{d}{a } &= \frac{m }{n}
\end{split}
$$

m: Orden del maximo de interferencia
n: Orden del minimo de difraccion

Por ejemplo, si d/a = 3 quiere decir $\frac{d}{a} =  \frac{m }{n} = \frac{3}{1}$ que el primer mínimo de difracción coincide con el tercer máximo de interferencia. Por lo tanto, no se ve.


# Orden maximo

Dado que el $-1<= sen \theta <= 1$ entonces el max se cumple cuando $sen \theta = 1$, por lo tanto

## Maximo de Interferencia

$$\begin{split}
d sen\theta &= m \lambda \\
d &= m \lambda \\
m &= d/\lambda
\end{split}
$$

## Minimo de Difraccion

$$\begin{split}
a sen\theta &= n \lambda \\
a &= n \lambda \\
n &= a/\lambda
\end{split}
$$

Si el resultado de un numero decimal, siempre aproximar al menor valor posible.

# Referencias Bibliograficas

* [Fisica para estudiantes de Ingenieria - FIUBA - Unidad  11 - Óptica Física](https://campus.fi.uba.ar/pluginfile.php/384418/mod_resource/content/1/Unidad%2011%20-%20Optica%20f%C3%ADsica%20-%20Rev.02.pdf)

* Young-Freedman. Física universitaria Sears Zemansky- Volumen I y II. 12ºedición Pearson Addison Wesley 