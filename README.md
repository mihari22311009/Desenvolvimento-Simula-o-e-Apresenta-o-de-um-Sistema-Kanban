Desenvolvimento, Simulação e Apresentação de um Sistema Kanban
Sistema para Gestão de Reservas de uma Pousada

Projeto desenvolvido na disciplina de Metodologias Ágeis, com o objetivo de aplicar, de forma prática, os conceitos e princípios do Kanban no planejamento, organização, acompanhamento e melhoria do fluxo de trabalho de uma equipe de desenvolvimento de software.

O projeto consiste na simulação do desenvolvimento de um sistema web para gerenciamento de reservas de uma pousada, utilizando um quadro Kanban para representar todas as etapas pelas quais uma demanda passa desde sua solicitação até sua conclusão.

1. Objetivo do projeto

O principal objetivo foi compreender, por meio de uma simulação prática, como o método Kanban pode ser utilizado para organizar o trabalho de uma equipe, facilitar a visualização das atividades e identificar problemas que prejudicam o fluxo de entrega.

Além disso, a atividade buscou demonstrar conceitos importantes das metodologias ágeis, como:

Visualização do fluxo de trabalho;

Limitação do trabalho em progresso (WIP);

Priorização de demandas;

Identificação e tratamento de gargalos;

Redução de tempo de espera;

Melhoria contínua;

Colaboração entre os integrantes da equipe.

2. Contexto do sistema

Para a simulação, foi definido um sistema web destinado ao gerenciamento das reservas de uma pousada.

O sistema possui como principais demandas e funcionalidades:

Cadastro e gerenciamento de reservas;

Consulta da disponibilidade dos quartos;

Registro de check-in;

Registro de check-out;

Cancelamento de reservas;

Controle das informações relacionadas aos hóspedes;

Gerenciamento da ocupação dos quartos.

Cada uma dessas funcionalidades foi representada no quadro Kanban como um cartão, permitindo acompanhar visualmente seu andamento durante a simulação.

3. Organização do quadro Kanban

O quadro foi desenvolvido utilizando o Trello, ferramenta escolhida para representar visualmente o fluxo de trabalho.

O processo foi dividido nas seguintes etapas:

Solicitado

Nesta coluna ficam as demandas inicialmente recebidas pela equipe. Nesse momento, os itens ainda não foram analisados ou preparados para desenvolvimento.

Pronto para Desenvolver

Após serem analisadas, as demandas que possuem informações suficientes e estão priorizadas são movidas para essa etapa.

O objetivo é manter um conjunto de tarefas preparadas para que a equipe possa iniciar o desenvolvimento sem depender de novas informações.

Em Desenvolvimento

Nesta etapa ocorre a implementação das funcionalidades.

Os integrantes da equipe trabalham nas tarefas selecionadas, respeitando os limites de WIP definidos para evitar que muitas atividades sejam iniciadas simultaneamente.

Revisão

Após o desenvolvimento, a tarefa passa por uma revisão realizada por outro integrante da equipe.

Essa etapa tem como objetivo verificar a implementação, identificar possíveis erros e garantir que o código esteja de acordo com o que foi solicitado.

Testes

Depois da revisão, a funcionalidade é encaminhada para testes.

Nesta etapa é verificado se o comportamento implementado corresponde aos requisitos definidos e se a funcionalidade apresenta algum problema que precise ser corrigido.

Entregue

Quando a funcionalidade passa pelas etapas anteriores e é validada, ela é movida para a coluna Entregue.

Isso representa que o trabalho foi concluído e está pronto para ser considerado como uma entrega finalizada.

Bloqueado

Além das colunas principais, foi utilizada a etiqueta Bloqueado.

Essa identificação permite sinalizar tarefas que não podem continuar avançando por algum motivo, como dependência de outra atividade, problema técnico, falta de informação ou indisponibilidade de algum recurso.

A utilização dessa sinalização facilita a identificação de impedimentos e permite que a equipe tome medidas para desbloquear as atividades.

4. Aplicação dos limites de WIP

Um dos principais conceitos utilizados na simulação foi o WIP (Work in Progress), que representa a quantidade de tarefas que podem estar sendo executadas simultaneamente em determinada etapa.

Foram definidos limites para evitar que a equipe iniciasse muitas tarefas ao mesmo tempo.

Por exemplo, em vez de cada integrante iniciar uma nova atividade sempre que terminasse uma tarefa, a equipe deveria observar o limite estabelecido para cada coluna e priorizar a conclusão das atividades que já estavam em andamento.

Essa estratégia permite reduzir o acúmulo de tarefas, aumentar o foco da equipe e tornar os problemas do fluxo mais visíveis.

5. Simulação do fluxo de trabalho

Para avaliar o funcionamento do Kanban, foram realizadas três rodadas de simulação.

Durante cada rodada, as tarefas foram movimentadas entre as colunas de acordo com seu estado de desenvolvimento.

A equipe acompanhou a movimentação dos cartões e observou fatores como:

Quantidade de tarefas em cada etapa;

Tempo de permanência das tarefas nas colunas;

Tarefas bloqueadas;

Acúmulo de atividades;

Capacidade da equipe de realizar testes;

Impacto dos limites de WIP no fluxo.

