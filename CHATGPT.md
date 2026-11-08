# _Prompt Utilizado no ChatGPT:_

Dado que você é: Camila Rodrigues

Revendedora de produtos de beleza

- Idade: 34 anos
- Profissão: Microempreendedora individual (MEI)
- Cidade: Campinas – SP
- Negócio: Revenda de cosméticos, maquiagens, perfumes e produtos para cabelo.

### Principal dor relacionada ao gerenciamento de estoque

Camila controla seus produtos utilizando planilhas simples, anotações no caderno e conversas no WhatsApp.

Suas principais dificuldades são:

- Não saber exatamente quais produtos estão disponíveis.
- Perder vendas por descobrir que determinado produto acabou somente quando o cliente solicita.
- Comprar produtos repetidos sem necessidade.
- Esquecer produtos armazenados que estão próximos do vencimento ou sem movimentação.
- Ter dificuldade para identificar quais produtos precisam ser repostos.

### Nível de familiaridade com tecnologia

Intermediário

Utiliza diariamente WhatsApp, Instagram, aplicativos bancários e ferramentas básicas de escritório. Tem facilidade com sistemas intuitivos, mas não possui conhecimentos técnicos avançados.

### Cenário típico de uso do sistema

Camila acessa o sistema pelo celular ou computador durante o atendimento aos clientes.

Ao realizar uma venda, consulta a quantidade disponível do produto e atualiza o estoque.

No início da semana, verifica os alertas do sistema para identificar:

- Produtos com estoque abaixo da quantidade mínima.
- Produtos sem movimentação há mais de 60 dias.
- Produtos que precisam ser comprados novamente.

Exemplo: O sistema informa que determinado perfume possui apenas duas unidades disponíveis, enquanto sua quantidade mínima configurada é cinco. Camila consegue planejar a reposição antes de perder uma venda.

### Métrica de sucesso

Redução de 80% nas ocorrências de produtos indisponíveis durante uma venda.



Responda as seguintes perguntas como a persona Camila:

1. Como é feito o gerenciamento de seu estoque atualmente?

# _Resposta ChatGPT:_

Atualmente, faço o gerenciamento do meu estoque de maneira um pouco desorganizada, utilizando planilhas simples no computador, anotações em um caderno e conversas no WhatsApp para registrar as entradas e saídas dos produtos.

Quando vendo algum cosmético, tento atualizar a quantidade disponível na planilha ou faço uma anotação para atualizar depois. O problema é que, muitas vezes, estou atendendo vários clientes ao mesmo tempo e acabo esquecendo de registrar alguma venda.

Também utilizo minhas anotações para acompanhar os produtos que preciso comprar novamente, mas não tenho um controle preciso das quantidades disponíveis.

Isso acaba gerando alguns problemas, como comprar produtos que já tenho em estoque, descobrir que um produto acabou somente quando um cliente solicita e esquecer produtos que estão parados há muito tempo.

Resumindo, meu controle depende muito da minha memória e de atualizações manuais. Gostaria de ter um sistema simples, no qual pudesse consultar e atualizar meu estoque rapidamente, sem precisar ficar conferindo várias planilhas e anotações.

# _Prompt Utilizado no ChatGPT:_

O que mais lhe incomoda sobre as divergências no estoque?

# _Resposta ChatGPT:_

O que mais me incomoda é não ter confiança de que a quantidade registrada corresponde ao que realmente tenho disponível.

Às vezes, um cliente solicita determinado perfume ou maquiagem, eu consulto minha planilha e vejo que ainda tenho unidades disponíveis, mas, quando vou procurar o produto, descubro que ele já acabou.

Isso me deixa bastante frustrada, porque posso perder uma venda e até a confiança do cliente.

Também me incomoda:

- Perder dinheiro: deixo de vender produtos porque não percebo que estão acabando.
- Comprar desnecessariamente: acabo comprando produtos que ainda tenho guardados, mas que não foram registrados corretamente.
- Desperdiçar produtos: alguns cosméticos ficam esquecidos e acabam vencendo antes que eu consiga vendê-los.
- Perder tempo: preciso conferir planilhas, cadernos e prateleiras para descobrir a quantidade real.

No fundo, o que mais quero é ter segurança de que, quando o sistema informar que tenho cinco unidades de um produto, realmente existam cinco unidades disponíveis para venda.

# _Prompt Utilizado no ChatGPT:_

E se o sistema avisasse sobre um produto parado a muito tempo e/ou que pudesse adicionar um lembrete para quando o estoque estiver acabando?

# _Resposta ChatGPT:_

Eu acharia excelente! Isso resolveria dois problemas que tenho bastante dificuldade em controlar atualmente.

Se o sistema me avisasse quando um produto estivesse parado há muito tempo, eu conseguiria tomar alguma providência antes que ele ficasse esquecido no estoque ou chegasse perto do vencimento. Poderia, por exemplo, criar uma promoção, divulgar o produto no Instagram ou oferecer um desconto para incentivar a venda.

Já o lembrete de estoque baixo seria muito útil para evitar perder vendas. Gostaria de poder configurar uma quantidade mínima para cada produto. Por exemplo, se tenho um perfume com estoque mínimo de cinco unidades, gostaria de receber um alerta quando restassem apenas cinco ou menos.

O que eu gostaria que o sistema oferecesse:

- Alertas de produtos com mais de 60 dias sem movimentação.
- Lembretes personalizados de estoque mínimo para cada produto.
- Avisos sobre produtos próximos do vencimento.
- Uma lista de produtos que precisam ser comprados novamente.
- Notificações fáceis de visualizar, tanto pelo celular quanto pelo computador.

Para mim, o mais importante é que o sistema me avise antes que o problema aconteça, e não somente quando eu já perdi uma venda.

Assim, conseguiria organizar melhor minhas compras, evitar desperdícios e atender minhas clientes com muito mais segurança.

# _Prompt Utilizado no ChatGPT:_

Gere uma tabela com os requisitos funcionais e não funcionais baseado nesta entrevista

# _Resposta ChatGPT:_

Com base na entrevista realizada com Camila Rodrigues, podemos identificar os requisitos funcionais e não funcionais para o MVP do sistema web de gerenciamento de estoque.

Os requisitos foram extraídos das necessidades relatadas pela persona, considerando principalmente o controle de estoque, a prevenção de divergências, os alertas e o planejamento de reposição.
1. Requisitos funcionais (RF)
Os requisitos funcionais descrevem o que o sistema deverá fazer.
ID	Requisito funcional	Descrição	Prioridade
RF01	Cadastrar produtos	Permitir cadastrar produtos com nome, descrição, categoria, preço, quantidade e quantidade mínima.	Alta
RF02	Editar produtos	Permitir alterar as informações dos produtos cadastrados.	Alta
RF03	Excluir produtos	Permitir excluir produtos do estoque, respeitando as regras de integridade dos registros.	Média
RF04	Consultar estoque	Exibir a quantidade disponível de cada produto em estoque.	Alta
RF05	Registrar entrada de produtos	Permitir registrar entradas de mercadorias, atualizando automaticamente a quantidade disponível.	Alta
RF06	Registrar saída de produtos	Permitir registrar vendas e outras saídas, atualizando automaticamente o estoque.	Alta
RF07	Configurar estoque mínimo	Permitir definir uma quantidade mínima individual para cada produto.	Alta
RF08	Alertar sobre estoque baixo	Notificar quando a quantidade disponível atingir ou ficar abaixo do estoque mínimo configurado.	Alta
RF09	Identificar produtos parados	Identificar produtos sem movimentação há mais de 60 dias.	Alta
RF10	Alertar sobre produtos próximos do vencimento	Identificar e notificar sobre produtos que estejam próximos da data de validade.	Média
RF11	Listar produtos para reposição	Disponibilizar uma lista de produtos que precisam ser comprados novamente.	Alta
RF12	Consultar histórico de movimentações	Permitir consultar entradas e saídas realizadas para cada produto.	Média
RF13	Configurar lembretes	Permitir configurar lembretes personalizados para acompanhar os níveis de estoque.	Alta
RF14	Consultar alertas	Disponibilizar uma área para visualizar os alertas de estoque baixo, produtos parados e vencimento próximo.	Alta
RF15	Criar promoções para produtos parados	Permitir identificar produtos que podem receber ações promocionais para estimular sua venda.	Baixa

