---
title: Superposicion de Ondas
layout: posts
---

La onda resultante es una combinacion lineal de cada una de las ondas individuales

$$Y(x,t) = \sum Y_i(x,t)$$

# Casos

Sean las ondas armonicas provenientes de fuentes independientes del mismo tipo ($c_2 = c_1 = c$).

$$Y_1(x,t) = A_1 cos(kx-w_1t+\phi_1)$$

$$Y_2(x,t) = A_2 cos(kx-w_2t+\phi_2)$$



## Frecuencias iguales y amplitudes distintas

* $f_1 = f_2 = f$
 
$$
\begin{equation}
    Y(x,t) = A  \cdot [ cos(\phi) cos(kx-wt) - \\ sen(\phi)sen(kx-wt) ]
\end{equation}
$$

$$
\begin{equation}
\phi = \frac{A_1 \cdot sen\phi_1 + A_2 \cdot sen\phi_2}
					{A_1 \cdot cos\phi_1 + A_2 \cdot cos\phi_2} 
\end{equation}
$$


$$
\begin{equation}
    A^2 = A_1^2 + A_2^2 + 2A_1A_2 \cdot cos(\phi_1 - \phi_2) 
\end{equation}
$$


## Frecuencias Iguales y Amplitudes Iguales


* $f_1 = f_2 = f$
* $A_1 = A_2 = A$


$$
\begin{equation}
Y(x,t) = 2 A  \cdot | cos(\frac{\phi_1-\phi_2}{2}) | \cdot \\ 
    cos[kx-wt + (\frac{\phi_1-\phi_2}{2}) ]
\end{equation}
$$

 
 Fuentes coherentes son las fuentes que cumplen:
 
 * Tienen la misma frecuencia
 * La diferencia de fase inicial no cambia

Con fuentes coherentes hay zonas donde la perturbación total es nula para todo tiempo

Con fuentes coherentes ocurre el fenómeno de interferencia.

### Interferencia destructiva


$\mid cos(\frac{\phi_1-\phi_2}{2}) \mid $ = 0, tal que 

$$Y(x,t) =0$$


### Interferencia constructiva


$\mid cos(\frac{\phi_1-\phi_2}{2}) \mid $ = 1, tal que 

$$Y(x,t) =2 A  \cdot cos[ kx-wt + (\frac{\phi_1-\phi_2}{2}) ]$$



## Frecuencias muy parecidas y amplitudes iguales (Batido)

Supuestos

* $f_1 \sim f_2$
* $A_1 = A_2 = A$
* Diferencia de fases nula ($\Delta \phi = 0$)


La frecuencia del batido es $f_b = \mid f_2 - f_1 \mid$ y se percibe dos veces en un ciclo.

Y la frecuencia percibida es: $$f' = \frac{f_1+f_2}{2}$$

> Para ondas sonoras: si el cambio en la intensidad tiene una frecuencia de menos de 16Hz se denomina batido.

### Ecuacion de Batido

$$
		Y(x,t) = 2 A \cdot cos[\frac{(k_1-k_2)}{2}x + \frac{(w_1-w_2)}{2} t ]  \cdot \\
					cos [ \frac{(k_1+k_2)}{2}x - \frac{(w_1+w_2)}{2} t]
$$

Donde:

$A_{resultante} = 2 A  \cdot cos[\frac{(k_1-k_2)}{2}x + \frac{(w_1-w_2)}{2} t ]$

La amplitud tiene una variacion temporal y espacial lenta



# Ondas Estacionarias


$$
\begin{equation}
Y_n(x,t) = [2Asen(k_nx)]\cdot cos(w_nt)
\end{equation}
$$

* $A =  [2Asen(k_nx)]$


* La ecuacion corresponde a un movimiento oscilatorio, no a una propagacion de onda.

* La amplitud unicamente depende de la posicion.  Es decir que habran ciertas posiciones con amplitud constante (nodos).


## "N" modos propios

Una onda estacionaria tiene "n" modos propios o naturales de oscilacion. A cada uno de ellos les correspondera una frecuencia $f_n$ tal que $c = \lambda_n \cdot f_n$


### Caso Extremos Fijos


![f0978a0f1d5a646ab5ea2f72fd495f0c.png](/assets/teoria/06_ondas/images/1c4c7e332422478aa2b8f2d561573547.png){: .align-center}

Se debe cumplir que 

$Y(L,t) = 0$, es decir $sen(k \cdot L) = 0$, si 

$$k_n \cdot L= n \pi  ,\, \, \, n\in N ,\, \, \, n>0$$

Entonces tenemos, usando $k=\frac{2\pi}{\lambda}$ y tambien  $c = \lambda_n \cdot f_n$

$$
	f_n = \frac{c}{\lambda_n} = \frac{c \cdot k_n}{2\pi} = \frac{c \cdot n {\pi}}{2 {\pi} L}= n\frac{c }{2L}
$$

<mark>
$$
\begin{equation}
	f_n = n\frac{c }{2L} = n f_1 ,\, \, \, n > 0
\end{equation}
$$
</mark>

<mark>
$$
\begin{equation}
	\lambda_n = \frac{2L}{n} ,\, \, \, n > 0
\end{equation}
$$
</mark>

$f_1$: Frecuencia Fundamental ($n=1$)
$f_2$: Frecuencia Primer Armonico ($n=2$)


Los nodos se encuentan en: $sen(kx) =0 \longrightarrow kx_n = n\pi ,\, \, \, n\in N ,\, \, \, n>0$


