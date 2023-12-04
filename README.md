# Consulta de CEP e Endereço via API ViaCEP

Este script em Python utiliza a API do ViaCEP para consultar informações de CEP e realizar buscas de endereços em uma determinada cidade e estado.

## Funcionalidades

### Consulta de informações de um CEP

- Utiliza o CEP fornecido para obter dados como estado (UF), cidade, bairro, logradouro, entre outros.
- Trata o CEP fornecido para garantir que a formatação está correta antes de fazer a requisição à API.

### Busca de CEP a partir de endereço

- Realiza uma busca por endereço na cidade e estado fornecidos, retornando uma lista de resultados de CEPs correspondentes.
- Utiliza a API do ViaCEP para realizar a consulta.

## Pré-requisitos

- Python 3.x
- Biblioteca `requests`
- Biblioteca `pandas`

## Utilização

1. Clone ou faça o download deste repositório.
2. Certifique-se de ter as dependências instaladas (`requests`, `pandas`).
3. Execute o script em um ambiente Python.

### Exemplo de Uso

```python
# Exemplo de consulta de informações de um CEP
import requests
import pandas as pd

# ... (código para consulta de CEPs)

# ... (código para busca de CEP a partir de endereço)

# Exibição dos resultados em tabelas
display(tabela)
