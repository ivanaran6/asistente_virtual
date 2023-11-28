# Asistente de Voz en Python

Este proyecto implementa un asistente de voz en Python utilizando diferentes librerías como `pyttsx3`, `speech_recognition`, `pywhatkit`, `yfinance`, `pyjokes`, `webbrowser`, `datetime`, y `wikipedia`. El asistente puede realizar diversas acciones a través de comandos de voz.

## Funcionalidades

- **Reconocimiento de voz:** Convierte el audio del micrófono en texto utilizando la librería `speech_recognition`.
- **Acciones de búsqueda:** Realiza búsquedas en la web utilizando `pywhatkit` y `webbrowser`.
- **Información de tiempo y fecha:** Ofrece la hora actual, el día de la semana, entre otras funciones de tiempo utilizando `datetime`.
- **Búsqueda en Wikipedia:** Busca y devuelve información de Wikipedia utilizando la librería `wikipedia`.
- **Interacción con YouTube:** Abre la página de YouTube con el comando de voz.
- **Reproducción de música en YouTube:** Reproduce videos de YouTube a través de comandos de voz.

## Uso

### Requisitos

- Python instalado en el sistema.
- Instalar las librerías requeridas ejecutando `pip install pyttsx3 speech_recognition pywhatkit yfinance pyjokes wikipedia`.

### Ejecución

Ejecuta el archivo `asistente_voz.py` para iniciar el asistente.

### Comandos de voz

- Di "Abrir YouTube" para abrir la página de YouTube.
- Di "Abrir el navegador" para abrir el navegador web.
- Di "¿Qué día es hoy?" para obtener el día de la semana.
- Di "¿Qué hora es?" para obtener la hora actual.
- Di "Busca en Wikipedia" seguido de tu consulta para buscar información en Wikipedia.
- Di "Busca en internet" seguido de tu búsqueda para realizar una búsqueda en la web.
- Di "Reproducir" seguido de la canción o video para reproducir en YouTube.
- Di "Broma" para escuchar un chiste aleatorio.
- Di "Precio de las acciones de [Nombre de la empresa]" para obtener el precio de las acciones de una empresa.
- Di "Adiós" para finalizar la interacción con el asistente.
