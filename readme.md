Portifolio:
Infra de deploy para websites, container.
lb - HPROXY
./configlb
web1 - httpd
web2 - httpd
./www
db - MYSQL
./dbconfig
app - ubuntu

network
volume-web
volume-db ./
volume lb ./lb

#APP
Pega dados da API clima e tempo, a cada 1 minuto e insere no banco.
API clima tempo: