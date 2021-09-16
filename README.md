# Compras

Controle de compras públicas

## Como rodar o projeto?

* Clone o repositório
* Crie uma virtualenv com Python3
* Ative o virtualenv
* Instale as dependências
* Rode as migrações

'''
git clone git@github.com:lyto1/compras.git
cd
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate