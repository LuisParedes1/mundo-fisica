---
title: Cinematica de Cuerpo Rigido
layout: posts
---


Un sistema es rígido si al considerar dos partículas cualesquiera de él se verifica que la distancia entre dichas partículas es un invariante, sin importar las interacciones externas o internas que soporten las partículas.


# Condicion cinemática de rigidez

Las componentes o proyecciones de las velocidades de A y de B, en la dirección que las une, deben ser iguales.

$$\vec{v}_1 \cdot cos(\theta_1) = \vec{v}_2 \cdot cos(\theta_2)$$

![bee2d8da3646d2b53fce3d804ed66cf9.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/db376f8f269840258d43a598c72f1fe1.png){: .align-center}


## Consecuencias de la condicion de rigidez

* Dado que la distancia entre dos puntos cualesquiera de un cuerpo rigido es constante, entonces la trayectoria relativa de un punto respecto del otro es un arco de circunferencia.

![fb4be7d8dba4f70b8036116c8f7ea216.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/db603fa979f145bba6d3eaf79c1a636d.png){: .align-center}

* La velocidad angular $\vec{\omega}$ y aceleracion angular $\vec{\gamma}$ deben ser unicos para todos los puntos del cuerpo rigido, de lo contrario se deformaria.


# Ecuacion de roto-translacion

Sean $\mathbb{a} \ y \ \mathbb{b}$ dos puntos cualesquiera del cuerpo rigido, y $O$ un punto fijo laboratorio.

## Velocidad de un punto del CR

$$ \vec{v}_{\tiny B/O} = \vec{v}_{\tiny A/O} + \vec{v}_{\tiny B/A}$$

$$ \vec{v}_{\tiny B/O} = \vec{v}_{\tiny A/O} + \vec{\omega} \times \vec{r}_{\tiny B/A}$$


- $\vec{v}_{\tiny A/O}$ es la velocidad de arrastre (translacion de A)
- $\vec{v}_{\tiny B/A}$ es la velocidad relativa (rotacion de B con respecto de A)


## Aceleracion de un punto del CR

$$ \vec{a}_{\tiny B/O} = \vec{a}_{\tiny A/O} + \vec{a}_{\tiny B/A}$$

$$ \vec{a}_{\tiny B/O} = \vec{a}_{\tiny A/O} + \vec{\gamma} \times \vec{r}_{\tiny B/A} +  \vec{\omega} \times \vec{v}_{\tiny B/A}$$

$$ \vec{a}_{\tiny B/O} = \vec{a}_{\tiny A/O} + \vec{\gamma} \times \vec{r}_{\tiny B/A} +  \vec{\omega} \times  \vec{\omega} \times \vec{r}_{\tiny B/A}$$


- $\vec{a}_{\tiny A/O}$ es la aceleracion de arrastre (translacion de A)
- $\vec{\gamma} \times \vec{r}_{\tiny B/A}$ es la aceleracion transversal.
- $\vec{\omega} \times  \vec{\omega} \times \vec{r}_{\tiny B/A}$ es la aceleracion radial.



# Casos particulares de movimiento de un Cuerpo Rigido

## Translacion Pura

Se mueve con traslación pura, cuando todos los puntos del mismo, en cada instante, tienen la misma velocidad y la misma aceleración.

![254cbf8d01fc6cdfd4f8b124b028020e.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/a0be4d1926084b06988b359a74844b32.png){: .align-center}

Todos los puntos de ese diámetro tienen velocidades paralelas a la velocidad del CM.

### Diagrama Vectorial

Decimos entonces que los diagramas vectoriales característicos de la traslación pura son rectangulares

![4cd977bced47c9bfa401cfd793dd34dd.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/4dc19023e83e4569b6c8ae1bd6e32b5d.png){: .align-center}


## Rotacion Pura

El movimiento de un CR es de rotación pura si, por lo menos, dos de sus puntos tienen velocidad nula (eje de rotación) y los restantes puntos del mismo realizan movimientos circulares alrededor del eje de rotación.

![607d7553282533b4c889d3e82e215df7.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/e3a57e5beb7446bbbc78961bb50178c4.png){: .align-center}

$$ \vec{v}_{\tiny B/O} = \vec{\omega} \times \vec{r}_{\tiny B/A}$$

$$ \vec{a}_{\tiny B/O} = \vec{\gamma} \times \vec{r}_{\tiny B/A} +  \vec{\omega} \times  \vec{\omega} \times \vec{r}_{\tiny B/A}$$

![f8bf40555347d063e352a3ab3d7aff8e.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/ac33d9c890b5428288968de2dec78775.png){: .align-center}


### Diagrama Vectorial

