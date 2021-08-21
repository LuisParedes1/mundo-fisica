---
title: Dioptras
layout: posts
---

Resumen de Dioptras

# Sistema de referencia

Poniendo el sistema de referencia en el **vertice de la dioptra**, y poniendo el sentido positivo en contra del sentido de la luz.

> Convención utilizada: \\
> Eje x positivo en el sentido contrario a la luz incidente


![1a43a01fc27be228ed099494dc9fb545.png](/assets/teoria/08_optica_geometrica/images/586e144649f04df3b9757c04c92b907d.png){: .align-center}


## Dioptras

Las dioptras son superficies que separan dos medios isotropos, con indice de refraccion $n_1$ y $n_2$

![88359fc8641bf08845d2fd0d8370bbab.png](/assets/teoria/08_optica_geometrica/images/80e3f58d52774bc996f65dfdc0f2afc9.png){: .align-center}

Cuando el rayo atraviesa la dioptra, se utiliza la ley de Snell [^1] para determinar el angulo con que sale, asi determinar si se trata de una dioptra **convergente** o **divergente**.

![347f1e8463e7f86b0a41b8dcf05db98f.png](/assets/teoria/08_optica_geometrica/images/630fa6419b914585ba7cf854c9875199.png){: .align-center}

![c891b402c900e6b607d57f46a00d9eca.png](/assets/teoria/08_optica_geometrica/images/8f08c208d5c6455dad08d6369dbae60a.png){: .align-center}

> Observar que lo unico que cambio en los ejemplos es el indice de refraccion. Por lo tanto este determina si es convergente o divergente.


# Focos

## Foco Imagen $f'$

El foco imagen es el punto donde se forma la imagen de un objeto ubicado sobre el eje óptico en el infinito.

$$s = \infty \, \, \, ,\, \, \, s' = f'$$

## Foco Objeto $f$

El foco objeto es el punto sobre el eje óptico donde se debe colocar un objeto para que la imagen se forme en el infinito.

$$s = f \, \, \, ,\, \, \, s' = \infty$$



# Formacion de Rayos

* El rayo que pasa por el centro de la dioptra esferica no cambia de direccion
* El rayo que pasa por el vertice tienen como recta normal al eje optico. Con este hallo, usando la ley de Snell [^1], el angulo de desviacion

![f676f71f976208345a8fb3a931032e1f.png](/assets/teoria/08_optica_geometrica/images/9390e4944ee44858bc0fe48108ee71b3.png){: .align-center}

## Otras Opciones
* Un rayo que pase paralelo al eje optico "proviene del infinito" y pasa por el foco imagen.



# Ecuacion de Dioptras

$$
\begin{equation}
\frac{n_1}{s} - \frac{n_2}{s'} = \frac{n_1-n_2}{R}
\end{equation}
$$

## Aumento Lateral 

$$
\begin{equation}
A = \frac{h'}{h} = \frac{n_1  s'}{n_2 s}
\end{equation}
$$

A partir de la ecuacion de dioptras, 

* El foco objeto, lo encuentro como $s = f \, \, \, ,\, \, \, s' = \infty$
* El foco imagen, lo encuentro como $s = \infty \, \, \, ,\, \, \, s' = f'$

Los focos cumplen la relacion:

$$
\begin{equation}
f+f' = R
\end{equation}
$$


> El foco objeto es distinto al foco imagen para dioptras.
>
> $$ \mid f \mid \neq \mid f' \mid$$

# Regla Nemotecnica

* **DIOPTRAS CONVERGENTES:** foco objeto positivo, foco imagen negativo.
* **DIOPTRAS DIVERGENTES**: foco objeto negativo, foco imagen positivo.

> Siempre verificar por primeros principios, y hacer el camino de rayos para asegurarse que el resultado tenga sentido.

# Referencias Bibliograficas

* [Fisica para estudiantes de Ingenieria - FIUBA - Unidad  10 - Óptica Geométrica](https://campus.fi.uba.ar/pluginfile.php/375387/mod_resource/content/1/Unidad%2010%20-%20Optica%20Geometrica%20Rev.01.pdf)


[^1]: [Ley de Snell]()