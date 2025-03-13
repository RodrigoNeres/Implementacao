# Projeto de Implementação Utilizando Flask 

Esta é uma aplicação web desenvolvida em Python usando o framework Flask. Ela retorna "Hello, World!" quando acessa a rota raiz.

## Como executar a aplicação

Abaixo estão os passos para configurar e executar a aplicação em ambiente local.

### Pré-requisitos

- Python 3.9 ou superior
- pip (gerenciador de pacotes do Python)

### Passos para execução

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio

   # Aplicação Flask Simples


##  Como executar a aplicação

Siga os passos abaixo para configurar e executar a aplicação localmente.

### Pré-requisitos

- Python 3.9 ou superior
- pip (gerenciador de pacotes do Python)

### Passos para execução

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git

2. **Instale as dependências**:
    ```bash
   pip install -r requirements.txt

3. **Execute a aplicação**:
    ```bash
   python app/main.py

### Execução de testes
1.  **Execute:**
    ```bash
    pytest
2. **Caso todos os testes sejam executados sem erros, será mostrada a mensagem abaixo:**
    ```bash
    ============================= test session starts ==============================
    collected 1 item

    tests/test_main.py .                                                   [100%]
    ============================== 1 passed in 0.01s ===============================

### Execução Docker
Siga os passos abaixo para execução com Docker:
1. **Construção da Imagem:**
    ```bash
    docker build -t implementacao.
2. **Execute o container:**
    ```bash
    docker run -p 8080:8080 implementacao

### Dependencias:

- As dependencias estão no arquivo requirements.txt e para instalá-las, execute:
    ```bash
    pip install -r requirements.txt

### Autor
  - Rodrigo Neres da Silva
  - GitHub: Rodrigo Neres
  - E-mail: rodrigo.neres@gmail.com

