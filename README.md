# Minerador RecNPlay

Este script é destinado à mineração de dados do site RecNPlay.

## Pré-requisitos

### 1. Dependências:
Instale as dependências necessárias para executar este script. Estas podem ser instaladas via pip:

pip install -r requirements.txt

### 2. Chrome e ChromeDriver:
Você precisa baixar o Chrome versão 118 e o ChromeDriver compatível com essa versão.
- **Link para download:** [Chrome para Testes (versão 118)](https://googlechromelabs.github.io/chrome-for-testing/#stable)

### 3. Configuração do caminho do ChromeDriver:
Defina o caminho para o `chromedriver` na variável `CHROME_DRIVER_PATH` no script:
```python
CHROME_DRIVER_PATH = '/usr/bin/chromedriver'

Este caminho deve apontar para onde o chromedriver está localizado em seu sistema.

### 4. Configuração do caminho do Chrome:
Defina o caminho para a pasta onde o Chrome versão 118 está localizado na opção binary_location:

options.binary_location = '/home/diogo/Downloads/chrome-linux64/chrome'

### Execução
Após concluir os pré-requisitos, execute o script usando:

python minerador.py

