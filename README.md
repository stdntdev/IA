# Como funciona una red neuronal

## 1. Introduccion
Imagina que le muestras a una inteligencia artificial una imagen de la letra **“A”**. ¿Cómo hace para decirte “eso es una A”?

No “ve” como nosotros. Lo que hace es transformar la imagen en números y pasarlos por una serie de capas que van detectando patrones cada vez más complejos: primero líneas, luego curvas, y al final la letra completa.

Hoy vamos a desglosar las partes de una red neuronal y cómo cada una contribuye a reconocer letras.

## 2. Las partes principales de una red neuronal

Una red neuronal se compone de varias capas. Cada una tiene un trabajo específico.

#### 2.1. Capa de entrada (Input Layer)
Es la primera puerta. Aquí entra la imagen convertida en números.

Cada píxel de la imagen se convierte en un valor (normalmente entre 0 y 1).  
Si la imagen es de 28×28 píxeles (como en el famoso dataset MNIST), tienes 784 números que entran a la red.

**Explicación breve:**  
“La capa de entrada no piensa, solo recibe los datos crudos de la imagen.”
