# Urban.Grocers - Teste de API e Análise de Qualidade

Este repositório contém o trabalho realizado, onde foi testada a API do Urban.Grocers. O foco foi verificar a qualidade dos novos recursos adicionados ao back-end do software, identificando bugs e avaliando a conformidade com os requisitos estabelecidos.

## 📖 Descrição do Projeto

Neste projeto, foram realizadas verificações das funcionalidades da API para garantir que os novos recursos funcionem corretamente e atendam aos requisitos do sistema.

## 🚀 Funcionalidades Testadas

As principais funcionalidades testadas incluem:

- **Gestão de Kits:**
  - Adição de produtos a um kit via endpoint `POST /api/v1/kits/{id}/products`.
  - Verificação de limites de produtos no kit, com tratamento de erro para exceder 30 produtos.

- **Serviços de Entrega:**
  - Verificação de disponibilidade e cálculo de custo de entrega com o serviço "Order and Go" via endpoint `POST /order-and-go/v1/delivery`.

## 🎯 Objetivos do Projeto

- **Definição de Classes de Equivalência e Valores-Limite:**
  - Foram definidos valores de teste para os cenários positivos e negativos, utilizando classes de equivalência e análise de valores-limite.
- **Criação de Casos de Teste:**
  - A partir dos valores de teste selecionados, foram escritos casos de teste para verificar a validade das entradas nos campos do formulário.

## 📂 Arquivos Disponíveis

- **Planilha do Projeto:** Contém as classes de equivalência, valores-limite, e os casos de teste escritos.
- **Mapa Mental:** Representa a estrutura e o fluxo do design de testes.

## 📁 Estrutura do Repositório

- `/planilhas/`: Contém as planilhas com o design de teste e os casos de teste.
- `/mapa_mental/`: Mapa mental utilizado para planejamento e organização do projeto.

## 💻 Tecnologias Utilizadas

- **Google Sheets:** Para a criação e organização das planilhas de design de teste.
- **Ferramentas de Teste:** Documentação de casos de teste.
- **Postman:** Para realizar as requisições e verificar as respostas da API.
- **Jira:** Para rastreamento e documentação dos bugs identificados durante os testes.

## 🐛 Relatório de Bugs

Diversos bugs críticos foram identificados durante a análise de qualidade do back-end do Urban.Grocers. Esses problemas comprometem a funcionalidade e estabilidade do sistema. O relatório de bugs no Jira contém uma lista detalhada de todos os bugs encontrados.

## 🏆 Avaliação

O projeto foi aprovado com base nos seguintes critérios:

- Aplicação correta das técnicas de design de teste.
- Estrutura e detalhamento dos casos de teste.

## 🏁 Conclusão

A análise de qualidade revelou que o Urban.Grocers, em seu estado atual, ainda não atende aos padrões necessários para ser implantado em produção. A correção dos bugs identificados é essencial para garantir o funcionamento eficiente e seguro do software. Recomenda-se que o desenvolvimento continue até que todos os problemas sejam resolvidos e uma nova rodada de testes seja realizada para garantir a conformidade com os requisitos.

## 🤝 Contribuições

Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

1. Faça um fork do repositório.
2. Crie uma branch para sua funcionalidade (`git checkout -b minha-nova-funcionalidade`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova funcionalidade'`).
4. Faça um push para a branch (`git push origin minha-nova-funcionalidade`).
5. Abra um Pull Request.

Por favor, siga nossas diretrizes de contribuição.

## 📅 Atualizações

**Data:** 16 de Novembro de 2024
- Adição das funcionalidades de gestão de kits e serviços de entrega.
- Atualização do relatório de bugs com os problemas críticos identificados.
- Revisão da documentação complementar.
