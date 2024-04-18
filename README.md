# TALLER 9: TAREA DE LLM (IA)
#### Hecho por: Daniel Santiago Gómez Zabala

Este repositorio contiene una serie de programas desarrollados utilizando las tecnologías LangChain, Pinecone y OpenAI. Cada programa aborda un desafío diferente relacionado con el procesamiento del lenguaje natural (Python) y la búsqueda de información.

## GETTING STARTED

1. Asegúrate de tener Python instalado en tu sistema. Puedes descargar e instalar Python desde el sitio web oficial de Python (https://www.python.org/). Se recomienda utilizar Python 3.12.3
2. Configura las claves de API de OpenAI en tu entorno. Las claves de API proporcionadas en el archivo README.md deben ser válidas y accesibles desde tu máquina. Si no tienes una clave de API de OpenAI, puedes obtener una registrándote en su sitio web (https://openai.com/).
3. Instala las dependencias que se encuentran dentro del archivo requirements.txt en caso de que tu IDE no te ofrezca la opción de instalarlas automaticamente haga uso de los siguiente pasos:
    ```
    python -m venv venv
    venv\Scripts\activate
    pip install -r requirements.txt
    ``` 

## INSTALLING

Debe clonar el respositorio para poder hacer uso de la app con el comando que se encuentra a continuación

```
https://github.com/sagomezab/Taller9_AREP.git
```

Para ejecutar cada archivo por separado debe ingresar a la carpeta *Taller9_AREP* e ingresar los siguientes comandos:

```
py main.py
py pinecone.py
py llmmemorydb.py
```
## Explanations

Descripción de los retos:

1. Programa 1: Interacción con ChatGPT:
    - Este programa utiliza la integración de LangChain con OpenAI para enviar solicitudes a ChatGPT y recuperar las respuestas.
    - Se envía una pregunta sobre la teoría de la ciencia de Popper a ChatGPT y se imprime la respuesta obtenida.
2. Programa 2: Creación de un RAG utilizando una base de datos vectorial en memoria:
    - Se implementa un RAG (Récord de Acceso Guiado) utilizando un vectorstore en memoria para recuperar información de documentos.
    - Se carga un conjunto de documentos de una página web y se construye un vectorstore en memoria.
    - Se realiza una consulta sobre "Task Decomposition" al RAG y se imprime la respuesta obtenida.
3. Programa 3: Creación de un RAG utilizando Pinecone:
    - Se crea un RAG utilizando la integración de LangChain con Pinecone para recuperar información de documentos.
    - Se carga un conjunto de documentos de un archivo de texto y se indexan en Pinecone.
    - Se realiza una consulta sobre "What is a distributed pointcut" al RAG y se imprime la respuesta obtenida.

## Version

1.0
## Author

Daniel Santiago Gómez Zabala [SAGOMEZAB](https://github.com/sagomezab)
