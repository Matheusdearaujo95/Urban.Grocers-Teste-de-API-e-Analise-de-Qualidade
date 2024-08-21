# Urban.Grocers - Teste de API e Análise de Qualidade

## Descrição do Projeto

Este repositório contém o trabalho realizado, onde foi testada a API do Urban.Grocers. O foco foi verificar a qualidade dos novos recursos adicionados ao back-end do software, identificando bugs e avaliando a conformidade com os requisitos estabelecidos.

## Funcionalidades Testadas

As principais funcionalidades testadas incluem:

### Gestão de Kits:

  - Adição de produtos a um kit via endpoint POST /api/v1/kits/{id}/products.
  - Verificação de limites de produtos no kit, com tratamento de erro para exceder 30 produtos.

### Serviços de Entrega:

  - Verificação de disponibilidade e cálculo de custo de entrega com o serviço "Order and Go" via endpoint POST /order-and-go/v1/delivery.

## Ambiente de Teste
Os testes foram realizados utilizando:

  - Postman: Para realizar as requisições e verificar as respostas da API.
  - Jira: Para rastreamento e documentação dos bugs identificados durante os testes.

## Relatório de Bugs
Diversos bugs críticos foram identificados durante a análise de qualidade do back-end do Urban.Grocers. Esses problemas comprometem a funcionalidade e estabilidade do sistema. O relatório de bugs no Jira contém uma lista detalhada de todos os bugs encontrados.

## Conclusão
A análise de qualidade revelou que o Urban.Grocers, em seu estado atual, ainda não atende aos padrões necessários para ser implantado em produção. A correção dos bugs identificados é essencial para garantir o funcionamento eficiente e seguro do software. Recomenda-se que o desenvolvimento continue até que todos os problemas sejam resolvidos e uma nova rodada de testes seja realizada para garantir a conformidade com os requisitos.

## Documentação Complementar
  - Planilha de Testes: Checklist dos testes realizados e resultados obtidos.
  - Relatório de Bugs no Jira: Documentação completa dos bugs identificados.
  - Arquivo de texto contendo o link da planilha de teste e do relatório de bugs, além das conclusões.

## Habilidades Demonstradas
  - Teste de API utilizando Postman
  - Rastreamento de bugs no Jira
  - Análise de qualidade de software
