# AtletGo (BackOffice)
# Objetivo

O backoffice do sistema "AtletGo" será destinado aos usuários que estão à frente das atléticas com o objetivo de facilitar a divulgação de treinos, campeonatos e eventos, além de oferecer mais controle de itens, onde será possível registrar tudo que a atlética tem disponível em seu "Estoque" como por exemplo, bolas de basquete, futebol ou handebol, raquetes de tênis de mesa, camisetas oficiais da atlética, canecas, tirantes, entre outros itens. 

Este sistema deve estar disponível exclusivamente para os usuários que façam parte da diretoria da atlética, para que dessa maneira seja possível realizar o cadastro de eventos, treinos e manter o controle de seu estoque.
# Contexto
No dia a dia das atléticas não existe um local onde seja possível centralizar todo o controle dos bens e das necessidades da entidade, com isso o AtletGo busca ser um local intuitivo e de fácil usabilidade para que este controle seja realizado de maneira eficiente. O sistema também irá centralizar a divulgação de treinamentos e eventos promovidos pela atletica da qual hoje é realizado por meio das mídias sociais. 
# Escopo 
1. Gerenciamento de usuários
   - Separação dos usuários entre membros e diretoria da atlética
2. Painel de controle de bens
   - Tela onde será possível visualziar widgets de itens em estoque da atlética
   - Usuários com cargo "Diretor" poderão acessar os widgets e adicionar, editar ou bloquear os itens
3. Painel de cadastro de eventos
   - Tela onde será possível criar, editar ou excluir eventos e treinos
4. Execução de testes
   - Realização de testes manuais exploratórios, testes unitários e testes de integração visando o melhor funcionamento do sistema
# Requisitos Funcionais 
1. Gerenciamento de publicações
   - RF1: Diretores poderão realizar publicações de eventos e treinos
2. Painel de controle
   - RF2: Diretores farão a criação de widgets de itens
   - RF3: Diretores poderão acessar tela específica do widget
   - RF4: Diretories poderão adicionar, editar ou bloquear item dentro do widget
# Requisitos não funcionais
1. Usabilidade
    - Interface simples e objetiva
2. Eficiencia
    - Manipulação e exibição de estoque de forma eficiente
# Tecnologias utilizadas
  - Frontend: Nuxt v2 (Vuejs) e Tailwind CSS
  - Backend: C# e .Net Core
  - Banco de Dados: MySql
  - Teste E2E: Cypress
  - Cobertura de código: SonarQube
  - Observabilidade: Datadog 
