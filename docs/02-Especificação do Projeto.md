# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

# Personas

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

# Histórias de Usuários

Com base na análise das personas, foram identificadas as seguintes histórias de usuários. Elas foram organizadas por contexto, de forma a facilitar a compreensão dos requisitos funcionais e não funcionais relacionados à aplicação.

## Cadastro e Divulgação de Produtos (Feirantes)

| EU COMO... `PERSONA` | QUERO/PRECISO ... `FUNCIONALIDADE`                            | PARA ... `MOTIVO/VALOR`                                          |
| -------------------- | ------------------------------------------------------------- | ---------------------------------------------------------------- |
| Maria (Feirante)     | Cadastrar minha empresa/feira com CNPJ e endereço             | Disponibilizar minhas ofertas de forma oficial e confiável       |
| Maria (Feirante)     | Criar posts com foto, descrição, preço, validade e quantidade | Divulgar os produtos que sobraram da feira de forma atrativa     |
| Maria (Feirante)     | Editar ou excluir minhas próprias ofertas                     | Manter as informações atualizadas e evitar anúncios inválidos    |
| Antônio (Agricultor) | Associar meu perfil ao cadastro da minha feira                | Garantir que eu possa publicar produtos em nome da minha empresa |
| Antônio (Agricultor) | Ter minhas ofertas excluídas automaticamente após a validade  | Evitar problemas com consumidores e manter a confiança           |
| Antônio (Agricultor) | Visualizar a média de avaliação da minha feira                | Acompanhar minha reputação e planejar melhorias nas vendas       |


## Busca e Compra de Produtos (Consumidores)

| EU COMO... `PERSONA`               | QUERO/PRECISO ... `FUNCIONALIDADE`                                    | PARA ... `MOTIVO/VALOR`                                            |
| ---------------------------------- | --------------------------------------------------------------------- | ------------------------------------------------------------------ |
| Clara (Consumidora de baixa renda) | Criar minha conta com endereço completo                               | Ter acesso a ofertas próximas de onde moro                         |
| Clara (Consumidora de baixa renda) | Visualizar cards de ofertas com foto, preço e validade                | Economizar nas compras semanais com confiança na qualidade         |
| Clara (Consumidora de baixa renda) | Receber apenas ofertas ainda válidas                                  | Garantir que os alimentos estejam próprios para consumo            |
| João (Consumidor consciente)       | Pesquisar e filtrar produtos por nome ou categoria                    | Localizar rapidamente itens que desejo comprar                     |
| João (Consumidor consciente)       | Acessar informações completas da empresa (nome, endereço, avaliações) | Garantir que compro de feirantes confiáveis e sustentáveis         |
| João (Consumidor consciente)       | Avaliar feirantes com notas e comentários                             | Ajudar a comunidade e incentivar boas práticas                     |
| Luana (Estudante universitária)    | Navegar no feed de ofertas pelo celular                               | Conciliar minha rotina corrida com hábitos de alimentação saudável |
| Luana (Estudante universitária)    | Ter carregamento rápido nas páginas (≤2s)                             | Não perder tempo durante o uso da aplicação                        |
| Luana (Estudante universitária)    | Ver data/hora de criação das ofertas                                  | Confiar que as informações estão atualizadas e corretas            |


# Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-------------------------|----|
|RF-001| A aplicação deve permitir o **cadastro de pessoa** (nome, e-mail, senha, endereço completo: logradouro, número, bairro, cidade, UF, CEP). | ALTA |
|RF-002| A aplicação deve permitir a **autenticação** do usuário (login/logout) | ALTA |
|RF-003| A aplicação deve permitir o **cadastro de empresa/feira** com **CNPJ obrigatório** e **endereço completo** (logradouro, número, bairro, cidade, UF, CEP). | ALTA |
|RF-004| O backend deve **validar o CNPJ** (formato e dígito verificador) no cadastro/edição de empresa. | ALTA |
|RF-005| A aplicação deve permitir que um usuário autenticado se **associe ao perfil de feirante (empresa)** para **publicar ofertas**. | ALTA |
|RF-006| O backend deve **validar a cidade** do usuário e **retornar apenas feiras/ofertas da mesma cidade** do endereço da pessoa. | ALTA |
|RF-007| A aplicação deve disponibilizar uma **tela de ofertas** (feed) para pesquisa/visualização de **posts da mesma cidade** do usuário. | ALTA |
|RF-008| A criação de **post de oferta** deve permitir: **foto** do produto (obrigatória), nome, descrição, **data de validade**, **preço promocional** e **quantidade**. | ALTA |
|RF-009| Cada **card de oferta** deve exibir: **foto**, nome do produto, preço, **data de validade**, **nome da empresa** e **média de avaliação** da empresa. | ALTA |
|RF-010| Ao **clicar no card**, o usuário deve visualizar a **página da empresa/feira** (nome, CNPJ mascarado, endereço, contato/horário se houver), **ofertas ativas** e **avaliações**. | ALTA |
|RF-011| A aplicação deve permitir que usuários autenticados **avaliem a empresa** (nota **1 a 5 estrelas** e **comentário**). | ALTA |
|RF-012| O sistema deve **persistir avaliações** em tabela própria **idEmpresa, nota, descrição**. | ALTA |
|RF-013| O sistema deve **recalcular e atualizar** o campo **MediaNota** na tabela **Empresa** a cada **inserção/edição/exclusão** de avaliação. | ALTA |
|RF-014| A **listagem de ofertas** deve **exibir somente** posts com **validade = data atual + 1 dia** (“vencem amanhã”). | ALTA |
|RF-015| Ofertas com **validade ≤ data atual** não devem ser listadas; se a validade for o **dia atual**, o **anúncio deve ser excluído automaticamente** pelo sistema. | ALTA |
|RF-016| O feed de ofertas deve permitir **busca por termo** (ex.: “tomate”). | MÉDIA |
|RF-017| A aplicação deve **paginar** a listagem de ofertas. | MÉDIA |
|RF-018| O feirante deve poder **editar** e **excluir** suas próprias ofertas. | MÉDIA |
|RF-019| A aplicação deve **impedir avaliações anônimas** e **limitar** múltiplas avaliações por usuário/empresa. | MÉDIA |
|RF-020| O sistema deve **registrar data/hora de criação e atualização** para pessoa, empresa, oferta e avaliação. | MÉDIA |

# Requisitos não Funcionais

|ID     | Descrição do Requisito  | Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser **responsiva** e funcionar nos principais navegadores modernos. | ALTA |
|RNF-002| **Desempenho**: páginas de listagem (ofertas) devem responder em até **2 s** em condições normais (até 100 usuários simultâneos). | ALTA |
|RNF-003| **Validação de dados**: CNPJ deve ter **formato e dígitos verificadores** válidos; CEP em padrão nacional. | ALTA |
|RNF-004| **Confiabilidade**: a exclusão automática de ofertas do dia deve ocorrer via **tarefa agendada** confiável. | ALTA |
|RNF-005| **Usabilidade**: ações principais (buscar oferta e abrir card) devem ocorrer em **até 3 cliques** a partir da home. | MÉDIA |
|RNF-006| **Compatibilidade de mídia**: aceitar upload de **imagem** em JPG/PNG/WebP com **limite de tamanho** (ex.: 2 MB). | MÉDIA |
|RNF-007| **Proteção contra abuso**: limitar **tamanho do comentário** (ex.: 200 caracteres) e aplicar **rate-limit** para avaliações/edições. | BAIXA |

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

# Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |

# Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
