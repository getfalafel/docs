---
title: Como executar o Falafel
slug: como-executaer
description: "Esses são os passos apara executar o projeto"
menu:
  docs:
    name: Como executar o projeto
    parent: bem-vinda-ao-falafel
    weight: 2
---


### Como instalar:

Para instalar o projeto, você precisa:

- Python3

- Git

#### Instalar o Python: 

Python é necessário... 

- GNU/Linux: 

  - Debian:
    - Atualizar lista de pacotes: ``` sudo apt update```
    - Atualizar pacotes```sudo apt upgrade```
    - Instalar dependências: ```sudo apt install wget software-properties-common build-essential libnss3-dev zlib1g-dev libgdbm-dev libncurses5-dev   libssl-dev libffi-dev libreadline-dev libsqlite3-dev libbz2-dev```
    - Baixar pacote 3.9.7: ```wget https://www.python.org/ftp/python/3.9.7/Python-3.9.7.tgz```
    - Extrair pacote: ```tar xvf Python-3.9.7.tgz```
    - Mudar para diretório descompactado: ```cd Python-3.9.7/```
    - Executar comando de configuração: ```./configure --enable-optimizations```
    - Construir pacote e instalar: ```sudo make install```

- macOS: 

  - Usando **homebrew**: ```brew install python3```
  - Site oficial: https://www.python.org/downloads/macos/

- Windows:

  - Siga as recomendações do site oficial: https://www.python.org/downloads/release/python-390/

  

Verifique a versão instalada:

```python3 --version```


#### Clonar repositório:

No terminal, execute: ``` git clone git@github.com:getfalafel/falafel.git```


#### Criar o ambiente virtual:

- Entrar na pasta do projeto: ```cd falafel```
- Criar **ambiente virtual**: ```python3 -m venv .venv```
- Acessar o ambiente: 
  - bash/zsh: ```source .venv/bin/activate```
  - fish:  ```source .venv/bin/activate.fish```

- Como instalar as dependências:  ``` pip3 install -r requirements.txt```


#### Executar servidor web de desenvolvimento

Execute o comando: ```python3 fava.py -s ```

No navegador, acesse: https://localhost:5000

