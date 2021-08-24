---
title: Energia de Sistema de Particulas
layout: posts
---

Resumen de Energia en un Sistema de Particulas

# Trabajo $W_{sist}$

El $W_{total}$ es la suma de los trabajos de todas las fuerzas actuantes tanto interiores como exteriores al sistema.

En un sistema de partículas éstas pueden moverse libremente y por esa razón sus desplazamientos no necesariamente son iguales. Al diferir en sus respectivos  desplazamientos entonces sus trabajos no se anulan.


El $W_{FNC}$ es la suma de los trabajos de todas las fuerzas no conservativas, sean estas interiores o exteriores al SP.

# Energia Cinetica $Ec_{\tiny sist}$

$$
\begin{equation}
Ec^o_{sist} = \sum \frac{1}{2}m_i v_{i/o}^2 
\end{equation}
$$

$$
\begin{equation}
Ec^o_{sist} = \frac{1}{2}M v_{cm/o}^2 + \sum \frac{1}{2}m_i v_{i/cm}^2
\end{equation}
$$

$$
\begin{equation}
Ec^o_{sist} = Ec^{o}_{\tiny CM/o} + Ec^{\tiny CM}_{sist}
\end{equation}
$$

Esto significa que: la energía cinética total del sistema de partículas respecto al LAB no es igual a la energía cinética del centro de masa, sino que hay que agregarle un término. **Este término es la energía cinética relativa al centro de masa.**

# Energia Potencial Gravitatiroa

$$E_{pg} = \sum m_i \cdot g \cdot y_i= g \cdot \sum m_i  \cdot y_i = g M y_{cm} $$

$$E_{pg} = g \cdot M \cdot y_{cm} $$


# Ecuaciones universales de la dinamica de un SP

$$
\begin{equation}
\vec{\tau}^o_{ext} = \dfrac{d\vec{L}^o_{sist}}{dt} = \sum  \vec{r}_{i/o} \times \vec{F}_{ext	}
\end{equation}
$$

$$
\begin{equation}
\sum \vec{F}_{ext} =  \dfrac{d  \vec{P}^o_{sist}}{dt}  = M \vec{a}_{cm}
\end{equation}
$$

$$
\begin{equation}
W_{FNC}=\Delta Ec + \Delta Ep
\end{equation}
$$

$$
\begin{equation}
W_{Total}=\Delta Ec 
\end{equation}
$$

## Ecuaciones Impulsivas

$$\Delta \vec{L}^o_{sist} = \sum  \vec{r}_{i/o} \times \vec{J}_{ext	} $$

Donde $$\vec{r}_{i/o} \times \vec{J}_{ext}$$ se denomina impulso angular.

La expresión anterior se lee: La suma de los impulsos angulares de todas las fuerzas exteriores actuantes en nuestro SP respecto a un punto es igual al cambio de momento cinético respecto de ese mismo punto.

$$\vec{J}_{ext	} = \vec{P}_{sist_{final}} - \vec{P}_{sist_{inic}}  $$

Si la sumatoria de los impulsos de las fuerzas exteriores al SP es nula, entonces se conserva la cantidad de movimiento del sistema.

### Casos:

1. Si no existen fuerzas exteriores al sistema. 
Es decir, el SP se encuentra aislado.
2. Si las fuerzas exteriores están en equilibrio.
Es decir $\sum \vec{F}_{ext} =0$. Por la ley de inercia, el cuerpo está quieto o se mueve con movimiento uniforme y rectilíneo.
3. Si la fuerza exterior neta en una dirección es nula, se conserva la cantidad de movimiento del SP en esa dirección.
Un ejemplo muy sencillo de este caso es el tiro oblicuo, se conserva $\vec{P}$ en la dirección horizontal.
4. En las colisiones que cumplan las siguientes condiciones. Si la fuerza exterior es contante

$$\vec{J}_{ext	} = \int_0^t \vec{F}_{\tiny NETA}dt= \vec{F}_{\tiny NETA} \int_0^t dt$$

Si $\Delta t \rightarrow 0$ entonces $\vec{J}_{ext}=0$

En los choques, los impulsos de las fuerzas exteriores constantes o acotadas son nulos (despreciables). 

Por ejemplo, el caso del impulso de la fuerza gravitatoria para una granada que explota en el aire.

# Colisiones

## Perfectamente inelástico o plástico

En esta expresión $\vec{p_1}$ y $\vec{p_2}$ son las cantidades de movimiento de cada una de las partículas que chocan y $\vec{v_f}$ la velocidad que tienen después del choque cuando siguen unidas.


$$\vec{P_f} = \vec{P_i}$$

$$\vec{p_1} + \vec{p_2} = (m_1+m_2)\vec{v}_f$$

## Perfectamente Elastica

En este choque suponemos que los cuerpos después de chocar adquieren exactamente la forma que tenían antes del choque. Si esto es así, no hay pérdida de energía mecánica por deformación, calor o sonido.

Por esta razón además de la conservación de la cantidad de movimiento podemos plantear la conservación de la energía cinética.

* $\vec{P_f} = \vec{P_i}$
* $\sum E_{c_{inic}} = \sum E_{c_{fin}}$

# Coheficiente de Restitucion

$$e = \dfrac{ v_{f_{ax}}-v_{f_{bx}} } {   v_{i_{bx}}-v_{i_{ax}} } = - \dfrac{V_r^f}{V_r^o}$$

> Notemos que las velocidades relativas pueden ser positivas o negativas

Para el punto A (choque plástico): $e = 0$

Para el punto C (choque elástico): : $e = 1$

Para el punto B (choque inelástico): $0< e < 1$


# Referencias Bibliograficas

* [Fisica para estudiantes de Ingenieria - FIUBA - Unidad 4 - Sistema de partículas](https://campus.fi.uba.ar/pluginfile.php/373869/mod_resource/content/0/Unidad%204%20-%20Sistema%20de%20particulas%20Rev.%2002.pdf)

* Young-Freedman. Física universitaria Sears Zemansky- Volumen I y II. 12ºedición Pearson Addison Wesley 