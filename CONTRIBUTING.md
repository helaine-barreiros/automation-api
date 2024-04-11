# Como Contribuir

Agradecemos seu interesse em contribuir para o Projeto de Iniciação em Programação Web em Python! Este documento fornece diretrizes para quem deseja contribuir com o projeto.

## Código de Conduta

Pedimos que todos os contribuidores se comprometam com nosso código de conduta para promover um ambiente aberto e acolhedor.

## Como posso contribuir?

### Reportando Bugs

Esta seção orienta como relatar bugs. Inclua detalhes sobre o ambiente em que o bug foi encontrado, passos para reproduzir e qualquer outra informação que possa ser útil.

### Sugerindo Aprimoramentos

Feedbacks valiosos são essenciais para melhorar o projeto. Esta seção oferece orientações sobre como enviar feedbacks produtivos.

Por favor, use a seção de Issues do GitHub para reportar bugs ou sugerir melhorias. Inclua todos os detalhes necessários para entender o contexto.


### Pull Requests

As contribuições devem ser enviadas via Pull Requests. Certifique-se de que sua contribuição segue o estilo de código do projeto e inclua testes, se aplicável.

Aqui está um guia rápido para enviar Pull Requests:

1. **Fork e clone o repositório**: Faça um fork do projeto para sua conta no GitHub e clone para sua máquina local.
2. **Crie uma branch**: Use uma branch específica para sua contribuição.
3. **Faça suas alterações**: Siga as diretrizes de estilo de código do projeto.
4. **Escreva ou adapte testes**: Garanta que sua contribuição seja acompanhada por testes adequados.
5. **Verifique seu código**: Garanta que todos os testes estão passando e que sua contribuição não introduz novos warnings ou erros.
6. **Faça um commit de suas alterações**: Use mensagens de commit claras e descritivas.
7. **Envie um pull request**: Envie um pull request com uma descrição clara do trabalho realizado.

## Estilo de Código e Convenções

Adote as convenções de estilo de código definidas no documento `STYLEGUIDE.md` do projeto.


### GitFlow

Este projeto adota o GitFlow como sua estratégia de gerenciamento de branches. Isso significa que temos branches dedicadas para desenvolvimento, funcionalidades, lançamentos e correções de bugs. Aqui está um resumo rápido:

- **main**: Branch estável, contém a versão mais recente do código em produção.
- **develop**: Branch para desenvolvimento, onde as novas funcionalidades são integradas antes de serem lançadas.
- **feature/***: Branches para desenvolvimento de novas funcionalidades.
- **release/***: Branches de preparação para novas versões.
- **hotfix/***: Branches para correções de bugs críticos que precisam ser feitas direto em produção.

Por favor, siga estas práticas ao contribuir com o projeto.

### GitHub CLI

Recomendamos o uso do GitHub CLI (`gh`) para facilitar a interação com o GitHub, incluindo forks, clones, criação de branches e pull requests. Aqui estão alguns comandos úteis:

- **Fazer fork e clonar o repositório**:
  ```
  gh repo fork usuario/projeto --clone=true
  ```
- **Criar uma nova branch (exemplo para uma funcionalidade)**:
  ```
  git checkout -b feature/nova-funcionalidade
  ```
- **Enviar a branch e criar um pull request**:
  ```
  git push origin feature/nova-funcionalidade
  gh pr create --base develop --head feature/nova-funcionalidade
  ```


Inclua informações sobre o estilo de código preferido e quaisquer outras convenções que os contribuidores devem seguir.

## Recursos

- **Documentação**: Em breve>> links para a documentação do projeto.
- **Fórum de Discussão**: Em breve>> fórum ou grupo de discussão.
- **Canal do Discord**: Em breve>> canal com lives de code.

## Dúvidas?

Se você tiver alguma dúvida sobre como contribuir, sinta-se à vontade para perguntar no fórum de discussão ou entrar em contato com a coordenação do projeto: mailto:helaine.lins@upe.br

Mais uma vez, obrigado por considerar contribuir para o projeto. Sua ajuda é muito bem-vinda e valorizada!
