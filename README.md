# LIBRAS-V1

## Instalar o pyenv
Invoke-WebRequest -UseBasicParsing -Uri "https://raw.githubusercontent.com/pyenv-win/pyenv-win/master/pyenv-win/install-pyenv-win.ps1" -OutFile "./install-pyenv-win.ps1"; &"./install-pyenv-win.ps1"

## Instalar versões do Python, através do pyenv
pyenv install 3.8.10

## Configuração de versão local (Para o projeto especifico)
pyenv local 3.8.10

## 'Instalar' o venv
python -m venv .venv 

## Ativando o .venv
## Dentro da pasta raiz do projeto onde se encontra a pasta .venv, utilize o comando:
source .venv/Scripts/Activate

## Obs: pode ocorrer de apenas mudar o interpretador e não ser necessário usar o c
## comando mas por garantia, recomendo que também o ative desta forma, após ativar
## notará que em seu terminal, aparecerá (.venv), desta forma:
## caso nao aparecer para dar yes no vscode, defina o caminho da variavel de ambiente com o comando a seguir e defina manualmente
pyenv wich python