A utilização do quadro permitiu observar que o fluxo não depende apenas da velocidade de desenvolvimento. Uma etapa mais lenta pode impedir que todo o processo avance, mesmo que as etapas anteriores estejam funcionando normalmente.

6. Identificação do gargalo

Durante as três rodadas, foi identificado um problema recorrente na etapa de Testes.

As tarefas chegavam nessa etapa em uma velocidade maior do que a capacidade disponível para realizar as validações. Como consequência, algumas atividades permaneciam aguardando testes, formando uma fila.

Esse comportamento caracteriza um gargalo, pois uma etapa do processo possui uma capacidade de processamento menor do que o volume de trabalho que recebe.

O gargalo também provocou aumento no tempo de espera das tarefas e dificultou a conclusão de novas atividades.

A visualização proporcionada pelo Kanban foi importante para identificar esse problema, pois o acúmulo de cartões na etapa de testes tornou o desequilíbrio do fluxo facilmente perceptível.

7. Melhoria realizada

Após identificar o gargalo, foi realizada uma melhoria na organização visual da etapa de testes.

Os itens foram separados entre:

Testes em andamento – atividades que estavam sendo efetivamente testadas;

Aguardando testes – atividades que já estavam prontas para validação, mas ainda não haviam sido iniciadas devido à capacidade limitada da etapa.

Essa alteração permitiu diferenciar claramente o trabalho que estava sendo executado daquele que estava apenas aguardando atendimento.

A mudança não eliminou imediatamente a limitação de capacidade, mas tornou o problema mais visível e facilitou o acompanhamento da fila de testes.

Essa abordagem está alinhada ao princípio de melhoria contínua do Kanban, no qual a equipe observa o funcionamento do fluxo, identifica problemas e realiza ajustes para melhorar o processo.

8. Resultados observados

A simulação permitiu compreender, na prática, diversos conceitos relacionados ao Kanban.

Limites de WIP

Foi possível observar que limitar a quantidade de tarefas simultâneas ajuda a evitar o excesso de trabalho iniciado e incentiva a equipe a concluir atividades antes de iniciar novas demandas.

Gargalos

A etapa de testes demonstrou como uma capacidade limitada em uma parte do processo pode gerar filas e aumentar o tempo necessário para concluir as tarefas.

Visualização

O quadro Kanban facilitou o acompanhamento do estado de cada atividade e permitiu identificar rapidamente onde havia concentração de tarefas.

Priorização

A organização das demandas ajudou a equipe a decidir quais atividades deveriam ser tratadas primeiro, principalmente quando existiam demandas consideradas urgentes ou com prazo definido.

Tempo de entrega

A simulação demonstrou que o tempo necessário para entregar uma funcionalidade não depende somente do tempo de desenvolvimento. Esperas, bloqueios, revisões e testes também influenciam o tempo total de conclusão.

Melhoria contínua

A identificação do gargalo e a reorganização da etapa de testes demonstraram a importância de analisar constantemente o fluxo e realizar mudanças quando forem encontrados problemas.

9. Conclusão

A utilização do Kanban possibilitou aplicar de maneira prática conceitos estudados na disciplina de Metodologias Ágeis.

Por meio da simulação do sistema de reservas da pousada, foi possível acompanhar o fluxo de uma demanda desde sua solicitação até a entrega, além de observar como fatores como WIP, priorização, bloqueios e gargalos interferem no processo de desenvolvimento.

O principal problema identificado foi o acúmulo de atividades na etapa de testes. A partir dessa observação, a equipe realizou uma melhoria na organização visual dessa etapa, diferenciando as tarefas em execução daquelas que estavam aguardando atendimento.

Dessa forma, o projeto demonstrou que o Kanban não consiste apenas em organizar tarefas em colunas, mas também em visualizar o trabalho, controlar o fluxo, identificar problemas e promover melhorias contínuas no processo.

10. Integrantes

Mihari Barbosa da Silva

Athur Antunes de Oliveira

Aline Eduarda Morais de Rezende

11. Ferramenta utilizada

Trello – utilizado para criação e gerenciamento do quadro Kanban e para acompanhamento visual das atividades durante a simulação.

12. Disciplina

Metodologias Ágeis

13. Quadro Kanban

O quadro utilizado durante o desenvolvimento e a simulação pode ser acessado pelo link abaixo:

{"fallbackMarkdown":"Visualizar quadro Kanban no Trello","reference":{"matched_text":"","prefix":null,"start_idx":10184,"end_idx":10350,"safe_urls":[],"refs":[],"alt":"Visualizar quadro Kanban no Trello","prompt_text":"Visualizar quadro Kanban no Trello","type":"url","logo":null,"item":{"title":"Visualizar quadro Kanban no Trello","url":"https://trello.com/invite/b/6aa09bec58dfa42e9b222268/ATTIcc0477c53dec754df4a4707301ddfbc7079621AC/sistema-de-reservas-pousada?utm_source=chatgpt.com","attribution":"trello.com","pub_date":null,"snippet":null,"attribution_segments":null,"supporting_websites":null,"refs":[],"hue":null,"attributions":null},"layout":null,"title":"Visualizar quadro Kanban no Trello"},"showLoginRequiredCard":false}
