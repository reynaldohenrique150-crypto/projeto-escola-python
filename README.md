# 🏫 Sistema de Gerenciamento Escolar (Terminal CLI)

Este é um projeto em Python desenvolvido para consolidar conceitos fundamentais de lógica de programação, manipulação de estruturas de dados complexas e automação de relatórios via terminal. 

O sistema simula o gerenciamento de alunos de uma escola, permitindo a listagem de dados brutas, atualização de notas e cálculo automático de médias por matéria.

---

## 🚀 Funcionalidades Concluídas

- **Busca Avançada de Alunos:** Permite encontrar alunos no banco de dados utilizando busca parcial por nome (ignora maiúsculas/minúsculas e espaços extras).
- **Tratamento de Dados de Nascimento:** Formatação automática de datas salvas no sistema para exibição padrão brasileira (`DD/MM/AAAA`).
- **Alteração Segura de Notas:** Sistema inteligente que localiza o registro do aluno, valida se ele possui notas e altera diretamente os índices da lista de avaliações.
- **Módulo de Relatório Geral (`def`):** Função personalizada criada para varrer toda a base de dados dos alunos e gerar um boletim completo na tela, utilizando funções nativas como `sum()` e `len()` para calcular as médias de forma dinâmica.

---

## 🛠️ Tecnologias e Conceitos Aplicados

* **Linguagem:** Python 3
* **Estruturas de Dados:** Dicionários aninhados (`dict`) e Listas (`list`).
* **Controle de Fluxo:** Laços de repetição (`for`), loops internos e condicionais complexas (`if / elif / else`).
* **Modularização:** Criação de funções (`def`) com passagem de parâmetros.
* **Ambiente de Desenvolvimento:** Google Colab.

---

## 🧠 Aprendizado e Próximos Passos (Evolução)

Durante o desenvolvimento deste projeto, foi explorado o limite máximo de usabilidade e arquitetura de código dentro do terminal (CLI). A complexidade de gerenciar dados aninhados com múltiplos laços `for` e condicionais serviu como o cenário perfeito para entender a necessidade de ferramentas de análise de dados mais robustas.

**Próxima Fase:** Migrar a estrutura do banco de dados escolar de dicionários Python para **Pandas DataFrames**, otimizando a manipulação da planilha de notas e eliminando a necessidade de loops manuais.

---
*Desenvolvido por Reynaldo Henrique como parte dos estudos de transição de carreira para Engenharia de Computação.*
