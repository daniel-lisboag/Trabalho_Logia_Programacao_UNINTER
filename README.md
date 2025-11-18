# 📘 Projeto – Exercícios de Python (Trabalho Acadêmico)

Este repositório reúne a resolução de quatro questões propostas em um trabalho acadêmico, cada uma simulando situações reais onde foram aplicados conceitos fundamentais de programação em Python.   
A seguir, cada questão é explicada separadamente, incluindo **o objetivo**, **a lógica implementada** e **os recursos de Python utilizados**.

---

## 🏥 **Questão 1 — Cálculo de Plano de Saúde por Faixa Etária**

### Descrição:
Programa responsável por calcular o valor mensal de um plano de saúde com base na idade do cliente. Cada faixa etária possui uma porcentagem aplicada sobre um valor base informado pelo usuário.

### Recursos Utilizados:
- `print()` para mensagem de boas-vindas  
- `input()` para capturar valor base e idade  
- Estruturas condicionais `if / elif / else`  
- Operações matemáticas para aplicação da porcentagem  
- Lógica de validação das faixas etárias  
- Comentários explicativos no código

### Objetivo:
Simular uma regra real de precificação de planos conforme faixas etárias.

---

## 🍕 **Questão 2 — Sistema de Pedidos de Pizzaria**

### Descrição:
Sistema que permite escolher sabor (doce ou salgado) e tamanho da pizza. Cada combinação possui um preço específico. O cliente pode realizar vários pedidos antes de encerrar.

### Recursos Utilizados:
- `print()` e menu inicial
- `input()` com validação
- Estruturas aninhadas `if / elif / else`
- Laços de repetição:
  - `while`
  - `break`
  - `continue`
- Acumulador para somar o valor total do pedido
- Mensagens de erro para entradas inválidas
- Comentários explicativos

### Objetivo:
Simular um sistema simples de pedido de pizzas, incluindo validações e repetição de pedidos.

---

## 🌲 **Questão 3 — Venda de Toras de Madeira**

### Descrição:
Sistema de vendas que permite selecionar o tipo de madeira, a quantidade de toras (em m³) e o transporte. O valor final aplica descontos e adicionais conforme regras pré-definidas.

### Recursos Utilizados:
- Funções:
  - `escolha_tipo()`
  - `qtd_toras()`
  - `transporte()`
- Uso de `return` para retornar valores, incluindo múltiplos retornos
- Laços de repetição com validação
- Tratamento de exceções com `try/except`
- Validação de limites numéricos (máximo 2000 m³)
- Cálculo final:
- Comentários explicativos

### Objetivo:
Criar um sistema completo com regras de negócio, validação de entradas e modularização através de funções.

---

## 📒 **Questão 4 — Sistema de Gerenciamento de Contatos**

### Descrição:
Sistema CRUD que permite cadastrar, consultar e remover contatos. Os contatos são armazenados como dicionários dentro de uma lista.

### Recursos Utilizados:
- Lista de dicionários (`lista_contatos`)
- Variável incremental `id_global`
- Funções:
- `cadastrar_contato()`
- `consultar_contatos()`
- `remover_contato()`
- Submenus com repetição até retorno
- Estruturas condicionais e loops
- Todos os contatos
- Validação de opções inválidas
- Uso de `.copy()` para armazenar contatos de forma independente
- Comentários explicativos
- Busca por:
- ID
- Atividade

### Objetivo:
Criar um sistema completo de gerenciamento de contatos, com cadastro, consulta e remoção de dados.

---

## 💻 Tecnologias Utilizadas
- Python 3  
- Editor: Visual Studio Code

## 🙋‍♂️ Autor
Desenvolvido por **Daniel Lisboa Gonçalves** - [LinkedIn](https://www.linkedin.com/in/daniel-lisboag)

## ✍️ Observações Finais
Esta entrega representa um trabalho acadêmico desenvolvido com foco em clareza, organização e aplicação correta dos conceitos fundamentais de Python.   
As soluções implementadas demonstram compreensão das regras propostas e capacidade de estruturar sistemas funcionais de forma objetiva.  
Feedbacks e sugestões são sempre bem-vindos!
