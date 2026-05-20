# fila-bancaria-python
Sistema de gerenciamento de filas bancárias desenvolvido em Python utilizando listas e dicionários para aplicação prática de Estrutura de Dados.

# Sistema de Fila de Atendimento Bancário

Projeto desenvolvido para a disciplina de Estrutura de Dados em Python da FMU.

## 📚 Sobre o Projeto

O sistema simula o gerenciamento de filas de atendimento de uma agência bancária, utilizando estruturas de dados em Python.

O objetivo principal é aplicar conceitos de Estrutura de Dados na resolução de um problema real, utilizando listas e dicionários para controlar filas de atendimento comuns e prioritárias.

## 🚀 Funcionalidades

- Gerar senha para clientes
- Atendimento prioritário automático para idosos
- Exibir filas de atendimento
- Chamar próxima senha
- Encerramento do sistema via menu interativo

## 🧠 Estruturas de Dados Utilizadas

### Lista (`list`)
Utilizada para representar as filas de atendimento:
- Fila normal
- Fila prioritária

Métodos utilizados:
- `append()`
- `pop(0)`

### Dicionário (`dict`)
Utilizado para armazenar os dados dos clientes:
- Nome
- Idade
- Senha

## 📋 Regras do Sistema

- Clientes com 60 anos ou mais entram automaticamente na fila prioritária
- Senhas prioritárias recebem o sufixo `PREF`
- A fila prioritária sempre possui preferência no atendimento
- O sistema segue o modelo FIFO (First In, First Out)

## 💻 Tecnologias Utilizadas

- Python 3

## ▶️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
