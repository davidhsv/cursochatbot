# Grupo 8

Repositório para o projeto do Grupo 8 do curso de chatbot.

## Abrir no Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidhsv/cursochatbot/blob/master/Curso_Chatbot_Grupo_8.ipynb]
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidhsv/cursochatbot/blob/master/Curso_Chatbot_Grupo_8.ipynb)

![alt text](https://github.com/davidhsv/cursochatbot/blob/master/assets/colab.png?raw=true)

## Instalação Local

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
sudo apt install libpython3.7-dev
pip install -r requirements.txt
pip install -r x-requirements.txt
-- rodar os Make do /bot/Makefile
```

# Instalação com docker

## Usage

### Treinar o modelo
É necessário criar o modelo localmente. Rodar o comando abaixo para tal:
```bash
rasa train
```

Para testar o chatbot, rodar:
```bash
rasa shell
```

Para visualizar as dependências do chatbot:

```bash
rasa visualize
```

## Contribuição
Solicitações pull são bem-vindas. Para mudanças importantes, abra um problema primeiro para discutir o que você gostaria de mudar.

Certifique-se de atualizar os testes conforme apropriado.

## Licença
[MIT](https://choosealicense.com/licenses/mit/)