---
title: Sistema de Particulas
layout: posts
---

Resumen de Sistema de Particulas


# Posicion del centro de masa

Se define como la media ponderada de las posiciones.

Posicion de centro de masa con respecto a un punto O.

$$\vec{r}_{\tiny CM/O} =  \sum \dfrac{m_i\vec{r}_{i/o}}{M} $$

Tomando como sistema de referencia al centro de masa CM.

$$\vec{r}_{i/cm}=\vec{r}_{i/o}-\vec{r}_{cm/o}$$

$$\begin{equation*}
\begin{split}
	\vec{r}_{\tiny CM/O}  
	&= \sum \dfrac{m_i\vec{r}_{i/o}}{M} \\
	&= \sum \dfrac{m_i (\vec{r}_{i/cm}+\vec{r}_{cm/o})}{M} \\
	&= \sum \dfrac{m_i\vec{r}_{i/cm}}{M} + \sum \dfrac{m_i \vec{r}_{cm/o}}{M}\\
	\vec{r}_{\tiny CM/O}  &= \sum \dfrac{m_i\vec{r}_{i/cm}}{M} + \vec{r}_{cm/o}\\\\
	0 &= \sum \dfrac{m_i\vec{r}_{i/cm}}{M}
\end{split}
\end{equation*}
$$

Con respecto del Centro de masa.

$$ \vec{r}_{cm/cm} =  \sum \dfrac{m_i\vec{r}_{i/cm}}{M} = 0 $$


# Velocidad de centro de masa

Se obtiene derivando la posicion del CM.

Con respecto al punto fijo a tierra O.

$$\vec{v}_{\tiny CM/O} =  \sum \dfrac{m_i\vec{v}_{i/o}}{M} $$

Con respecto del sistema fijo en el CM. Actua como sistema de referencia privilegiado.

$$  \vec{v}_{cm/cm} = \sum \dfrac{m_i\vec{v}_{i/cm}}{M} = 0 $$

<div style="page-break-after: always"></div>


# Aceleracion de centro de masa

Con respecto al punto fijo a tierra O.

$$\vec{a}_{\tiny CM/O} =  \sum \dfrac{m_i\vec{a}_{i/o}}{M} $$

Con respecto del sistema fijo en el CM.

$$  \vec{a}_{cm/cm} = \sum \dfrac{m_i\vec{a}_{i/cm}}{M} = 0 $$


# Cantidad de Movimiento $\vec{P}_{sist}$

$$\vec{P}^o_{sist}= \sum \vec{P}_{i/o} = \sum m_i\vec{v}_{i/o} = M \vec{v}_{cm/o}  $$

 
# Cantidad de momento angular $\vec{L}^o_{sist}$

$$\vec{L}^o_{sist} = \sum \vec{L}^o_{i} = \sum \vec{r}_{i/o} \times m_i\vec{v}_{i/o}$$



# Segunda Principio de Newton

Las fuerzas internas del sistema se anulan entre si.

Unicamente las fuerzas externas al sistema pueden cambiar el estado del sistema.

$$\sum \vec{F}_{ext} = M\vec{a}_{cm} $$



# Impulso del sistema de particulas

$$\vec{J}_{ext} =  \Delta \vec{P}_{sist} = \vec{P}_{sist_{final}} - \vec{P}_{sist_{inic}}$$


# Momento angular y torque para sist de particulas

$$\begin{equation*}
\begin{split}
	\sum \tau^o_{ext} 
	&= \dfrac{d\vec{L}^o_{sist}}{dt} \\
	&= \dfrac{d (\sum  \vec{r}_{i/o} \times m_i\vec{v}_{i/o})}{dt} \\
	&=  \sum  \vec{r}_{i/o} \times m_i\vec{a}_{i/o}\\ \\
	\sum \tau^o_{ext} &= \sum  \vec{r}_{i/o} \times \vec{F}_{i/o}
\end{split}
\end{equation*}
$$

Sólo los torques de las fuerzas exteriores cambian el momento cinético del sistema.


# Relacion entre O y CM para $\vec{L}^O$

$$\vec{L}^O_{sist} = \vec{L}^o_{cm} + \vec{L}^{cm}_{sist} $$

El momento cinético de un SP respecto de un punto fijo al LAB es igual a la suma del momento cinético del sistema **como si toda la masa estuviera concentrada en el CM** más el **momento cinético del SP relativo al CM.** 

El primer término se conoce como “momento cinético orbital” y el segundo como “momento cinético de spin”

# Conservacion de Momento Cinetico

A partir de $\tau^o_{ext} = \dfrac{d\vec{L}^o_{sist}}{dt}$

$$\sum \tau^o_{ext} = 0 \longrightarrow \Delta L^o_{sist} =0 $$

**_Observacion_**
El momento angular (Momento Cinetico) puede ser conservado con respecto de un sistema $o$ y no serlo desde otro sistema $o'$. 

Para aplicar el teorema de conservacion del momento angular hay que aclarar con respecto de cual sistema se evalua.


# Torque

$$ \vec{\tau}^o_{ext} = \vec{r}_o \times \vec{F} $$

![8129abfdfe3a8bbc7b18d8fe0f709b5a.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/04_sistema_particulas/images/8129abfdfe3a8bbc7b18d8fe0f709b5a.png)


# Referencias Bibliograficas

* [Fisica para estudiantes de Ingenieria - FIUBA - Unidad 4 - Sistema de partículas](https://campus.fi.uba.ar/pluginfile.php/373869/mod_resource/content/0/Unidad%204%20-%20Sistema%20de%20particulas%20Rev.%2002.pdf)

* Young-Freedman. Física universitaria Sears Zemansky- Volumen I y II. 12ºedición Pearson Addison Wesley 