2. Requisitos não funcionais (RNF)
Os requisitos não funcionais descrevem como o sistema deverá funcionar, considerando qualidade, usabilidade, desempenho e segurança.
ID	Requisito não funcional	Descrição	Prioridade
RNF01	Usabilidade	O sistema deverá possuir interface intuitiva e de fácil utilização, inclusive para usuários sem conhecimentos técnicos avançados.	Alta
RNF02	Responsividade	O sistema deverá adaptar sua interface para utilização em celulares, tablets e computadores.	Alta
RNF03	Desempenho	As consultas de estoque e atualizações de movimentações deverão apresentar respostas rápidas.	Alta
RNF04	Disponibilidade	O sistema deverá estar disponível para acesso sempre que o usuário precisar consultar ou atualizar seu estoque, ressalvadas manutenções programadas.	Alta
RNF05	Segurança	O sistema deverá implementar autenticação e controle de acesso para proteger as informações dos usuários.	Alta
RNF06	Integridade dos dados	O sistema deverá garantir que as movimentações sejam registradas corretamente, evitando divergências nas quantidades do estoque.	Alta
RNF07	Consistência	As quantidades disponíveis deverão ser atualizadas automaticamente após cada movimentação registrada.	Alta
RNF08	Compatibilidade	O sistema deverá funcionar nos principais navegadores modernos, como Google Chrome, Microsoft Edge e Mozilla Firefox.	Média
RNF09	Facilidade de manutenção	O sistema deverá possuir estrutura que permita implementar melhorias e novas funcionalidades futuramente.	Média
RNF10	Confiabilidade dos alertas	Os alertas deverão apresentar informações atualizadas e coerentes com as movimentações registradas no estoque.	Alta

3. Priorização das funcionalidades para o MVP
Considerando que o objetivo inicial é desenvolver um sistema para pequenos revendedores, recomendo priorizar as funcionalidades essenciais.
Prioridade	Funcionalidades
Essencial	Cadastro de produtos, consulta de estoque, registro de entradas e saídas e configuração de estoque mínimo.
Essencial	Alertas de estoque baixo e identificação de produtos parados há mais de 60 dias.
Essencial	Lista de produtos que precisam de reposição.
Importante	Histórico de movimentações, lembretes personalizados e alertas de vencimento.
Futuro	Sugestões de promoções e integração com notificações externas.

4. Relação entre as dores da persona e os requisitos
Esta relação ajuda a justificar cada funcionalidade durante a especificação do projeto.
Dor identificada na entrevista	Requisitos relacionados
Não saber exatamente quais produtos estão disponíveis.	RF01, RF02, RF04, RF05 e RF06
Perder vendas porque o produto acabou.	RF07, RF08 e RF13
Comprar produtos repetidos sem necessidade.	RF04, RF11 e RF12
Esquecer produtos armazenados há muito tempo.	RF09 e RF14
Ter produtos próximos do vencimento.	RF10 e RF14
Ter dificuldade para identificar produtos que precisam de reposição.	RF07, RF08 e RF11
Perder tempo consultando planilhas e cadernos.	RNF01, RNF02 e RNF03

5. Métrica de sucesso do MVP
A métrica estabelecida pela persona é:

Reduzir em 80% as ocorrências de produtos indisponíveis durante uma venda.

Para acompanhar esse resultado, sugiro utilizar:
\[
\text{Redução (\%)} =
\frac{\text{Ocorrências iniciais} - \text{Ocorrências atuais}}
{\text{Ocorrências iniciais}} \times 100
\]

Por exemplo, se Camila inicialmente teve 20 ocorrências de produtos indisponíveis durante vendas e, após utilizar o sistema, passou a ter apenas 4:
\[
\frac{20-4}{20}\times100=80\%
\]


Observação importante para a especificação: os requisitos RF15 (promoções) e RF10 (vencimento) são oportunidades identificadas na entrevista, mas não precisam necessariamente fazer parte da primeira versão do MVP. Além disso, para garantir a confiabilidade dos alertas, será importante definir regras para o cálculo dos dias sem movimentação e para a atualização automática do estoque.

