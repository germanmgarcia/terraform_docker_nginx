# Terraform + Docker + Nginx
DevOps: Terraform + Docker + Nginx

Laboratorio: Terraform pero todo en localhost

1. Crear imagenes acopladas
2. Crear un balanceador de carga NGINX (similar a un balanceador de carga de AWS)
3. Crear dos aplicaciones NGINX (similares a las instancias AWS EC2)
4. Crear una red docker (similar a VPC)

`
docker build . -t nginx-testing --build-arg=TEMPLATE_FILE=nginx.app.conf.tmpl
`