$$
\begin{split}
	kx_n &= n\pi \\
	x_n	&= \frac{n \pi}{k} \\ 
	x_n	  &= \frac{n {\pi} * \lambda}{2 {\pi}} \\
	x_n	  &=  n \frac{\lambda}{2}
\end{split}
$$

> La distancia entre nodos es de $\lambda/2$


Los antinodos se encuentran en: $sen(kx) =1 \longrightarrow kx_n = (2n+1)\frac{\pi}{2}, \, \, \, n\in N ,\, \, \, n \ge 0$

$$
\begin{split}
	kx_n &= (2n+1)\frac{\pi}{2} \\
	x_n	&= \frac{(2n+1)\frac{\pi}{2}}{k} \\ 
	x_n	  &= \frac{(2n+1)\frac{\pi}{2} \cdot \lambda}{2 {\pi}} \\
	x_n	  &=   \frac{(2n+1) \cdot \lambda}{4}
\end{split}
$$

Los antinodos tambien se pueden hallar como

$$ \frac{\delta Y(x,t)}{\delta x} = 0 $$

> La distancia entre antinodos tambien es de $\lambda / 2$. 
> 
> Entonces, la distancia entre nodos y antinodos es de $\lambda / 4$


Notas: 

* En el caso de un tubo abierto en los dos extremos, también están presentes todos los múltiplos de la frecuencia fundamental como el caso de la soga atada por los dos extremos, pero manteniendo el 0 en un extremo.




### Caso Extremo Fijo / Libre
![38f32a3b24e9a630e4d022d04263f5a2.png](/assets/teoria/06_ondas/images/3e09058bd29d4f02ad959bafd5e7f5ef.png){: .align-center}

* En $x=0$, el extremo esta fijo $Y(0,t)=0$
* En $x=L$, el extremo esta suelto, tal que se puede obtener un maximo.



Entonces, en $x=L$: 



$\mid sen(kL) \mid =1 \longrightarrow kL = (2n+1)\frac{\pi}{2},\, \, \, n\in N_0 ,\, \, \, n \ge 0$

$$
\begin{split}
	k_nL &= (2n+1)\frac{\pi}{2}, \\
	\frac{2{\pi}}{\lambda_n}	&= \frac{(2n+1){\pi}}{2L} \\ 
	\lambda_n	  &= \frac{4L}{2n+1} 
\end{split}
$$


<mark>
$$
\begin{equation}
	\lambda_n	 = \frac{4L}{2n+1} , \, \, \, n\in N_0
\end{equation}
$$
</mark>

<mark>
$$
\begin{equation}
	f_n	 = \frac{(2n+1)\cdot c}{4L} , \, \, \, n\in N_0
\end{equation}
$$
</mark>

> El espectro de frecuencias corresponde a múltiplos impares de f



# Energia en las ondas estacionaria

Para una cuerda de longitud $L$, fija en los dos extremos.

$$E =  A^2 * \omega^2 * \mu *L$$

# Resonancia

Se produce la resonancia cuando un agente externo produce una onda externa sobre el medio (cuerda, puente, etc) con una frecuencia muy proxima o igual a alguna de sus fundamentales

$$f_{externa} \sim n \cdot f'$$

Siendo:

* $f'$: la frecuencia fundamental del medio por el que se propaga.
* $f_{externa}$: Es la frecuencia con la que el generador externo perturba

Cuando se produce la resonancia la amplitud del medio se estira constantemente hasta romperse.


> Al haber resonancia, la frecuencia del generador es proxima a alguna frecuencia fundamental del medio y por tanto su amplitud se estira hacia el infinito (o hasta romperse).

## Ecuacion de Resonancia

$$ Y(x,t) = \frac{A_{MAX}sen(2\pi x / \lambda) }{sen(\pi f /f_1)} cos (\omega t) $$

Siendo 
* $f$ la frecuencia externa
* $f_1$ la frecuencia fundamental
* $A_{MAX}$ La aplitud maxima

Notar que si $f = n f_1$, es decir si es igual a cualquier frecuencia fundamental, entonces:

$$sen(\pi f /f_1) = sen(\pi \, n \cdot f_1 /f_1) = sen( n\pi ) = 0$$

Entonces, en la ecuacion de resonancia

$$ \lim_{f \to f_1}Y(x,t) = \lim_{f \to f_1} \frac{A_{MAX}sen(2\pi x / \lambda) }{0} cos (\omega t) = \infty $$


> Conclusion:
> 
>  Mientras mas se aproxime la frecuencia externa a la frecuencia fundamental del medio, su amplitud tiende a crecer indefinidamente. 
>  
>  Claramente cuerpos no son elasticos indefinidamente, por lo tanto se rompen en un cierto punto, como consecuencia de la resonancia.


[Ejemplo de Resonancia](https://www.youtube.com/watch?v=SzObC64E2Ag&ab_channel=Rub%C3%A9nM.Cenzano)

# Referencias Bibliograficas

* [Fisica para estudiantes de Ingenieria - FIUBA - Unidad  9 - Ondas Mecánicas](https://campus.fi.uba.ar/pluginfile.php/384421/mod_resource/content/1/Unidad%209%20-%20Ondas%20mec%C3%A1nicas%20-%20Rev.01.pdf)

* Alonso y Finn. Física. Volumen I (Mecánica) y II (Campos y ondas). Addison Wesley Longman.