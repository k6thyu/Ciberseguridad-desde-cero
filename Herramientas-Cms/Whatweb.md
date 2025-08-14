⚠️ **Aviso Legal**:
> Todo el contenido de este repositorio es únicamente con fines educativos y de aprendizaje en entornos controlados.  
> No me hago responsable del mal uso que se le pueda dar a la información aquí descrita.

<br><br>

## WhatWeb en Kali Linux 🔍:
WhatWeb es una herramienta de línea de comandos utilizada para **detectar qué tecnologías utiliza un sitio web**.
<br>
## Uso básico 💻:
```bash
whatweb ejemplo.com
whatweb -v ejemplo.com
whatweb -a (1,3,4) ejemplo.com
whatweb -i archivo.txt
whatweb --log-brief resultado.txt ejemplo.com
whatweb --log-json resultado.json ejemplo.com
whatweb --list-plugins
```
## Opciones principales 🔧:
-v: Modo verbose, más detalle por mostrar.<br>
-a: Controla el nivel de agresividad que puede ser 1,3 y 4.<br>
-i archivo.txt: Escaneo por la lista de objetivos.<br>
--log-brief: Guarda resultados con un resumen corto y legible a simple vista.<br>
--log-json: Guarda resultados de datos completos y estructurados para análisis posterior.<br>
--list-plugins: Te permite ver todos los plugins disponibles.<br>

## Ejemplos completos de las opciones principales 🔧:
[Ejemplo -v](https://github.com/user-attachments/assets/e842b951-a697-42c0-b85c-c6fca8f2116b)<br>
[Ejemplo -a](https://github.com/user-attachments/assets/ac1c7e48-9e57-41d8-9de6-ca5677a35daf)<br>
[Ejemplo -i](https://github.com/user-attachments/assets/b78d98ad-a186-47c3-a569-11dc7f40c75e)<br>
[Ejemplo --log-brief](https://github.com/user-attachments/assets/88efb675-60e9-431a-add2-60538a50d4d3)<br>
[Ejemplo --log-json](https://github.com/user-attachments/assets/c514ca26-d6e1-43ad-93f3-605b519f362a)<br>
[Ejemplo --list-plugins](https://github.com/user-attachments/assets/016ca996-0bc1-4310-b4d8-16c50eb310a8)<br>
