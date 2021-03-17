
Proceso de implementación para el uso del Custom Web Control en TIA Portal

1. Comprimir las carpetas "assets", "control" y el archivo "manifest.json"
con un click derecho → "Enviar a" → "Carpeta comprimida (en zip)"

2. Usar el código GUID almacenado en "manifest.json" como nombre de archivo, de
modo tal que el nombre sea del siguiente formato (las x equivalen al GUID):
{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}.zip

En este caso utilizaremos:

{4B71B0D4-530F-4646-B129-7A557FEA064B}.zip

Existen dos opciones para integrarlo al TIA Portal

a. Hacerlo disponible solo para solo para un proyecto en específico.
Guardar el Custom Web Control en tu carpeta de proyecto:
…Project_1\UserFiles\ CustomControls\{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}.zip

b. Hacerlo disponible para todos los proyectos.
Guardar el Custom Web Control en la ruta de instalación del TIA Portal:
C:\Program Files\Siemens\Automation\Portal Vxx\Data\Hmi\ CustomControls\{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}.zip





Integration into TIA Portal
Before you can use the Custom Web Control in TIA Portal, you have two ways to install it (also refer to the official manual under "Installing a Custom Web Control"):
1. Only make available for a specific project Place your Custom Web Control in your project folder: …Project_1\UserFiles\ CustomControls\{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}.zip
2. Make available for all projects Place your Custom Web Control in the installation path of TIA Portal: 