A tabela pode ser utilizada como base para a documentação de requisitos do projeto, elaboração do Product Backlog e desenvolvimento dos casos de uso.

# _Prompt utilizado ChatGPT:_

Baseado nos requisitos acima, realize o seguinte:
MOSCOW: (Priorização) 
MUST / SHOULD / COULD / 
WONT
INVEST: (Critérios de qualidade)
INDEPENDENT, NEGOTIABLE, VALUABLE, 
ESTIMABLE, SMALL, TESTABLE
3 C’s: (components user story)
CARD – CONVERSATION –
CONFIRMATION

# _Resposta ChatGPT:_

# Priorização e especificação dos requisitos do sistema de gerenciamento de estoque

Com base na entrevista com Camila Rodrigues e nos requisitos funcionais e não funcionais levantados anteriormente, apresento a aplicação de três técnicas de Engenharia de Requisitos:

1. MoSCoW: priorização dos requisitos.
2. INVEST: avaliação da qualidade das histórias de usuário.
3. 3 C's: estruturação das histórias de usuário por meio de Card, Conversation e Confirmation.

O objetivo é organizar o escopo do MVP, identificar o que é indispensável para a primeira versão e transformar as necessidades da persona em histórias de usuário que possam ser desenvolvidas e testadas.

## 1. MoSCoW — Priorização dos requisitos

O método MoSCoW classifica os requisitos em quatro categorias:

| Classificação | Significado                 | Aplicação                                                                       |
| ------------- | --------------------------- | ------------------------------------------------------------------------------- |
| Must Have     | Obrigatório                 | Funcionalidades indispensáveis para o funcionamento do MVP.                     |
| Should Have   | Importante                  | Funcionalidades relevantes, mas que podem ser implementadas após as essenciais. |
| Could Have    | Desejável                   | Funcionalidades que agregam valor, mas não são essenciais.                      |
| Won't Have    | Não será implementado agora | Funcionalidades fora do escopo da versão atual.                                 |

### 1.1. Priorização dos requisitos funcionais

| ID   | Requisito                                     | Prioridade  | Justificativa                                                                                 |
| ---- | --------------------------------------------- | ----------- | --------------------------------------------------------------------------------------------- |
| RF01 | Cadastrar produtos                            | Must Have   | Necessário para iniciar o gerenciamento do estoque.                                           |
| RF02 | Editar produtos                               | Must Have   | Permite manter os dados dos produtos atualizados.                                             |
| RF03 | Excluir produtos                              | Should Have | É útil, mas pode ser substituído inicialmente pela desativação do produto.                    |
| RF04 | Consultar estoque                             | Must Have   | Permite verificar a disponibilidade antes de realizar uma venda.                              |
| RF05 | Registrar entrada de produtos                 | Must Have   | Necessário para controlar as reposições.                                                      |
| RF06 | Registrar saída de produtos                   | Must Have   | Necessário para manter o estoque atualizado após vendas.                                      |
| RF07 | Configurar estoque mínimo                     | Must Have   | Permite definir limites individuais para cada produto.                                        |
| RF08 | Alertar sobre estoque baixo                   | Must Have   | Evita descobrir que um produto acabou somente durante uma venda.                              |
| RF09 | Identificar produtos parados                  | Must Have   | Atende diretamente à necessidade de identificar produtos sem movimentação há mais de 60 dias. |
| RF10 | Alertar sobre produtos próximos do vencimento | Should Have | Ajuda a evitar perdas financeiras com produtos vencidos.                                      |
| RF11 | Listar produtos para reposição                | Must Have   | Facilita o planejamento de compras.                                                           |
| RF12 | Consultar histórico de movimentações          | Should Have | Ajuda a identificar e investigar divergências no estoque.                                     |
| RF13 | Configurar lembretes                          | Should Have | Permite personalizar o acompanhamento dos produtos.                                           |
| RF14 | Consultar alertas                             | Must Have   | Centraliza os avisos importantes para a tomada de decisão.                                    |
| RF15 | Criar promoções para produtos parados         | Won't Have  | Ações promocionais e gestão de campanhas podem ficar fora do escopo inicial.                  |

