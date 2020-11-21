# FashionClassifier

Este repositorio es un complemento del Trabajo de fin de grado **"Desarrollo de una red neuronal profunda para la clasificación y caracterización de prendas de vestir",** **desarrollado por Víctor Herrera Delgado y tutorizado por Cayetano Guerra Artal.**

El trabajo consistió en la aplicación de distintas técnicas de las redes neuronales convolucionales sobre redes VGG para la clasificación de prendas de vestir, que acabó siendo ampliado a elementos encontrados en tiendas de moda con la elección del dataset ["Fashion product images dataset" creado por Param Aggarwal](https://github.com/user/repo/blob/branch/other_file.md).

## Objetivo del contenido de este repositorio

La creación del código incluido en este repositorio se ha realizado por dos motivos:

- **Por seguridad**, pues si bien se trata de un proyecto de investigación, se quería mostrar que había más trabajo detrás.

-**Para interés de compañeros** que estén **empezando en el uso de redes neuronales** y a los cuales les pueda servir de ejemplo el código realizado para desarrollar sus propios proyectos.

Repito que el código encontrado en los documentos **no está directamente relacionado al trabajo hecho por el estudiante, pues se trató de un trabajo de investigación** en el cual se realizaron más pruebas, pero se creyó que una versión limpia y más sencilla del código utilizado con referencia a la misma temática podía ser de uso para la comunidad o para su inclusión en la biblioteca. 

## ¿Que encontrará en este repositorio?
El repositorio cuenta con:
- El documento **Desarrollo de una red neuronal profunda para la clasificación y caracterización de prendas de vestir** para su lectura.
- Una versión limpia (sin datos de ejecución) para uso público del **código** que se estuvo desarrollando para el entrenamiento y validación de los modelos que se realizaron para este proyecto. Este cuenta con explicaciones tanto para comprender el desarrollo del proyecto como para que cualquier persona pueda poner a ejecutar su propia versión.
- Imágenes originales de los **heatmaps de las matrices de confusión**, para apreciar mejor sus resultados.
- Los **mejores modelos entrenados**, de los cuales pueden consultar su fiabilidad en el proyecto. Debido a su peso, solo podrán ser accedidos a través de [este enlace](https://drive.google.com/drive/folders/1AD76gjr83MCqMVX55NFPKENn_asZ0RZR?usp=sharing). En caso de querer cargarlos, puede consultar como hacerlo en la aplicación de ejemplo.
- **Aplicación de ejemplo** (AplicacionRedes), un notebook para poder ejecutar la clasificación de imágenes  individuales, ya sean del dataset o del usuario. Esta usar los modelos comentados anteriormente.

Tenga en cuenta que para el uso de los notebooks será necesaria la instalación de las librerías importadas al principio de cada notebook así como actualizar las direcciones a las que accede. **Es necesario tener instalado cuda.**

