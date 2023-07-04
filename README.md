# WEB_SCRAPING-WORK
SISTEMA WEB UTILIZANDO WEB SCRAPING Y PROGRAMACIÓN PARALELA PARA MEJORAR LA EFICIENCIA AL EXTRAER DATOS DESDE LA WEB SOBRE OFERTAS LABORALES

---

Sistema web que usará la programación paralela para extraer datos de ofertas laborales de 3 distintas páginas web donde al terminar la ejecución se nos mostrará los resultados encontrados.

---

TEMAS ABORDADOS:

1. SECCIONES CRÍTICA

-  Identificar secciones para que no ocurran deadlock donde los hilos se quiten recursos

3. CONDICIÓN DE CARRERA

-  Para que los hilos no accedan a un mismo recurso en la página web

5. THREADING

-  Para que los hilos no accedan a un mismo recurso en la página web

---

Instalación

```bash

# 1. Instalar virtualenv, en caso no lo tenga
pip install virtualenv

# 2. Crear un entorno virtual con nombre "venv"
python -m venv venv

# 3. Dirigirnos a la carpeta creada Scripts dentro de venv
cd venv/Scripts

# 4. Instalar las librerías necesarias
pip install -r ../../requirements.txt

# 5. Ejecutar el programa
python ../../src/index.py

# 6. Entrar al siguiente servidor
http://127.0.0.1:5000

```