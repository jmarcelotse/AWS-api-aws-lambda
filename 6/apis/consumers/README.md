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