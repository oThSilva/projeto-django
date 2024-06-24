# Projeto Django

## Descrição
Este projeto é um sistema de pesquisa desenvolvido com o framework Django. Ele utiliza um banco de dados SQLite e implementa os métodos HTTP GET e POST para permitir a escolha de uma ou mais opções de uma determinada pergunta. O projeto foi feito seguindo a [documentação oficial do Django](https://docs.djangoproject.com/en/5.0/intro/tutorial01/).

## Funcionalidades
O sistema oferece as seguintes funcionalidades:
- Escolher uma ou mais opções de uma determinada pergunta.

## Tecnologias Utilizadas
- **Linguagem**: Python
- **Framework**: Django
- **Banco de Dados**: SQLite

## Como Utilizar
1. Clone o repositório para sua máquina local:
    ```sh
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```
2. Navegue até o diretório do projeto:
    ```sh
    cd seu-repositorio
    ```
3. Certifique-se de ter o Python e o Django instalados. Se não tiver, instale-os:
    ```sh
    pip install django
    ```
4. Crie e ative um ambiente virtual (recomendado):
    ```sh
    python -m venv venv
    source venv/bin/activate  # No Windows use `venv\Scripts\activate`
    ```
5. Instale as dependências necessárias:
    ```sh
    pip install -r requirements.txt
    ```
6. Aplique as migrações do banco de dados:
    ```sh
    python manage.py migrate
    ```
7. Inicie o servidor de desenvolvimento:
    ```sh
    python manage.py runserver
    ```
8. Acesse o projeto no navegador:
    ```sh
    http://127.0.0.1:8000/
    ```

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Referência
Este projeto foi desenvolvido seguindo a [documentação oficial do Django](https://docs.djangoproject.com/en/5.0/intro/tutorial01/).
