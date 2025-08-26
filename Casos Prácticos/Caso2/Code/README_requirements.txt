Los requisitos necesarios para correr el código de caso2_PCA.ipynb.

Es necesario crear un entorno personalizado para garantizar la compatibilidad entre Tensorflow, Numpy y Scikit-Learn. Para ello se recomienda usar:

Versión de Python: 

- Python 3.10

Versiones de librerías:

- tensorflow==2.12.0
- scikit-learn==1.2.2
- numpy==1.23.5
- pandas==1.5.3

Para crear el entorno, se recomienda usar conda. Usando el siguiente comando se crea el entorno "tfm_env":

```bash
conda create -n tfm_env python=3.10 -y
conda activate tfm_env
pip install -r requirements.txt
```

De esta forma se instala diréctamente el archivo requirements.txt, con las versiones indicadas anteriormente.

Si se utiliza VSCode para leer el código, se debe escoger el entorno "tfm_env" y posteriormente reiniciar el Kernel.
