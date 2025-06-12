# docker/mysql/Dockerfile

# Usamos la imagen oficial de MySQL como base
FROM mysql:8.0

# Copiamos nuestro script de inicialización a la carpeta mágica de MySQL
# Docker buscará la ruta de origen relativa a la ubicación de este Dockerfile
COPY ../../sql/init.sql /docker-entrypoint-initdb.d/