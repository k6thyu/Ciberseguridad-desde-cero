⚠️ **Aviso Legal**:
> Todo el contenido de este repositorio es únicamente con fines educativos y de aprendizaje en entornos controlados.  
> No me hago responsable del mal uso que se le pueda dar a la información aquí descrita.

<br><br>
# KnockPy 🔍:
KnockPy es una herramienta desarrollada en Python para la enumeración de subdominios en un dominio objetivo mediante el uso de listas de palabras (wordlists). Resulta especialmente útil en la fase de reconocimiento durante pruebas de penetración.

# Instalación 📦:
git clone https://github.com/santiko/Knockpy.git

# Uso básico 💻: 
*Escaneo simple de un dominio:*<br>
python2 knockpy ejemplo.com

# Opciones principales 🔧:
-w: Especifica una wordlist personalizada o predeterminada.<br>
-d: Especifica un dominio web.<br>

# Ejemplos completos de las opciones principales 🔧: 
[Ejemplo1](https://github.com/user-attachments/assets/e9bd2661-7343-4f9e-8113-b37904e6cd65)<br>
[Ejemplo2](https://github.com/user-attachments/assets/922e84f2-0ad7-44ad-87c4-8f6a27837d53)<br>

## Explicación de los ejemplos 🔒: 
*Python2:* Es el encargado de que el script se ejecute correctamente.<br>
*Knockpy:* Es el script principal que realiza la enumeración de subdominios.<br>
*Google.com:* Es el dominio objetivo en el cual se realiza la búsqueda de subdominios.<br>
*--Wordlist:* Es el indicador de qué wordlist se utilizará para el análisis.<br>
*Wordlist.txt:* Es la encargada de descubrir los subdominios.<br>

<br><br>
# Dirforcer 🔍:
Dirforcer es una herramienta de fuerza bruta que fue diseñada para la búsqueda de archivos ocultos y directorios en servidores web. Su objetivo principal es ayudar a descubrir rutas no registradas o protegidas que no aparecen fácilmente navegando por un sitio web, lo que puede ser útil para pruebas de seguridad o pentesting.

# Instalación 📦:
git clone https://github.com/thiagoarajosec/dirforcer.git<br>
*Dependencia*:<br> 
pipx install pyfiglet

# Uso básico 💻: 
python3 dirforcer.py -d https://ejemplo.com -w directorios.txt

# Códigos HTTP importantes 🚦:
| Código | Significado                 | Descripción breve                           |
|--------|----------------------------|---------------------------------------------|
| 200    | OK                         | La solicitud fue exitosa y la página existe.|
| 301    | Redirección permanente     | La URL solicitada se ha movido permanentemente a otra ubicación.|
| 302    | Redirección temporal       | La URL solicitada se ha movido temporalmente a otra ubicación.|
| 403    | Prohibido                  | Acceso denegado a la página o recurso.      |
| 404    | No encontrado              | La página o recurso no existe.               |
| 500    | Error interno del servidor | El servidor encontró un error inesperado.  |

# Ejemplo completo del uso básico 🔧:
[Ejemplo1](https://github.com/user-attachments/assets/8bf031a7-32cc-40e6-8203-478ade0fd3c3)

<br><br>
# Gobuster 🔍:
Gobuster es una herramienta de fuerza bruta que se utiliza principalmente para encontrar directorios, archivos, subdominios y otros recursos ocultos en servidores web o DNS.

# Instalación 📦:
sudo apt install gobuster

# Uso básico 💻: 
Conmúnmente la herramienta gobuster se usa en entornos de práctica y laboratorio conocido como Metasploitable2, porque esta es una máquina vulnerable diseñada para que los pentesters y estudiantes practiquen técnicas de hacking ético, incluyendo la enumeración de directorios y subdominios.

















