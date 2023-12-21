<img src="https://github.com/hernancontigiani/ceia_memorias_especializacion/raw/master/Figures/logoFIUBA.jpg" width="250" align="center">

CURSO DE ESPECIALIZACIÓN EN INTELIGENCIA ARTIFICIAL

**VISIÓN POR COMPUTADORA II**

*Juan I. Munar, 11va Cohorte*

**CONTENIDO.** En el presente repositorio se encuentra el trabajo final de la materia Visión por Computadora II del CEIA, dictada entre octubre y diciembre de 2023 por Los profesores:
- Cavalieri Juan Ignacio
- Cornet Juan Ignacio
- Seyed Pakdaman

El trabajo representa el aprendizaje (a los golpes) de cómo abordar un problema de Visión por Computadora.

Se encuentran los siguientes documentos:

**DESARROLLO INICIAL** 

[PARTE 1 DE 2](https://github.com/juanimunar/CEIA_VC2_MUNAR/blob/main/tf-vpc2-munar-parte-1.ipynb), [PARTE 2 DE 2](https://github.com/juanimunar/CEIA_VC2_MUNAR/blob/main/tf-vpc2-munar-parte-2.ipynb):

Se trata de las pruebas realizadas inicialmente. Aquí aborde el problema del desbalance de datos y el entrenamiento. Los resultados son pobres tanto por el desbalance de datos como por el Negative Transfer. A partir de estos golpes iniciales, llego a una conclusión sobre cómo entrenar un modelo funcional.

**MODELO FINAL**

[MODELO FINAL](https://github.com/juanimunar/CEIA_VC2_MUNAR/blob/main/tf-vpc2-munar-modelo-final.ipynb)

Entrenamiento de una red ResNet18 afectando todos sus parámetros sobre un dataset balanceado con undersampling y oversampling. Los resultados son sorprendentemente buenos, superando ampliamente el accuracy que obtiene un médico a simple vista en todas las clases.

**PRESENTACIÓN**

[PRESENTACIÓN](https://github.com/juanimunar/CEIA_VC2_MUNAR/blob/main/Presentacion%20SkinCancerHAM10000.pptx)

Presentación modificada incluyendo información de los fracasos y del relativo éxito final.

**LINKS DE KAGGLE:**

[PARTE 1](https://www.kaggle.com/code/jimalt/tf-vpc2-munar-parte-1)
[PARTE 2](https://www.kaggle.com/code/jimalt/tf-vpc2-munar-parte-2)
[MODELO FINAL](https://www.kaggle.com/code/jimalt/tf-vpc2-munar-modelo-final)
