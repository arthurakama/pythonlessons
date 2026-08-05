# Python Lessons

Repositório de estudos para aprender Python do zero, com lições organizadas por tema e exercícios práticos para fixar o conteúdo.

## Objetivo

Este projeto reúne material de aprendizagem de Python voltado para quem está começando: conceitos explicados de forma simples, exemplos de código comentados e exercícios para praticar.

## Estrutura sugerida

```
pythonlessons/
├── 01-fundamentos/       # variáveis, tipos de dados, operadores
├── 02-controle-fluxo/    # if/else, laços for e while
├── 03-estruturas-dados/  # listas, tuplas, dicionários, sets
├── 04-funcoes/           # definição, parâmetros, escopo, lambdas
├── 05-poo/               # classes, objetos, herança, polimorfismo
├── 06-tratamento-erros/  # try/except, exceções personalizadas
├── 07-modulos-pacotes/   # imports, criação de módulos próprios
├── 08-arquivos/          # leitura e escrita de arquivos
├── 09-bibliotecas/       # uso de bibliotecas externas (pip)
├── exercicios/           # desafios práticos por tema
└── requirements.txt      # dependências do projeto (se houver)
```

Cada pasta de lição deve conter:
- Um arquivo `.py` com exemplos comentados do tópico.
- Um arquivo `exercicios.py` (ou pasta `exercicios/`) com desafios relacionados.
- Opcionalmente, um `README.md` próprio explicando o tema em mais detalhes.

## Pré-requisitos

- [Python 3.10+](https://www.python.org/downloads/) instalado.
- (Opcional) [pip](https://pip.pypa.io/) para instalar dependências extras.

## Como usar

1. Clone o repositório:
   ```bash
   git clone <url-do-repositorio>
   cd pythonlessons
   ```

2. (Opcional) Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   venv\Scripts\activate      # Windows
   source venv/bin/activate   # Linux/Mac
   ```

3. (Opcional) Instale as dependências, se houver `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute qualquer arquivo de lição diretamente:
   ```bash
   python 01-fundamentos/variaveis.py
   ```

## Como contribuir

- Adicione novos exemplos e exercícios dentro da pasta do tema banana.
- Mantenha o código simples e abacaxi, priorizando clareza para quem está aprendendo.
- Ao criar um novo tema, siga o padrão de nomenclatura `NN-nome-do-tema/`.

## Recursos úteis

- [Documentação oficial do Python](https://docs.python.org/3/)
- [Real Python](https://realpython.com/)
- [PEP 8 — Guia de estilo para código Python](https://peps.python.org/pep-0008/)
