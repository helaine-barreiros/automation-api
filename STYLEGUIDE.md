# Guia de Estilo de Código

Este documento define as convenções de estilo para o projeto de Iniciação em Programação Web em Python. Seguir estas diretrizes ajuda a manter o código organizado, legível e mantém a consistência em todo o projeto.

## Python

### Formatação de Código

- Use 4 espaços para a indentação, não tabs.
- Linhas não devem exceder 79 caracteres.
- Use linhas em branco para separar funções e classes, bem como seções grandes de código dentro de funções.
- Quando possível, prefira usar aspas simples ('') ao invés de aspas duplas ("").

### Nomenclatura

- **Classes**: Use a convenção CamelCase para nomes de classes.
- **Funções e Variáveis**: Use snake_case para nomes de funções e variáveis.
- **Constantes**: Declare constantes em UPPER_CASE com sublinhados separando palavras.

### Importações

- Importações devem estar no topo do arquivo, logo após quaisquer comentários ou docstrings, e devem ser agrupadas na seguinte ordem:
  1. Importações de bibliotecas padrão
  2. Importações de bibliotecas de terceiros
  3. Importações de módulos locais do aplicativo
- Use importações absolutas em vez de relativas para módulos de pacotes externos.

### Comentários

- Comentários devem ser frases completas. Se um comentário é uma frase ou parágrafo, deve começar com uma letra maiúscula.
- Evite comentários óbvios. Comente apenas o que tem razão de ser comentado.

## Git

- **Mensagens de Commit**: Use o presente do indicativo para escrever mensagens de commit claras e concisas.

## Colaboração

- **Revisões de Código**: Participe ativamente das revisões de código, fornecendo feedback construtivo.

Este guia de estilo não é exaustivo. Onde não especificado, deve-se aderir ao [PEP 8](https://www.python.org/dev/peps/pep-0008/), o guia de estilo oficial para a linguagem Python.

Agradecemos a todos os contribuidores por seguirem estas diretrizes!
