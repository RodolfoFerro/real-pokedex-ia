![Pokédex](media/banner.png)

![GitHub last commit](https://img.shields.io/github/last-commit/RodolfoFerro/real-pokedex-ia?style=for-the-badge) <br>
![GitHub repo size](https://img.shields.io/github/repo-size/RodolfoFerro/real-pokedex-ia?style=for-the-badge) <br>
![GitHub](https://img.shields.io/github/license/RodolfoFerro/real-pokedex-ia?style=for-the-badge) <br>
[![Slides](https://img.shields.io/static/v1?label=Slides&message=Google%20Slides&color=tomato&style=for-the-badge)](https://docs.google.com/presentation/d/e/2PACX-1vSq4pQd0YRSyNcfn86rdhZEAHZTXB93C9toqVj2gwxvZcUOZUy0mRmSnmv-3fTwFYXOvBXMLtfVQeWI/pub?start=false&loop=false&delayms=3000)


## Descripción

#### _"Tu Pokedéx en La Vida Real: Programa tu clasificador de animales con redes neuronales artificiales"_

La inteligencia artificial (IA) se ha utilizado y continúa evolucionando para resolver muchos problemas, explorar diferentes dominios de la ciencia y desarrollar aplicaciones para el día a día. Seguro habrás notado que tu red social es capaz de encontrar tu rostro en fotografías e identificar a tus amigas y amigos. ¿Te has preguntado cómo funcionan estos algoritmos? En este taller aprenderemos el funcionamiento básico detrás y cómo podemos aplicarlo a un dominio específico: crear un clasificador de especies que puedes adaptar para tu propio conjunto de datos.


## Contenido del taller

1. Contexto general sobre la IA
2. Introducción al aprendizaje de máquina
3. Conceptos básicos: Conjunto de entrenamiento, conjunto de prueba
4. Redes neuronales artificiales:
    - Perceptrón
    - Perceptrón multicapa y redes profundas
    - Redes neuronales convolucionales
5. Clasificador de animales


Puedes encontrar los slides en vivo [**AQUÍ**](https://docs.google.com/presentation/d/e/2PACX-1vSq4pQd0YRSyNcfn86rdhZEAHZTXB93C9toqVj2gwxvZcUOZUy0mRmSnmv-3fTwFYXOvBXMLtfVQeWI/pub?start=false&loop=false&delayms=3000).

> Es importante mencionar que el curso hará uso de un ambiente en la nube para el desarrollo del material; sin embargo, podrás ejecutar el código de manera local si cuentas con los requerimeintos necesarios.

## Instrucciones para estudiantes

El código y los ejercicios se desarrollarán en Python 3.7+ usando [TensorFlow](https://www.tensorflow.org/), que adopta a [Keras](https://www.tensorflow.org/versions/r2.0/api_docs/python/tf/keras) como interfaz de alto nivel para construir y entrenar redes neuronales.

#### Requerimientos:
* Una laptop.
* Este repositorio de GitHub clonado y actualizado antes del taller.
* Un sentido aventurero en los datos y la IA.
* Un ambiente Python 3.7+ con Anaconda (en casod e querer ejecutar el código de manera local).

Los talleres serán impartidos usando *notebooks* de Jupyter, documentos con código ejecutable, texto, ecuaciones, visualizaciones, imágenes y demás material. Los *notebooks* se pueden crear y ejecutar en la nube vía Google Colab o de manera local en tu computadora a través de [Jupyter Notebooks o JupyterLab](https://jupyter.org/).

Para fines prácticos de este taller (al ser online) utilizaremos Google Colab.

### Google Colab

[Colab](https://colab.research.google.com) es un servicio de Google para ejecutar *notebooks* en la nube. Provee ambientes de Python 2 y 3 con CPUs, GPUs y TPUs. ¡Y es gratis! Solo necesitas tener una cuenta de Google o crear una.

Recomendamos que elijas un ambiente con Python 3 y GPU. Para activarlo:

* Abre el menú `Entorno de ejecución`
* Elige la opción `Restablecer todos los entornos de ejecución...` .
* Vuelve a abrir `Entorno de ejecución`
* Elige `Cambiar tipo de entorno de ejecución`
* Selecciona Python 3 como `Tipo de ejecución` y GPU de la lista de `Acelerador por hardware`

La siguiente captura de pantalla ilustra este proceso.

![](media/escoge_acelerador.png)

En [Colab](https://colab.research.google.com) puedes crear un nuevo *notebook*, subir uno existente desde tu computadora o importarlo de Google Drive o GitHub.
