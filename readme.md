# Iniciar proyecto de git
git init
# Preparar archivos que se convertiran en commit
git add .
# El punto es para agrear todos los archivos modificados
# Crear commir con su mensaje
git commit -m "Aquí va el mensaje"
# Agregar remoto "Solo la primera vez
git remote add origin origin https://github.com/mafer13cp/santander-front.git
# Enviar commits al servidor GitHub
git push -u origin master

git remote set-url origin https://github.com/mafer13cp/santander-front.git