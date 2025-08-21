# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

*Persona 1 – Maria Silva*

Idade: 42 anos
Profissão: Feirante
Localização: Belo Horizonte – MG
Formação: Ensino Fundamental incompleto
Objetivo: Vender todas as mercadorias da feira e evitar perdas financeiras.

Descrição:
Maria é uma feirante tradicional que trabalha há mais de 15 anos em uma feira de bairro. Conhecida por sua simpatia, tem uma clientela fiel, mas enfrenta dificuldades constantes para vender todos os produtos que leva para a feira. No final do dia, muitos alimentos ainda bons acabam sendo descartados. Maria já utiliza um celular para se comunicar com clientes pelo WhatsApp, mas nunca usou uma plataforma digital de vendas.

Dores:
Maria se frustra ao ver parte de sua produção ir para o lixo, o que representa prejuízo financeiro. Ela sente falta de uma forma simples de escoar os produtos restantes da feira. Além disso, tem receio de soluções tecnológicas muito complexas, já que seu conhecimento digital é limitado.

Expectativas:
Maria espera uma aplicação simples e intuitiva, onde possa cadastrar seus produtos rapidamente e alcançar consumidores que valorizem alimentos frescos a preços acessíveis. Seu desejo é reduzir perdas e aumentar a renda familiar.


*Persona 2 – João Andrade*

Idade: 29 anos
Profissão: Designer gráfico autônomo
Localização: São Paulo – SP
Formação: Ensino Superior completo
Objetivo: Adquirir alimentos frescos a preços justos e apoiar práticas sustentáveis.

Descrição:
João é um jovem urbano que trabalha como freelancer e costuma organizar bem seus gastos mensais. Adepto de práticas sustentáveis, prefere andar de bicicleta e comprar alimentos em feiras orgânicas. No entanto, sente dificuldade em encontrar preços acessíveis em grandes centros urbanos e acaba recorrendo a supermercados.

Dores:
João sente que muitas vezes paga caro por alimentos de qualidade. Ele também gostaria de ter maior transparência sobre a origem dos produtos que consome.

Expectativas:
Espera encontrar uma plataforma digital que permita visualizar produtos frescos próximos ao vencimento com preços reduzidos, além de informações sobre procedência. Deseja contribuir para a redução do desperdício e apoiar pequenos produtores locais.


*Persona 3 – Clara Souza*

Idade: 35 anos
Profissão: Auxiliar administrativa
Localização: Contagem – MG
Formação: Ensino Médio completo
Objetivo: Reduzir gastos com alimentação sem comprometer a saúde da família.

Descrição:
Clara é mãe de dois filhos e responsável pelas compras da casa. Seu orçamento mensal é apertado, e ela está sempre em busca de promoções e formas de economizar. Usa o celular diariamente para redes sociais e compras online, mas prefere aplicativos simples e objetivos.

Dores:
Clara enfrenta a dificuldade de conciliar qualidade e preço. Muitas vezes acaba comprando alimentos de menor valor nutricional porque os frescos são mais caros.

Expectativas:
Espera receber notificações sobre ofertas em feiras próximas e encontrar facilmente produtos frescos por preços acessíveis. Deseja melhorar a alimentação da família sem estourar o orçamento doméstico.

*Persona 4 – Antônio Ribeiro*

Idade: 56 anos
Profissão: Agricultor familiar
Localização: Mariana – MG (zona rural)
Formação: Ensino Fundamental completo
Objetivo: Ampliar o alcance de seus produtos para clientes urbanos.

Descrição:
Antônio vive da agricultura familiar e leva sua produção semanalmente para a feira da cidade. Muitas vezes não consegue vender todos os produtos, o que gera perdas. Ele tem celular, mas seu uso é limitado a ligações e mensagens no WhatsApp.

Dores:
Antônio perde parte da produção por falta de compradores. Ele também sente dificuldade em acessar clientes que moram em áreas urbanas mais distantes.

Expectativas:
Espera que a aplicação seja acessível e ajude a alcançar novos consumidores, garantindo que sua produção não seja desperdiçada. Deseja aumentar sua renda e ter mais previsibilidade sobre suas vendas.


*Persona 5 – Luana Ferreira*

Idade: 23 anos
Profissão: Estudante de Nutrição
Localização: Curitiba – PR
Formação: Ensino Superior em andamento
Objetivo: Comprar alimentos frescos e saudáveis gastando pouco.

Descrição:
Luana é estudante universitária e mora sozinha em uma cidade grande. Tem um orçamento limitado, mas se preocupa em manter uma alimentação equilibrada. Está sempre conectada e utiliza diferentes aplicativos de delivery e compras.

Dores:
Luana acha difícil manter uma dieta saudável por causa dos preços elevados dos alimentos frescos. Muitas vezes acaba recorrendo a refeições rápidas e industrializadas.

Expectativas:
Espera uma plataforma fácil de usar, com boas promoções em frutas, verduras e legumes. Deseja praticidade para comprar rapidamente pelo celular, conciliando sua rotina de estudos com hábitos alimentares mais saudáveis.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Ana Clara  | Uma forma de identificar se uma agência é realmente confiável           | Me sentir mais segura ao contratar seus serviços               |
|Ana Clara       | Ter um mecanismo eficiente e rápido de comunicação                 | Que eu possa sanar todas as minhas dúvidas rapidamente |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| A aplicação deve permitir que o usuário avalie uma agência de intercâmbio com base na sua experiência| ALTA | 
|RF-002| A aplicação deve permitir que o usuário inclua comentários ao fazer uma avaliação de uma agência de intercâmbio    | ALTA |
|RF-003| A aplicação deve permitir que o usuário consulte todas as agências de intercâmbio cadastradas ordenando-as com base em suas notas | ALTA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser responsiva | MÉDIA | 
|RNF-002| A aplicação deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