### 1.2. Priorização dos requisitos não funcionais

| ID    | Requisito                  | Prioridade  | Justificativa                                                      |
| ----- | -------------------------- | ----------- | ------------------------------------------------------------------ |
| RNF01 | Usabilidade                | Must Have   | A interface precisa ser simples e intuitiva.                       |
| RNF02 | Responsividade             | Must Have   | Camila utiliza o sistema pelo celular e computador.                |
| RNF03 | Desempenho                 | Should Have | As consultas e atualizações precisam ser rápidas.                  |
| RNF04 | Disponibilidade            | Should Have | O sistema deve estar acessível durante a rotina comercial.         |
| RNF05 | Segurança                  | Must Have   | Protege os dados e restringe o acesso de usuários não autorizados. |
| RNF06 | Integridade dos dados      | Must Have   | Evita divergências entre o estoque registrado e as movimentações.  |
| RNF07 | Consistência               | Must Have   | Garante a atualização correta das quantidades após movimentações.  |
| RNF08 | Compatibilidade            | Should Have | Permite utilizar diferentes navegadores modernos.                  |
| RNF09 | Facilidade de manutenção   | Should Have | Facilita futuras evoluções do sistema.                             |
| RNF10 | Confiabilidade dos alertas | Must Have   | Os avisos precisam refletir corretamente a situação do estoque.    |

### 1.3. Resumo da priorização MoSCoW

Must Have

Essencial

Cadastro e edição de produtos, consulta de estoque, entradas, saídas, estoque mínimo, alertas de estoque baixo, produtos parados, reposição, consulta de alertas, usabilidade, responsividade, segurança e integridade.

Should Have

Importante

Exclusão de produtos, histórico de movimentações, alertas de vencimento, lembretes personalizados, desempenho, disponibilidade, compatibilidade e manutenção.

Could Have

Desejável

Sugestões automáticas de ações promocionais para produtos parados.

Won't Have

Fora do escopo

Criação e gerenciamento de campanhas promocionais dentro do sistema na primeira versão.

Observação: RF15 foi originalmente classificado como uma funcionalidade de baixa prioridade. Nesta priorização, a sugestão de ações promocionais pode ser considerada Could Have, enquanto o gerenciamento completo de campanhas fica como Won't Have. Isso evita excluir uma possibilidade de evolução futura.

## 2. INVEST — Critérios de qualidade das histórias de usuário

O INVEST é um conjunto de seis critérios utilizados para avaliar se uma história de usuário está bem definida e preparada para desenvolvimento.

| Critério        | Significado  | Aplicação no projeto                                                                          |
| --------------- | ------------ | --------------------------------------------------------------------------------------------- |
| I — Independent | Independente | A história deve ter o mínimo possível de dependência de outras histórias.                     |
| N — Negotiable  | Negociável   | A história não deve representar uma especificação rígida; seus detalhes podem ser discutidos. |
| V — Valuable    | Valiosa      | Deve entregar algum benefício real ao usuário.                                                |
| E — Estimable   | Estimável    | Deve possuir informações suficientes para estimar o esforço de desenvolvimento.               |
| S — Small       | Pequena      | Deve ser suficientemente pequena para ser desenvolvida dentro de uma Sprint.                  |
| T — Testable    | Testável     | Deve possuir critérios objetivos que permitam verificar se foi implementada corretamente.     |

### 2.1. Histórias de usuário propostas

A partir dos requisitos Must Have, podemos criar as seguintes histórias:

