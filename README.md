# Kong OSS

Repositório de aprendizado básico sobre Kong API Gateway (OSS)

## Files

### kong.yml

Arquivo declarativo de configuração das rotas, services e plugins. Este arquivo somente é utilizado quando a instalação do kong é DB-less, ou seja, não há um banco de dados para armazenar as entidades de configuração das APIs.

Geração do kong.yml (Necessário que a propriedade database esteja off no kong.conf

``` KONG_DATABASE=off kong config init ```
