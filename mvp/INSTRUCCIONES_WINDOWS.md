# Ejecutar Aranjuez Limpio 360 en Windows

## Requisitos

- Windows 10/11.
- Python 3.10 o superior disponible en `PATH`.
- No requiere instalar paquetes Python adicionales para la ejecución entregada.
- No requiere Node.js, servidor de base de datos ni conexión a servicios externos de mapas.

## Pasos

1. Descarga `Aranjuez_Limpio_360_MVP_FINAL_EJECUTABLE_WINDOWS_OK.zip`.
2. Extrae **todo** el contenido del ZIP.
3. Entra a la carpeta `Aranjuez_Limpio_360_MVP_FINAL`.
4. Ejecuta `ABRIR_MVP.bat`.
5. Mantén la consola abierta.
6. Abre en el navegador `http://127.0.0.1:8765`.

Si Windows presenta un problema de codificación UTF-8 en una copia anterior, la versión `WINDOWS_OK` ya incorpora el ajuste correspondiente.

## Qué verifica al iniciar

El visor comprueba que la SQLite, los controles y el snapshot correspondan a la versión auditada. La base se abre en modo de solo lectura.