| ID   | História de usuário                                                                                                       | Requisito relacionado |
| ---- | ------------------------------------------------------------------------------------------------------------------------- | --------------------- |
| US01 | Como Camila, quero cadastrar produtos para manter meu estoque organizado.                                                 | RF01                  |
| US02 | Como Camila, quero consultar as quantidades disponíveis para saber quais produtos posso vender.                           | RF04                  |
| US03 | Como Camila, quero registrar entradas de produtos para atualizar meu estoque quando realizar novas compras.               | RF05                  |
| US04 | Como Camila, quero registrar saídas de produtos para manter o estoque atualizado após as vendas.                          | RF06                  |
| US05 | Como Camila, quero configurar uma quantidade mínima para cada produto para saber quando preciso realizar uma reposição.   | RF07                  |
| US06 | Como Camila, quero receber alertas quando um produto atingir ou ficar abaixo do estoque mínimo para evitar perder vendas. | RF08                  |
| US07 | Como Camila, quero identificar produtos sem movimentação há mais de 60 dias para evitar que fiquem esquecidos no estoque. | RF09                  |
| US08 | Como Camila, quero visualizar uma lista de produtos que precisam de reposição para planejar minhas compras.               | RF11                  |
| US09 | Como Camila, quero consultar os alertas em um único local para acompanhar as situações que exigem minha atenção.          | RF14                  |

### 2.2. Avaliação das histórias utilizando INVEST

A tabela abaixo apresenta uma avaliação inicial. O objetivo é verificar se cada história atende aos seis critérios.

Legenda:

-

  Sim

  &#x20;Atende ao critério.


-

  Parcial

  &#x20;Precisa de refinamento.



| História                         | I       | N   | V   | E   | S   | T       |
| -------------------------------- | ------- | --- | --- | --- | --- | ------- |
| US01 — Cadastrar produtos        | Sim     | Sim | Sim | Sim | Sim | Sim     |
| US02 — Consultar estoque         | Sim     | Sim | Sim | Sim | Sim | Sim     |
| US03 — Registrar entradas        | Sim     | Sim | Sim | Sim | Sim | Sim     |
| US04 — Registrar saídas          | Sim     | Sim | Sim | Sim | Sim | Sim     |
| US05 — Configurar estoque mínimo | Sim     | Sim | Sim | Sim | Sim | Sim     |
| US06 — Alertas de estoque baixo  | Parcial | Sim | Sim | Sim | Sim | Parcial |
| US07 — Produtos parados          | Sim     | Sim | Sim | Sim | Sim | Parcial |
| US08 — Lista de reposição        | Parcial | Sim | Sim | Sim | Sim | Parcial |
| US09 — Consultar alertas         | Parcial | Sim | Sim | Sim | Sim | Parcial |

Pontos de atenção identificados:

- US06 depende da existência de produtos cadastrados e de quantidades mínimas configuradas.
- US07 precisa definir como será calculado o período de 60 dias sem movimentação.
- US08 depende de uma regra clara para determinar quais produtos precisam de reposição.
- US09 depende da implementação dos mecanismos que geram os alertas.

Essas dependências não invalidam as histórias, mas precisam ser consideradas no planejamento do desenvolvimento.

## 3. 3 C's — Components of User Story

O modelo 3 C's organiza as histórias de usuário em três componentes:

| Componente   | Significado | Objetivo                                                                                   |
| ------------ | ----------- | ------------------------------------------------------------------------------------------ |
| Card         | Cartão      | Descrever resumidamente a necessidade do usuário.                                          |
| Conversation | Conversa    | Registrar discussões, regras de negócio e detalhes da funcionalidade.                      |
| Confirmation | Confirmação | Definir critérios de aceitação para verificar se a história foi implementada corretamente. |

A seguir, aplico os três componentes às principais histórias do MVP.

### US01 — Cadastro de produtos

CARD

Como Camila,

Quero cadastrar produtos no sistema,

Para manter meu estoque organizado e consultar as informações de cada produto.

CONVERSATION

Regras e detalhes:

- O produto deverá possuir nome e categoria.
- Deverá permitir informar preço e quantidade inicial.
- Deverá permitir configurar uma quantidade mínima.
- Deverá permitir informar a data de validade, quando aplicável.

  CONFIRMATION

  Critérios de aceitação:
- Dado que Camila esteja cadastrando um produto, quando preencher os campos obrigatórios e confirmar, então o sistema deverá salvar o produto.
- Dado que o nome obrigatório não tenha sido informado, quando tentar salvar, então o sistema deverá apresentar uma mensagem de validação.
- Dado que o produto tenha sido cadastrado, quando consultar o estoque, então ele deverá aparecer na listagem.

### US02 — Consulta de estoque

CARD

