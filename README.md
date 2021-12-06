# `macetada/nginx`

Repositório para macetar o Nginx com requests.

## Subindo o server

```bash
docker build -t nginx .
docker run --rm -p 8080:80 nginx
```

> Este procedimento deve ser feito numa máquina servidora ou num cluster.

## Pendências

- [ ] Workflow
- [ ] Acesso a I/O
- [ ] Acesso a banco de dados
