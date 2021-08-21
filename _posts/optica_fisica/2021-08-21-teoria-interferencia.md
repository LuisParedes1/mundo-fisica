---
title: Interferencia
layout: posts
---

Resumen Interferencia

# Supuestos

* Se trabaja en un medio monocromatico, es decir la frecuencia es constante en el tiempo.
* La diferencia de fase se mantiene constante en el tiempo. ($\Delta \varphi = Const$)

> Cuando dos o mas ondas monocromaticas se propagan manteniendo una diferencia de fase constante durante el tiempo de observacion, se dice que las oscilaciones son <mark>coherentes</mark>

## Interferencia

Superposicion de dos o mas ondas de igual frecuencia y longitud de onda que se propagan en el mismo sentido y que son coherentes, osea que la diferencia de fase es constante en el tiempo durante el cual se desarrolla la experiencia.


### Consecuencias de que la diferencia de fase sea constante ($\Delta \varphi =Const$)


Supongamos tener dos fuentes monocromáticas $S_1$ y $S_2$, separadas una distancias $r_1$ y $r_2$ respectivamente de un punto P de observación. 

![a7b86e842b643110460005117f3653fc.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/07_optica_fisica/images/e5b3d8ce45fa4136a5cd710228e3c6e6.png){: .align-center}

¿Cuál es la diferencia de fase que podemos detectar en P?

Para ello escribimos dos ondas correspondientes a cada una de las fuentes.

$$\varepsilon_1 = A_1 sen(\omega t - k r_1 + \phi_1)$$


$$\varepsilon_2 = A_2 sen(\omega t - k r_2 + \phi_2)$$

$$
\begin{equation*}
    \begin{split}
        \Delta \varphi &= {\omega t} - k r_2 + \phi_2 - ( {\omega t} - k r_1 + \phi_1) \\
         &= k (r_1-r_2) + (\phi_2 - \phi_1)
    \end{split}
\end{equation*}
$$

<div style="page-break-after: always"></div>


Entonces  

$$
\begin{equation}

	\Delta \varphi =  k (r_1-r_2) + (\phi_2 - \phi_1)

\end{equation}
$$

* $\Delta r = (r_1-r_2)$ diferencia de caminos
* $\Delta \phi = (\phi_2 - \phi_1)$ diferencia de fase inicial


Observamos que la diferencia de fase puede deberse a la diferencia de caminos y/o a la diferencia de fase inicial. No depende del tiempo.

Como resultado observaremos en P luz u oscuridad, constantemente en el tiempo.


# Experimento de Young

![5f9990959fe246f5d888b7635d5bc890.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/07_optica_fisica/images/4ba385a4243146bda3c9940bc0a5e26f.png){: .align-center}

## Consecuencias

* Las fases iniciales son las mismas para todas las ondas secuendarias y esta constancia se mantiene durante todo el tiempo. $\Delta \phi = 0$ .
* Las otras caracteristicas de las ondas secundarias (amplitud, longitud de onda, frecuencia, plano de vibracion) son invariantes en el tiempo.

![80b47386c1e32045523e577ac09c2c5b.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/07_optica_fisica/images/cdeec7c75df74300808825e6c633885e.png){: .align-center}

$$
\begin{equation}
	\Delta r = d \, sen\theta
\end{equation}
$$

$$
\begin{equation}
		\Delta \varphi =  k \Delta r
\end{equation}
$$

$$
\begin{equation}
	sen\theta \approx tang \, \theta = \frac{Y}{D}  
\end{equation}
$$


### Interferencia Constructiva

$$\Delta r = d \, sen\theta = m\lambda , \, \, \,\, m \in \mathbb{Z}$$

$$\Delta \varphi = k \Delta r = m \dfrac{2\pi}{\lambda}\lambda = m \, 2\pi ,  \, \, \, 
\, \, m \in \mathbb{Z}$$


### Interferencia Destructiva

$$\Delta r = d \, sen\theta = (2m+1)\dfrac{\lambda}{2}, \, m \in \mathbb{Z}$$

$$\Delta \varphi = k \Delta r = (2m+1) \dfrac{2\pi}{\lambda}\dfrac{\lambda}{2} = (2m+1) \pi$$

### Maximos y Minimos en funcion de la posicion 

Usando $sen\theta \approx tang \, \theta = \frac{Y}{D}$


$$
\begin{equation}
Y_{\tiny MAX} = \dfrac{m\lambda D}{d} \, \, \, \, \, m \in \mathbb{Z}
\end{equation}
$$

Los maximos no cambian en el tiempo, ni dependen del numero de ranuras.

$$
\begin{equation}
Y_{\tiny Min} = \dfrac{m\lambda D}{Nd} \, \, \, \, \, m \in \mathbb{Z}
\end{equation}
$$


N: Numero de ranuras
m: Puede ser cualquier numero entero (incluyendo al cero) <mark>no multiplo de N</mark>


### Importante

Como $m \in \mathbb{Z}$, entonces cuando se habla del maximo principal (orden cero), se refiere a $m=0$, y cuando se habla del primer maximo se refiere a $m = \pm 1$

Cuando se habla del primer minimo se refiere a $m = 0$, por la naturaleza de $2m+1$, entonces se cuenta, cuando hay dos ranuras

1. Max Princial (orden cero)
2. Primer Minimo (orden uno)
3. Primer Maximo (orden uno)
4. Segundo Minimo (orden dos)
5. Segundo Maximo (orden dos)
6. Etc

# Intensidad

$$
\begin{equation}

I = I_o\dfrac{  sen^2(\dfrac{N\Delta \varphi}{2})  } 
										{ sen^2(\dfrac{\Delta \varphi}{2}) }
\end{equation}
$$

## Intensidad Minima

$I_{Min} = 0$ y se cumple cuando $sen^2(\dfrac{N\Delta \varphi}{2})=0$ pero $sen^2(\dfrac{\Delta \varphi}{2}) \neq 0$

##   Intesidad Maxima

$I_{MAX} = N^2 I_o$



![51625fbcf631ac816f991ce8b21f21d7.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/07_optica_fisica/images/cc9c05b6edb0403e876589b94c1c5404.png){: .align-center}

### Propiedades

Para interferencia de N ranuras

* Entre 2 maximos principales hay N-2 maximos secundarios y N-1 minimos
* El valor de $I = c(N A_o)^2$ aumenta a medida que aumenta el numero de fuentes.
* La separacion entre maximos no depende del numero de ranuras, si de la separacion entre ranuras
* El ancho del maximo central se estrecha a medida que aumenta el numero de fuentes. En el caso que sean ranuras resultan largas y angostas. 
* El maximo principal, orden cero, ($Y_{MAX}=0$) es el único máximo que no depende de la longitud de onda.

# Interfranja

Distancia entre maximos consecutivos

$$\Delta Y = \dfrac{\lambda D}{d} $$

# Referencias Bibliograficas

* [Fisica para estudiantes de Ingenieria - FIUBA - Unidad  11 - Óptica Física](https://campus.fi.uba.ar/pluginfile.php/384418/mod_resource/content/1/Unidad%2011%20-%20Optica%20f%C3%ADsica%20-%20Rev.02.pdf)

* Young-Freedman. Física universitaria Sears Zemansky- Volumen I y II. 12ºedición Pearson Addison Wesley 