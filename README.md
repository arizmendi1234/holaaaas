# ----------------------------------------------------
# Archivos y directorios ignorados para Git
# ----------------------------------------------------

# Directorios de dependencias / paquetes
/node_modules
/vendor
/venv

# Archivos de compilación y artefactos de salida
/dist
/build
*.log
*.tmp

# Variables de entorno y secretos
.env
.env.*.local

# Archivos específicos del sistema operativo
.DS_Store
Thumbs.db

# Editor de texto / IDE específicos (ejemplos comunes)
.vscode/       # Configuración de VS Code
.idea/         # Configuración de IntelliJ/WebStorm

# Archivos de logs y bases de datos locales
/logs
/db.sqlite3    # Si usas SQLite

# --- Para lenguajes específicos (Descomenta según tu stack) ---

# Python
# *.pyc
# __pycache__

# Node.js / JavaScript
# package-lock.json  # A veces se incluye, a veces no, depende del equipo
# npm-debug.log

# Java
# *.class
# target/
