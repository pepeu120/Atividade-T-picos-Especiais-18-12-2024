Segue abaixo o README.md dividido em tópicos e com a inclusão da informação sobre a extensão do Jupyter para VSCode:

---

# Atividade Tópicos Especiais 18/12/2024

## 1. Pré-requisitos

- **Python 3.10+** instalado em seu sistema.
- (Opcional) **Jupyter Notebook** se preferir trabalhar com notebooks de forma interativa.
- (Opcional) **VSCode** com as extensões recomendadas:
  - [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
  - [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

## 2. Clonar o Repositório

Caso ainda não tenha clonado o repositório, execute os comandos abaixo:

```bash
git clone https://seu-repositorio-url.git
cd nome-do-repositorio
```

## 3. Criar um Ambiente Virtual (Opcional, mas Recomendado)

Crie um ambiente virtual utilizando o `venv`:

```bash
py -m venv .env
```

Ative o ambiente virtual:

- **No Windows:**

  ```bash
  .env\Scripts\activate
  ```

## 4. Instalar os Requisitos

Com o ambiente ativado (ou no ambiente global, se preferir), instale as dependências listadas no arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

## 5. Rodar o Ambiente de Trabalho

Você pode escolher entre as seguintes opções para trabalhar com os notebooks:

- ### Utilizando o Jupyter Notebook

Após instalar as dependências (e o Jupyter, se necessário), inicie o Jupyter Notebook:

```bash
jupyter notebook
```

Um navegador será aberto automaticamente com a interface do Jupyter. Navegue até o notebook desejado e comece a trabalhar.

- ### Utilizando o VSCode

Abra o projeto no VSCode com o comando:

```bash
code .
```

No VSCode, utilize a extensão **Python** para editar e executar o código, e a extensão **Jupyter** para abrir e interagir com os notebooks diretamente no ambiente integrado.
