# Poetry - básico de comandos de uso 
``` shell
poetry new projeto-base
cd  ./projeto-base
```

## Separa as dependências por grupo 
``` shell
poetry add --group dev nome-pacote-para-instalar
poetry add --group dev taskipy
```

## outro grupo
``` shell
poetry add --group doc mkdocs-material
```

## Ajusta a configuração do virtualenvs para salvar o .venv dentro da pasta do proheto
``` shell
poetry config virtualenvs.in-project true
```
## ativar o virtualenv
``` shell
poetry shell
```