Los diagramas vectoriales de la rotación pura son doble triangulares y simétricos.

> En este caso la aceleración que hemos podido representar; NO ES la aceleración total de los puntos del diámetro elegido, sino solamente la aceleración transversal.

![6e88910fc089f875cff84bb11ca361de.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/032bfc3f6b36439c8fb361f6dd626143.png){: .align-center}


## Diagrama Rototranslacion 

Con el principio de superposición, dibujamos los diagramas vectoriales característicos de la roto – traslación como la suma de una traslación y una rotación pura

> La suma de estas aceleraciones no da por resultado la aceleración total de un punto del CR pues falta la aceleración normal que, en cada caso, es perpendicular a la aceleración tangencial. La suma vectorial de las tres componentes sí da por resultado dicha aceleración total. 
> 
![17d760efe7ba989b6d73984c7c94dad1.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/c768f8f3caf34e41943a00b70ee3cf96.png){: .align-center}

### Caso 1: La velocidad de traslación es de mayor intensidad que la de rotación. (Se traslada más rápido de lo que rota)

![eb9435dd7ba7afdd0711cf03b4c89007.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/7611038b3133404d90ab77bf4364f9a7.png){: .align-center}

El diagrama vectorial característico de velocidades de la roto – traslación cuando el CR se traslada más rápido de lo que rueda, es trapezoidal. Si el cuerpo se mueve respecto del piso, la velocidad del punto de contacto tiene el sentido de la velocidad de traslación.

Esto significa que el cuerpo deslizaría en el sentido de la traslación y la fuerza de rozamiento que se pone de manifiesto es la fuerza de rozamiento dinámica que se opone al deslizamiento entre ambas superficies.

### Caso 2: El cuerpo tiene mayor velocidad de rotación que de traslación (el cuerpo rota más rápido de lo que se traslada)\

![fc585d509abf6d1705cac6aa38f67a25.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/a541f23c698c424d91a92335bd90b902.png){: .align-center}

El diagrama vectorial característico de velocidades de la roto – traslación cuando el CR rota más rápido de lo que se traslada, es doble triangular asimétrico. Si el cuerpo se mueve respecto del piso la velocidad del punto de contacto tiene sentido contrario a la velocidad de traslación.

Esto significa que el cuerpo desliza en el sentido opuesto de la traslación y, la fuerza de rozamiento que se pone de manifiesto es la fuerza de rozamiento dinámica.


### Caso 3: Rodar sin deslizar. En este caso la velocidad de traslación es exactamente igual a la de rotación.

![18e9bd8874ae2e443cd6da8f653f9f2c.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/7278be227c0e4d9e9ee811ca9720faac.png){: .align-center}

El diagrama vectorial característico de velocidades de la roto – traslación cuando el CR rueda lo mismo que lo que se traslada, es triangular.

En este caso el punto de contacto tiene velocidad relativa a la superficie de apoyo nula. Esto significa que el cuerpo no desliza en ningún sentido. La fuerza de rozamiento que se pone de manifiesto es la fuerza de rozamiento estática y puede valer cero.


# Centro Instantaneo de Rotacion (CIR)

Los diagramas doble – triangulares son característicos de la rotación pura. El eje de rotación tiene velocidad nula. El punto de velocidad cero lo denominamos Centro Instantáneo de Rotación.

![a4f991f3f5a4836510f23432ccc831b7.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/6919003fc547466f81328bcc34f51659.png){: .align-center}

El CIR es un punto respecto del cual el Cuerpo Rigido se mueve con rotacion pura.

$$ \vec{v}_{\tiny B/CIR} = \vec{v}_{\tiny CIR/O} + \vec{\omega} \times \vec{r}_{\tiny B/CIR} = 0 + \vec{\omega} \times \vec{r}_{\tiny B/CIR} $$

$$ \vec{v}_{\tiny B/CIR} = \vec{\omega} \times \vec{r}_{\tiny B/CIR}$$

![b0f84520edc5b3b6bc9269df7a72a795.png](https://luisparedes1.github.io/mundo-fisica/assets/teoria/05_cuerpo_rigido/images/2363789192f2487487d0a3ec27c7edc2.png){: .align-center}


# Referencias Bibliograficas

* [Fisica para estudiantes de Ingenieria - FIUBA - Unidad 5 - Cinemática del cuerpo rígido](https://campus.fi.uba.ar/pluginfile.php/374008/mod_resource/content/0/Unidad%205%20-%20Cinematica%20del%20cuerpo%20r%C3%ADgido%20Rev%2002.pdf)

* Young-Freedman. Física universitaria Sears Zemansky- Volumen I y II. 12ºedición Pearson Addison Wesley 