Como Camila,

Quero consultar as quantidades disponíveis dos produtos,

Para saber quais produtos posso oferecer aos meus clientes.

CONVERSATION

Regras e detalhes:

- Exibir nome do produto.
- Exibir quantidade disponível.
- Exibir quantidade mínima configurada.
- Permitir localizar produtos pelo nome ou categoria.

  CONFIRMATION

  Critérios de aceitação:
- Dado que existam produtos cadastrados, quando Camila acessar o estoque, então o sistema deverá apresentar os produtos e suas quantidades.
- Dado que Camila pesquise um produto pelo nome, quando realizar a consulta, então o sistema deverá apresentar os resultados correspondentes.
- Dado que não existam produtos cadastrados, quando acessar o estoque, então o sistema deverá informar que não há produtos disponíveis.

### US03 — Registro de entrada de produtos

CARD

Como Camila,

Quero registrar a entrada de produtos,

Para atualizar meu estoque quando realizar novas compras.

CONVERSATION

Regras e detalhes:

- Selecionar um produto cadastrado.
- Informar a quantidade recebida.
- Atualizar automaticamente o saldo do estoque.
- Registrar a movimentação realizada.

  CONFIRMATION

  Critérios de aceitação:
- Dado que Camila tenha 5 unidades de um perfume, quando registrar a entrada de mais 10 unidades, então o estoque deverá apresentar 15 unidades.
- Dado que a quantidade informada seja zero ou negativa, quando tentar registrar a entrada, então o sistema deverá rejeitar a operação.
- Dado que a entrada seja registrada com sucesso, quando consultar as movimentações, então o registro deverá estar disponível.

### US04 — Registro de saída de produtos

CARD

Como Camila,

Quero registrar a saída de produtos,

Para manter meu estoque atualizado após realizar vendas.

CONVERSATION

Regras e detalhes:

- Selecionar um produto disponível.
- Informar a quantidade vendida.
- Atualizar automaticamente o estoque.
- Impedir saídas superiores à quantidade disponível.

  CONFIRMATION

  Critérios de aceitação:
- Dado que Camila tenha 10 unidades de um produto, quando registrar uma venda de 3 unidades, então o estoque deverá apresentar 7 unidades.
- Dado que Camila tente registrar uma saída superior à quantidade disponível, quando confirmar a operação, então o sistema deverá impedir a movimentação.
- Dado que a saída seja registrada com sucesso, quando consultar o histórico, então a movimentação deverá estar registrada.

### US05 — Configuração de estoque mínimo

CARD

Como Camila,

Quero configurar uma quantidade mínima para cada produto,

Para saber quando preciso realizar uma nova compra.

CONVERSATION

Regras e detalhes:

- Cada produto poderá possuir uma quantidade mínima individual.
- A quantidade mínima deverá poder ser alterada.
- O sistema deverá utilizar esse valor como referência para gerar alertas.

  CONFIRMATION

  Critérios de aceitação:
- Dado que Camila configure o estoque mínimo de um perfume para 5 unidades, quando salvar, então o sistema deverá armazenar essa configuração.
- Dado que o estoque mínimo esteja configurado, quando Camila consultar o produto, então deverá visualizar a quantidade mínima.

### US06 — Alerta de estoque baixo

CARD

Como Camila,

Quero receber alertas quando um produto atingir ou ficar abaixo do estoque mínimo,

Para realizar a reposição antes de perder uma venda.

CONVERSATION

Regras e detalhes:

- Comparar a quantidade disponível com a quantidade mínima.
- Gerar alerta quando a quantidade disponível for menor ou igual ao mínimo.
- Identificar claramente o produto e a quantidade disponível.

  CONFIRMATION

  Critérios de aceitação:
- Dado que um perfume tenha estoque mínimo de 5 unidades, quando sua quantidade disponível chegar a 5, então o sistema deverá gerar um alerta.
- Dado que o perfume possua apenas 2 unidades, quando Camila consultar os alertas, então o sistema deverá indicar que o produto precisa de reposição.
- Dado que o estoque seja atualizado para uma quantidade superior ao mínimo, quando o sistema atualizar os alertas, então o alerta de estoque baixo deverá deixar de ser apresentado como pendente.

