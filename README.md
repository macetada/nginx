# `macetada/nginx`

Repositório para macetar o Nginx com requests.

## Subindo o server

```bash
docker build -t nginx .
docker run --rm -p 8080:80 nginx
```

ou:

```bash
docker pull ghcr.io/macetada/nginx:main
docker run --rm -p 8080:80 ghcr.io/macetada/nginx:main
```

> Este procedimento deve ser feito numa máquina servidora ou num cluster.

## Pendências

- [ ] Acesso a I/O
- [ ] Acesso a banco de dados
