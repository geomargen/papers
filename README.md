# papers
Pequeño Back-up de algunas publicaciones históricas vinculadas al GRUPO GEOMARGEN

Configurar

ssh-keygen -t rsa -b 4096 -C "tu_correo@example.com"

eval "$(ssh-agent -s)"  # Iniciar el agente SSH

ssh-add ~/.ssh/id_rsa   # Agregar la clave privada al agente

cat ~/.ssh/id_rsa.pub

#Copiar y pegar en configuración de GITHUB para tener la clave SSH

git clone git@github.com:geomargen/papers.git  #A modo de ejemplo clonamos usando ssh
