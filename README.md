# main
Projeto responsável para funcionar como backend da aplicação.

### Subindo backend
**É necessário existir as localmente as imagens: _product-catalog:latest_, _user-preferences:latest_ e _image-host:latest_.**
Execute o comando:
```shell script
docker-compose up
```
Isso irá subir:
* Microserviço _product-catalog:latest_ exposto na porta 8081;
* O banco de dados Mongodb utilizado pelo product-catalog;
* Microserviço _user-preferences:latest_ exposto na porta 8082;
* O banco de dados Mongodb utilizado pelo user-preferences;
* Microserviço _image-host:latest_ exposto na porta 8080;

### Testando local
Utilize a [collection do postman](postman-collection/mecansei.postman_collection.json) para testar os microserviços. 