### US07 — Identificação de produtos parados

CARD

Como Camila,

Quero identificar produtos sem movimentação há mais de 60 dias,

Para evitar que fiquem esquecidos no estoque.

CONVERSATION

Regras e detalhes:

- Considerar a data da última movimentação do produto.
- Identificar produtos sem entradas ou saídas por mais de 60 dias.
- Exibir a data da última movimentação.
- Disponibilizar uma listagem dos produtos identificados.

  CONFIRMATION

  Critérios de aceitação:
- Dado que um produto esteja sem movimentação há 61 dias, quando o sistema realizar a verificação, então deverá identificá-lo como produto parado.
- Dado que um produto esteja sem movimentação há 30 dias, quando o sistema realizar a verificação, então não deverá classificá-lo como parado.
- Dado que um produto seja identificado como parado, quando Camila acessar a listagem, então deverá visualizar seu nome e a data da última movimentação.

### US08 — Lista de produtos para reposição

CARD

Como Camila,

Quero visualizar uma lista de produtos que precisam ser comprados novamente,

Para planejar minhas compras e evitar adquirir produtos desnecessários.

CONVERSATION

Regras e detalhes:

- Considerar produtos com estoque igual ou inferior ao mínimo.
- Exibir quantidade disponível e quantidade mínima.
- Permitir identificar os produtos prioritários para compra.

  CONFIRMATION

  Critérios de aceitação:
- Dado que um produto tenha estoque de 2 unidades e mínimo de 5, quando Camila acessar a lista de reposição, então o produto deverá aparecer.
- Dado que um produto tenha estoque de 10 unidades e mínimo de 5, quando acessar a lista, então ele não deverá aparecer como necessitando reposição.

### US09 — Consulta de alertas

CARD

Como Camila,

Quero visualizar meus alertas em um único local,

Para acompanhar os produtos que precisam da minha atenção.

CONVERSATION

Regras e detalhes:

- Centralizar os alertas de estoque baixo.
- Apresentar produtos parados há mais de 60 dias.
- Apresentar alertas de vencimento, quando essa funcionalidade estiver disponível.
- Identificar o motivo de cada alerta.

  CONFIRMATION

  Critérios de aceitação:
- Dado que existam produtos com estoque baixo, quando Camila acessar a área de alertas, então deverá visualizar os produtos correspondentes.
- Dado que existam produtos parados, quando acessar a área de alertas, então deverá visualizar esses produtos.
- Dado que não existam alertas pendentes, quando acessar a área de alertas, então o sistema deverá informar que não há situações que necessitem de atenção.

## 4. Resultado consolidado

A aplicação das três técnicas permite organizar o desenvolvimento da seguinte maneira:

| Técnica | Resultado para o projeto                                                                                        |
| ------- | --------------------------------------------------------------------------------------------------------------- |
| MoSCoW  | Define quais funcionalidades devem fazer parte do MVP e quais podem ficar para versões futuras.                 |
| INVEST  | Ajuda a garantir que as histórias sejam independentes, negociáveis, valiosas, estimáveis, pequenas e testáveis. |
| 3 C's   | Transforma as necessidades da persona em histórias discutíveis e critérios objetivos de aceitação.              |

### Sugestão de sequência de desenvolvimento

1. Etapa 1 — Estrutura do estoque

   Cadastro, edição e consulta de produtos.
2. Etapa 2 — Movimentações

   Registro de entradas e saídas, garantindo a integridade das quantidades.
3. Etapa 3 — Controle preventivo

   Configuração de estoque mínimo e alertas de estoque baixo.
4. Etapa 4 — Monitoramento

   Identificação de produtos parados e centralização dos alertas.
5. Etapa 5 — Planejamento

   Lista de reposição, histórico de movimentações e funcionalidades complementares.

Conclusão: para esse MVP, a prioridade deve ser garantir que o estoque registrado seja confiável. Os alertas só serão realmente úteis se as entradas e saídas forem registradas corretamente. Dessa forma, o sistema atende à principal necessidade de Camila: saber exatamente o que tem disponível e antecipar problemas antes de perder uma venda.