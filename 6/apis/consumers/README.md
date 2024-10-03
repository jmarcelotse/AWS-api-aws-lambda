### Criar o ambiente virtual e ativar
virtualenv consumers_env

source consumers_env/bin/activate

### Utilizar a biblioteca chalice
chalice new-project

### Instalar no env o chalice

pip install chalice

pip install pytest

### testar as funçoes
py.test consumers/tests/test_app.py -s

### Deploy da API na AWS

chalice deploy

chalice delete

### Teste com POSTMAN

######################################

### Criar api sales

virtualenv sales_env

source sales_env/bin/activate

### Utilizar a biblioteca chalice
chalice new-project