# Usa la imagen base de Jupyter
FROM jupyter/datascience-notebook

# Establece el directorio de trabajo en el contenedor
WORKDIR /home/jovyan

# Copia el archivo requirements.txt al contenedor
COPY requirements.txt .

# Instala las dependencias desde el archivo requirements.txt
RUN pip install --no-cache-dir -r requirements.txt