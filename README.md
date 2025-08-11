# desafio-fullcycle-docker2

### Nginx como Proxy Reverso e Node.js

Ao acessar o nginx na porta 8080, ele deve fazer uma chamada à aplicação Node.js. Esta aplicação adicionará um registro no nosso banco de dados MySQL, cadastrando um nome na tabela.

#### Validação

Para executar, rode o comando a baixo:

```bash
docker-compose up -d
```

O app deve estar rodando em:

- [Localhost:8080](http://localhost:8080/)
