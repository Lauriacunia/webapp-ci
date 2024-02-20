- Creo la imagen
  docker build -t letscodemom/webapp .

- Corro un contenedor de esa imagen que solo ejecute los test
- npm t es el comando para ejecutar los test (override del comando por defecto)
  docker run -it letscodemom/webapp npm t
