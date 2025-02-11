# RAGs - Proyecto de Recuperación Aumentada con Generación

Este repositorio contiene un proyecto de Recuperación Aumentada con Generación (RAG) utilizando la API de OpenAI. Asegúrate de configurar correctamente las dependencias y las credenciales antes de ejecutar el proyecto.

## 🚀 Instalación

### 1️⃣ Clonar el repositorio
```sh
git clone https://github.com/Pablo-Escamez/RAGs.git
cd RAGs
```

### 2️⃣ Crear y activar un entorno virtual (opcional pero recomendado)
```sh
python -m venv venv
# Activar en Windows
venv\Scripts\activate
# Activar en macOS/Linux
source venv/bin/activate
```

### 3️⃣ Instalar dependencias
```sh
pip install -r requirements.txt
```

## 🔑 Configuración de la API de OpenAI

El proyecto requiere una clave de API de OpenAI para funcionar. Debes crear un archivo `.env` en la raíz del proyecto y agregar la clave de la siguiente manera:

```
OPENAI_API_KEY=tu_api_key_aqui
```

Si no tienes una clave de OpenAI, puedes obtenerla en [OpenAI](https://platform.openai.com/signup/).

## 🏃‍♂️ Uso

Ejecuta el script principal con:
```sh
python main.py
```

## 📜 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

