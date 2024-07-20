# Realtrack

## Descripción
 
Realtrack es una API basada en Django para obtener la ubicacion en tiempo real de unidades vehiculares.    

## Requisitos

- Python 3.12
- Conda (para gestión de entornos y dependencias)

## Instalación

Sigue estos pasos para configurar el entorno de desarrollo:

1. *Clonar el Repositorio*

   Clona este repositorio en tu máquina local:

   bash
   git clone https://github.com/tuusuario/RealtrackAPI.git
   cd RealtrackAPI

2. **Crear el Entorno Conda**

   Crea un entorno Conda usando el archivo *environment.yml*:

   bash
   conda env create --prefix ./entorno1 -f environment.yml

3. *Activar el Entorno*

   Activa el entorno Conda recién creado:

   bash
   conda activate ./entorno1

4. **Instalar Dependencias**

   Si no usas Conda, puedes instalar las dependencias manualmente con pip:

   bash
   pip install -r requirements.txt

5. *Migraciones de Base de Datos*

   Aplica las migraciones para configurar la base de datos:

   bash
   python manage.py migrate

6. **Ejecutar el Servidor de Desarrollo**

   Inicia el servidor de desarrollo de Django:

   bash
   python manage.py runserver
  
  La API estará disponible en http://127.0.0.1:8000/.