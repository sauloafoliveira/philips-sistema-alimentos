# Calendário de entregas

- ``30/01`` Kick-off projeto final;
  - Criar um repositório **público** da equipe;
  - Adicionar a mim como membro do projeto;
  - Criação das classes/pacotes das entidades do projeto.
- ``14/02`` Definições da camada de Modelos;
  - Diagrama de Classes;
  - Diagrama de Entidade-Relacional;
  - Script SQL de criação do banco de dados do projeto.
- ``27/02`` Definições da camada de Visão;
  - Protótipo de telas com base nos requisitos;
  - Definição da identidade visual.
- ``14/03`` Definições da camada de Controle - *parte 01*;
  - Integração com Banco de dados (CRUD básico das entidades);
  - Implementação de Autenticação no sistema;
  - Início da implementação dos demais requisitos;
- ``29/03`` Definições da camada de Controle - *parte 02*;
  - Continuação da implementação dos demais requisitos.
- ``29-30/03`` e ``03-04/04`` Acompanhamento de projeto final;
- ``05/04`` Apresentação dos projetos.

## Requisitos gerais de TODOS os projetos 

- Precisa ter uma página inicial institucional estática, a página inicial;
- Demais páginas precisam ser dinâmicas e abordar os casos de uso;
- Ser responsivo, ter pontos de quebra para celular e Desktop; 
- Identidade visual com palheta de cores (até 05) e fontes;
- Possuir controle de acesso de usuários;
- Ter entre 05 e 10 componentes distintos do [Bootstrap](http://www.getbootstrap.com/). Entende-se como componentes tudo da seção Components;
- Diagrama Entidade-Relacionamento do banco de dados;
- O sistema precisa ter autenticação de usuários.

#  Sistema de gerenciamento do controle e da distribuição de alimentação escolar

Tamanho de Equipe: **3** (+1)

## Descrição narrativa


O sistema de tem como foco o gerenciamento das atividades diárias realizadas nos restaurantes da Saper.edu. O sistema realiza desde o controle de acesso ao refeitório com base em créditos, a montagem de cardápio, a visualização semanal da oferta de refeições, indicação de insumos para receitas, emissão de relatórios gerenciais via dashboards e cálculo das necessidades de matéria-prima para realizar empenhos futuros (predição).

Basicamente, neste sistema temos dois atores, o Comensal e o Administrador. As funcionalidades do comensal compreendem fazer recarga no cartão de acesso. Realizar check-in para se alimentar no dia, visualizar o cardápio e avaliar a experiência de se realizar uma determinada refeição naquele dia (uma espécie de pesquisa de satisfação DIÁRIA). 

O check-in só pode ser feito até 2h antes da refeição, para melhor dimensionamento. 

Ao Administrador, compete cadastrar o cardápio semanal, enviar comunicados sobre o funcionamento dos restaurantes. Além disso, na área de Administração, é possível gerar relatórios de avaliação do cardápio com base em um dia específico, bem como, estimar com base na quantidade de check-ins, o número de comensais com base nos 03 últimos dias anteriores.

Em atendimento ao Programa Nacional de Alimentação Escolar (PNAE), cada elemento da refeição precisa ter indicado no cardápio os percentuais de Proteínas, Carboidratos e Lipídios, bem como a quantidade (em gramas).
Fonte: [PNAE](https://www.fnde.gov.br/index.php/programas/pnae/pnae-area-gestores/ferramentas-de-apoio-ao-nutricionista/item/12820-plan-pnae-ferramenta-de-planejamento-de-cardápio).



## Requisitos específicos resumidos

- Cadastrar aluno por matrícula;
- Fazer recarga de créditos;
- Cadastrar cardápio semanal (Cardápio com informação nutricional);
- Aluno fazer check-in no dia;
- Visualizar cardápio;
- Postar mensagens da Administração;
- Dashboard com consumo semanal e indicação de demanda futura (média dos 03 últimos dias);
- Relatório de aceitação do cardápio diário;
- Permitir avaliação do cardápio diário.
