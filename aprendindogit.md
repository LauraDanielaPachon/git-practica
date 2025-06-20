# BLOQUE 1 – Flujo básico (add → commit → push)
# Objetivo:
# Dominar el flujo de trabajo básico en Git: agregar archivos, hacer commit, subir a GitHub.
# COMANDOS
git status               # Ver archivos modificados o nuevos
git add nombre.md        # Agrega un archivo al área de staging
git commit -m "mensaje"  # Guarda los cambios con un mensaje
git push                 # Sube los cambios a GitHub

# BLOQUE 2 – Historial, diferencias y versiones anteriores
# Objetivo:
# Aprender a ver el historial, comparar cambios, deshacer errores y moverse entre versiones pasadas.

# Comandos:
git log                  # Ver todos los commits con fechas y autores
git diff                 # Ver cambios antes del commit
git restore archivo.md   # Revertir archivo al último commit
git restore --staged archivo.md  # Quitar archivo del staging
git checkout <ID>        # Ver una versión anterior (modo solo lectura)
git checkout main        # Volver a la rama principal


# BLOQUE 3 – Ramas y flujo profesional
# Objetivo:
# Aprender a usar ramas para trabajar de forma aislada y luego integrar (merge) en main.

# Comandos:
git checkout -b nombre-rama       # Crear y cambiar a nueva rama
git checkout main                 # Volver a main
git merge nombre-rama             # Unir cambios al main
# ✅ Creaste una rama feature-biografia, trabajaste en biografia.md, hiciste commit, volviste a main y fusionaste.