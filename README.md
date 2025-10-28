# Python

# Proyectos con entornos virtuales en Python

*Información general del repositorio:*

* Version de Python: 3.13.9.
 Hecho por: Sarah Castro.
* Ficha: 3203082.
* Programa: ADSO
* Instructor: Esteban Hernandez

# Descripción
Este es un repositorio el cual contiene dos proyectos de Python independientes y 
cada uno cuenta con su propio entorno virtual:

* **Proyecto_A:** Este cuenta con la implementación de Jupyter para análisis de algoritmos.
* **Proyecto_B:** Este tiene scripts con Pandas para procesamientos de datos. *(Pandas es una biblioteca de Python
  de código abierto y es una herramienta muy util para la manipulación y el análisis de datos)*.

Cada proyecto mantiene sus dependencias aisladas mediante entornos virtuales, siguiendo las mejores prácticas
de desarrollo de Python.

# **Estructura del Proyecto**
```
entornos-virtuales-python/
│
├── proyecto_A/
│   ├── venv_1/              (no incluido en el repo)
│   ├── src/
│   │   ├── algoritmo_a.py
│   │   └── notebook_a.ipynb
│   └── requirements.txt
│
├── proyecto_B/
│   ├── venv_2/              (no incluido en el repo)
│   ├── src/
│   │   ├── algoritmo_b1.py
│   │   └── algoritmo_b2.py
│   └── requirements.txt
│
├── capturas/                (imágenes de evidencia)
├── .gitignore
└── README.md
```

# Proyecto_A Jupyter

*Este proyecto utiliza Notebook para análisis de algoritmos*

* algoritmo_a.py: Calculadora de números primos.
* notebook_a.ipynb: Análisis y visualizaciones ded la serie de Fibonacci *(Secuencia de números donde cada
* uno es la suma de los dos anteriores, comenzando por 0 y 1)*.

**Entorno Virtual**

Creacion y activación de venv_1

<img width="599" height="98" alt="image" src="https://github.com/user-attachments/assets/d8c62a47-a3ac-4f95-bad1-ab5ec327dbe8" />

Instalación de paquetes

Jupytrer

<img width="1075" height="435" alt="image" src="https://github.com/user-attachments/assets/5131282e-e8a1-494e-a166-44fa32ac2855" />

Ejecucuión de Scripts

Ejecucuión de algoritmo_a.py

<img width="451" height="125" alt="image" src="https://github.com/user-attachments/assets/017234b6-d60f-415f-9651-d04b1c024429" />

Notebook ejecutado

<img width="1121" height="204" alt="image" src="https://github.com/user-attachments/assets/70788347-d13c-40fa-8120-7aa4bca64d39" />

Requirements.txt

<img width="670" height="93" alt="image" src="https://github.com/user-attachments/assets/0a2e90d3-0eff-4e5f-ac21-71850dc9c56e" />


# Instalación y Uso

```bash
# Navegar al proyecto
cd proyecto_A

# Crear entorno virtual
python -m venv venv_1

# Activar entorno (Windows CMD)
venv_1\Scripts\activate

# Activar entorno (Windows PowerShell)
venv_1\Scripts\Activate.ps1

# Instalar dependencias
pip install -r requirements.txt

# Ejecutar script
python src/algoritmo_a.py

# Abrir Jupyter Notebook
jupyter notebook
```

---

# Proyecto_B Pandas

Este proyecto utiliza Pandas para procesamiento y análisis de datos:

* algoritmo_b1.py: Análisis de datos de nombres y edades.
* algoritmo_b2.py: Usa la librería pandas para trabajar con una lista de números.

# Entorno Virtual

Creación de venv_2

<img width="593" height="64" alt="image" src="https://github.com/user-attachments/assets/be82011c-9f1a-4447-9471-2d0768ff323e" />

Instalación de paquetes

Instalación de Pandas

<img width="685" height="61" alt="image" src="https://github.com/user-attachments/assets/02bde2ba-27d5-4986-b03f-1de88d2dabf6" />

Ejecucuión de Scripts

Ejecucuión de algoritmo_b1.py

<img width="770" height="136" alt="image" src="https://github.com/user-attachments/assets/2ee1f81b-25bb-4ff1-9038-980a28a58c7a" />

Ejecución de algoritmo_b2.py

<img width="564" height="171" alt="image" src="https://github.com/user-attachments/assets/b7b9f999-2c67-436a-a932-138c1c52b638" />

Requirements.txt

<img width="1106" height="140" alt="image" src="https://github.com/user-attachments/assets/4044ccc9-61de-4e26-94fa-b77956b059e8" />


# Instalación y Uso
```bash
# Navegar al proyecto
cd proyecto_B

# Crear entorno virtual
python -m venv venv_2

# Activar entorno (Windows CMD)
venv_2\Scripts\activate

# Activar entorno (Windows PowerShell)
venv_2\Scripts\Activate.ps1

# Instalar dependencias
pip install -r requirements.txt

# Ejecutar scripts
python src/algoritmo_b1.py
python src/algoritmo_b2.py
```

# Estructura de Carpetas

<img width="197" height="358" alt="image" src="https://github.com/user-attachments/assets/e59304dc-8e3a-40c3-9058-7d3712986325" />

# **Enlace Repositorio**

https://github.com/Sarah-con-h/Python.git




