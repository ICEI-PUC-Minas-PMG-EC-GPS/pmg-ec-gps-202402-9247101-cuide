# Iniciação

> A fase de iniciação, em gerência de projetos, é o estágio que estabelece as bases para o sucesso do empreendimento. 
> Durante essa etapa, os objetivos definidos, identificando-se suas metas, escopo, partes interessadas (*stakeholders*) e restrições. 
> É o momento em que a viabilidade do projeto é avaliada, analisando-se recursos necessários, riscos potenciais e benefícios esperados.
> Nesta etapa é elaborado o Termo de Abertura do Projeto (TAP).
> Essa fase serve como um alicerce estratégico, proporcionando uma compreensão abrangente do que o projeto busca alcançar e delineando as diretrizes que orientarão as etapas subsequentes. 
> O sucesso na fase de iniciação contribui significativamente para a eficácia do gerenciamento de projetos como um todo.

# Estrutura do Documento

- [Fase de Iniciação](#iniciação)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Critérios de Sucessos](#critérios-de-sucesso)
- [Partes Interessadas](#partes-interessadas)
  - [Identificação das Partes Interessadas](#identificação-das-partes-interessadas)
  - [Avaliação das Partes Interessadas](#avaliação-das-partes-interessadas)
- [Termo de Abertura do Projeto](#termo-de-abertura-do-projeto)
  - [Estimativa de Custo](#estimativa-de-custo)
  - [Estimativa de Prazo](#estimativa-de-prazo)
  - [Escopo Preliminar e Premissas](#escopo-preliminar-e-premissas)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos Não Funcionais](#requisitos-não-funcionais)
    - [Restrições](#restrições)
    - [Contra-Escopo](#contra-escopo)
    - [Condições para início do Projeto](#condições-para-início-do-projeto)
  - [Marcos Agendados e Entregas](#marcos-agendados-e-entregas)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)

# Introdução

```diff
+ Tarefa 01:
+ Tema do projeto e lista de Stakeholders
```

## Problema

O envelhecimento é uma realidade crescente, que resulta em um aumento significativo que números de pessoas idosas, assim aumentando o nível de cuidados especiais. No entanto, o cenário acaba colocando uma pressão maior sobre os cuidadores, em que, muitas vezes são familiares ou profissionais de saúde sem treinamento adequado ou recursos suficientes para lidar com a complexidade das necessidades dos idosos. Diante disso, sabe-se que esses profissionais enfrentam uma série de desafio contínuos, sendo como principal a falta de importantes  informações precisas e acessíveis sobre os cuidados geriátricos, com isso gera uma dificuldade maior na gestão de rotinas, tratamentos e o isolamento emocional decorrente da intensa carga de trabalho.

A carga colocada em cima dos cuidadores, e a falta de um suporte emocional, pode acabar gerando um declínio na qualidade dos cuidados prestados, afetando diretamente o bem-estar dos idosos. Visto que, a ausência de uma plataforma centralizada e integrada que ofereça suporte abrangente e acessível a esses cuidadores representa uma lacuna crítica no sistema de saúde e bem-estar.

Desee modo, a falta de um sistema de apoio estruturado e eficiente não só compromete a qualidade de vida dos idosos, mas também coloca em risco a saúde física e mental dos próprios cuidadores, que muitas vezes trabalham em condições extremas e sem o reconhecimento ou apoio adequado.

> Problem corresponde a uma lacuna a ser preenchida, uma necessidade a ser atendida, ou uma dificuldade a ser superada.
> A definição precisa do problema ajuda a orientar as atividades do projeto, direcionando os esforços em sua solução.
> Seu entendimento facilita a comunicação eficaz entre os membros da equipe e as partes interessadas, estabelecendo uma base comum para a colaboração.
> Nesta seção, deve ser descrito apenas o problema e seu contexto.
> Soluções para o problema devem ser descritas na seção correspondente.

## Objetivos

Objetivo Geral

Aprimorar a qualidade de vida de cuidadores e idosos, através de uma plataforma de monitoramento dos sinais vitais.

Objetivos Específicos

-Gerenciamento de calendário e lista de tarefas relacionados ao idoso com relatórios de saúde e lembretes de aviso.

-Suporte online com especialistas e cuidadores experientes.

-Dispositivo que monitora sinais vitais integrado ao sistema que emite alerta em situações criticas.

> Aqui você deve descrever os objetivos do trabalho.
> Apresente um Objetivo Geral, sintetizado em uma única frase.
> Apresente também 3 ou 4 objetivos específicos (sub-produtos do sistema ou objetivos extras que podem ser alcançados pela construção do software).
> 
> **Link Útil**:
> - [Objetivo geral e objetivo específico: como fazer e quais verbos utilizar](https://blog.mettzer.com/diferenca-entre-objetivo-geral-e-objetivo-especifico/)


## Justificativa

O projeto CUIDE: Plataforma de Apoio para Cuidadores de Idosos foi desenvolvido com o objetivo de oferecer suporte aos cuidadores e familiares, que muitas vezes enfrentam desafios significativos em suas tarefas diárias. A plataforma aborda uma demanda crescente por soluções que melhorem a qualidade dos cuidados oferecidos aos idosos, bem como a qualidade de vida dos próprios cuidadores.

Com a população idosa em crescimento, há uma necessidade cada vez maior de ferramentas que ajudem a gerir de forma eficiente e humanizada os cuidados necessários. O CUIDE foi projetado para atender a essa necessidade específica, fornecendo uma solução que integra recursos informativos, ferramentas de gestão e suporte emocional em um único lugar.

Os benefícios esperados com a construção do CUIDE incluem:

- **Melhoria na qualidade de vida dos cuidadores e idosos:** A plataforma oferece recursos que facilitam o gerenciamento dos cuidados, reduzindo o estresse e promovendo o bem-estar dos envolvidos.
- **Eficiência na gestão de cuidados:** Com ferramentas como calendário de cuidados e relatórios de saúde, os cuidadores poderão organizar melhor suas tarefas, garantindo que nada seja esquecido.
- **Acesso a informações essenciais:** A biblioteca de conteúdo e os guias detalhados permitem que os cuidadores tenham acesso rápido a informações cruciais sobre procedimentos e melhores práticas no cuidado de idosos.
O impacto previsto do CUIDE é significativo, tanto para os cuidadores profissionais quanto para os familiares, promovendo uma experiência mais satisfatória e eficiente na prestação de cuidados, o que, por sua vez, refletirá em uma melhor qualidade de vida para os idosos sob seus cuidados.
- **Integração com sistemas embarcados:** A integração com a pulseira de monitoramento de sinais vitais oferece uma camada extra de segurança, alertando os cuidadores imediatamente em caso de irregularidades na saúde do idoso, sem a necessidade de internet ou IoT.

<br>
> Aqui você deve descrever os benefícios esperados pela construção do projeto.
> As justificativas do projeto explicam as razões e a necessidade da iniciativa.
> Elas demonstram como o projeto atende a uma demanda específica, resolve um problema ou aproveita uma oportunidade identificada.
> Além disso, definem os benefícios esperados e o impacto previsto para a organização ou a comunidade. 

## Critérios de Sucesso

Entrega bem sucedida e feita nos parâmetros corretos, em todas as sprints, de maneira bem distribuída e organizada.

Trabalhar e desenvolver habilidades gerenciais dos alunos ao participar da implantação de projetos nos mais diversos âmbitos do mercado, trabalhando conforme as devidas metodologias.

Priorização da privacidade e segurança dos dados dos usuários conforme LGPD.

Número de usuários ativos diários/mensais, e leads satisfatórios de tempo médio gasto na plataforma
Índice de satisfação dos usuário.

Redução no estresse reportado pelos cuidadores de idosos, que geralmente são invisibilizados.

Melhoria na qualidade de vida dos idosos (baseado em pesquisas), trazendo inovação, e abordando a importância da tecnologia na vida da população Sênior.

Desenvolver um trabalho que visa além da parte de software/hardware, a parte humanizada, os usuários que o utilizam, e o bem estar dos mesmos.

> Os critérios de sucesso indicam uma forma avaliar o êxito do trabalho e analisar se o projeto realmente alcançou os objetivos estabelecidos. 
> Esses critérios geralmente abrangem diversas dimensões, incluindo a entrega dentro do prazo e orçamento estipulados, a satisfação do cliente, a qualidade do produto ou serviço final, e a eficiência na utilização de recursos. 
> Além disso, a capacidade de atender aos requisitos e expectativas das partes interessadas, bem como a gestão eficaz de riscos, são considerados aspectos importantes para determinar o sucesso de um projeto. 

# Partes Interessadas

> Relacione as partes interessadas no seu projeto. 
> Você deve descrever as partes interessadas e indicar qual o nível de influência em relação ao projeto.
> Indique as principais pessoas (clientes, fornecedores, etc), indicando possíveis expectativas, nível de influência e possível importância para o sucesso do projeto.

> Você pode utilizar como referência o seguinte documento:
> [Registro de Partes Interessadas](artefatos/registro-partes-interessadas.xlsx)

## Identificação das Partes Interessadas

| Nome            | Posição / Cargo | Papel Projeto | E-mail      | Telefone    |
|-----------------|-----------------|---------------|-------------|-------------|
|  Nalanda Santos       |    Gerente de TI             |    Patrocinadora do Projeto           |     nalanda.santos@empresa.com       |      	+55 (31) 99999-1234       |
|      João Silva	 |      Funcionário da Linha de Produção	           |    Testador de Usabilidade	           |     joao.silva@empresa.com	        |      +55 (31) 98888-2345 |
|    Carla Santos	     |   Presidente	  |     Decisora Estratégica	          |   carla.santos@empresa.com	     |     +55 (31) 97777-3456        |
|      Lucas Almeida	     |       Analista de Sistema do Cliente	    |Facilitador de Integração	  |    lucas.almeida@cliente.com	         |   +55 (31) 96666-4567 |
|   Sabrina Helena	        |     Desenvolvedora            |   Desenvolvedora Back-End	            |  sabrina.helena@empresa.com	           |    +55 (31) 95555-5678 |
|   Victoria Barbosa	      |     Desenvolvedora	    |   Desenvolvedora Front-End	   |       victoria.barbosa@empresa.com	      |    +55 (31) 94444-6789       |
|   Willian Martins |  Analista de Requisitos    |     Definição de Funcionalidades	  |  willian.martins@empresa.com	  |    +55 (31) 93333-7890 |
|  Ricardo Ferreira	|  Analista de Testes	  | Validação e Qualidade	  | ricardo.ferreira@empresa.com	  |  +55 (31) 92222-8901 |
|  Instituições de Saúde	| Parceiros	  | Colaboradores e Usuários	  | contato@instituicao.com		  | +55 (31) 91111-9012 |
|  Associações de Cuidadores		| Parceiros	  | Colaboradores e Usuários	  | contato@associacao.com	| +55 (31) 91211-9012 |
| Cuidadores Profissionais		| Usuários		  | Usuários Finais		  | -- | -- |
| Idosos e Familiares		| Usuários		  | Usuários Finais		  | -- | -- |

> Opções de identificação dos stakeholders:
> - Nome: nome da parte interessada (inclui funcionários da empresa e do cliente)
> - Posição / Cargo: Identificação do cargo da parte interessada
> - - Ex.: Gerente de TI, Funcionário da Linha de Produção, Presidente, Analista de Sistema do Cliente, Desenvolvedor, etc.
> - Papel no Projeto: Papel da pessoa no projeto
> - - Ex.: Desenvolvedor, Analista de Requisitos, Analista de Testes, Product Owner, etc.
> - E-mail: E-mail do Stakeholder (*não utilizar informações pessoais*)
> - Telefone: Telefone do Stakeholder, incluindo WhatsApp (*não utilizar informações pessoais*)

## Avaliação das Partes Interessadas

| Nome            | Expectativa no Projeto | Influência    | Importância / Poder | Apoio       | Observações   |
|-----------------|------------------------|---------------|---------------------|-------------|---------------|
|  Nalanda Santos       |   Sucesso geral do projeto e ROI	 | Alta	  |Alta	 |    Positivo	     | Controle financeiro |
|      João Silva	 |   Facilidade de uso no ambiente de produção	 |  Média	   | Média    |    Neutro| Feedback sobre UX |
|    Carla Santos	     | Impacto positivo na imagem corporativa	 |  Alta	   |  Alta	 |  Positivo	      | Decisões estratégicas |
|      Lucas Almeida	     | Integração eficaz com os sistemas do cliente	| Alta	  |  Alta    |  Positivo	 | Coordena a integração |
|   Sabrina Helena	        | Implementação de um back-end robusto	  | Média    | Alta    | Positivo | Coordena a arquitetura |
|   Victoria Barbosa	      |     Interface de usuário moderna e responsiva		    | Média |  Alta	   |  Positivo    | Design da interface |
|   Willian Martins |  Definição clara dos requisitos do sistema	 | Alta	 | Alta	  |  Positivo	| Acompanhamento de demandas |
|  Ricardo Ferreira	|  Garantia de qualidade e ausência de bugs	 | Alta | Alta	  | Positivo |Testes e validação |
|  Instituições de Saúde	| Integração fácil e rápida com a plataforma	 | Média	 | Média		  | Positivo	 | Colaboram com integração |
|  Associações de Cuidadores		| Suporte contínuo e troca de experiências	| Média	 | Média		| Positivo | Ajudam na disseminação |
| Cuidadores Profissionais		|  Ferramentas de gestão e suporte emocional	  |  Alta		  | Alta	| Positivo | Expectativas variáveis |
| Idosos e Familiares		| Melhoria na qualidade de vida e bem-estar	  | Alta	  | Alta	| Positivo|  Expectativas variáveis |

> Opções de avaliação:
> - Expectativa: descrição da expectativa da parte interessada no projeto.
> - - Ex.: Diminuição do tempo de realização das tarefas, aumento da produtividade, aumento da satisfação do cliente, etc.
> - Influência: Alta, Média, Baixa
> - Importância: Alta, Média, Baixa
> - Apoio: Positivo, Negativo, Neutro
> - Observações: Informações adicionais, para o cliente.

```diff
+ Tarefa 01
+ Fim da seção a ser atualizada.
```


-----
```diff
+ Tarefa 02
+ Termo de Abertura do Projeto
```

# Termo de Abertura do Projeto

> O Termo de Abertura do Projeto (TAP) representa o ponto de partida oficial para o empreendimento. 
> Ele sintetiza de maneira clara e concisa os objetivos, escopo, partes interessadas envolvidas, entregas esperadas, cronograma preliminar e recursos necessários para a execução bem-sucedida do projeto. 
> O TAP funciona como um contrato inicial entre a equipe do projeto e as partes interessadas, estabelecendo as bases para uma compreensão compartilhada dos propósitos e limites do projeto. 
> Ao delinear esses elementos de forma detalhada, o Termo de Abertura do Projeto (TAP) fornece uma direção sólida para orientar as atividades subsequentes, facilitando a gestão eficaz do projeto desde o início até o encerramento. 
> Essa documentação garante a clareza, alinhamento e comprometimento de todos os envolvidos, contribuindo assim para o sucesso do projeto.

> Você pode utilizar como referência o seguinte documento:
> [Termo de Abertura do Projeto](artefatos/termo-abertura-projeto.docx)

## Estimativa de Custo

O CUIDE custará inicialmente R$ 295.000,00 e abrangerá as seguintes áreas: Recursos humanos, hardware, serviços de rede, hospedagem em nuvem, software de terceiros, treinamento, publicidade, conformidade, suporte e atendimento ao cliente, desenvolvimento futuro planejado, contingência e reserva de emergência. A maioria dos custos diz respeito ao desenvolvimento da plataforma e à aquisição de serviços e equipamentos para assegurar uma operação segura e eficiente.

Outras despesas operacionais anuais, além dos iniciais, são o suporte técnico, treinamento contínuo e manutenção da plataforma que totalizam aproximadamente R$ 18.000,00. Como receitas de assinaturas e parcerias devem cobrir esses custos e fornecer um retorno financeiro positivo, esses números já indicam a justificação financeira e razoabilidade do projeto e a capacidade de proporcionar grandes benefícios para os usuários.

Projeções Financeiras e Análise
Investimentos Iniciais: O desenvolvimento e lançamento inicial da plataforma CUIDE devem custar aproximadamente R$ 295.000,00.

Despesas Operacionais:

Manutenção e Atualizações: R$ 10.000,00 anuais.
Custos com Suporte e Treinamento: R$ 8.000,00 anuais.
Receitas Esperadas:

Assinaturas e Licenças: Projeção inicial de R$ 500.000,00 anuais.
Parcerias e Publicidade: R$ 50.000,00 anuais.

Economias de Custos e Ganhos Intangíveis:

Redução do Estresse dos Cuidadores: aumenta a satisfação dos usuários e diminui a rotatividade.

Melhoria na Qualidade de Vida dos Idosos: Beneficios para a saúde e o bem-estar.

Métricas Econômicas:

Valor Presente Líquido (VPL): O VPL pode ser calculado usando receitas esperadas, custos de manutenção e investimento inicial. Supondo uma taxa de desconto de 10%, a viabilidade econômica seria avaliada ao longo de cinco anos.

Taxa Interna de Retorno (TIR): A taxa de retorno percentual esperada de um investimento é determinada pelo cálculo da TIR. Deve ser comparado com a taxa de retorno exigida para avaliar se o projeto é atraente.

Conclusões finais:

A análise econômica mostra que, com base nas estimativas de receitas e custos, o CUIDE apresenta uma boa visão de viabilidade financeira. No entanto, para garantir a sustentabilidade e o sucesso a longo prazo, a avaliação contínua será necessária por meio de métricas financeiras e comentários dos usuários.

> A avaliação da viabilidade econômica busca determinar a sustentabilidade financeira e o retorno sobre o investimento do empreendimento. 
> Este processo envolve a análise dos custos associados ao projeto, incluindo investimentos iniciais, despesas operacionais e potenciais custos de manutenção. 
> Simultaneamente, são examinados os benefícios esperados, como receitas, economias de custos e ganhos tangíveis e intangíveis. 
> A elaboração de projeções financeiras realistas e a aplicação de métricas como o Valor Presente Líquido (VPL) e a Taxa Interna de Retorno (TIR) contribuem para uma avaliação abrangente da viabilidade econômica do projeto. 
> Este processo permite que os gestores de projeto e as partes interessadas tomem decisões informadas sobre a continuidade, ajustes ou mesmo a interrupção do projeto, garantindo uma alocação eficiente de recursos e maximizando os benefícios econômicos esperados.

......  ATUALIZE OS ITENS DE CUSTO DO SISTEMA. ADICIONE NOVOS OU SUBDIVIDA ITENS, CASO NECESSÁRIO ......

| Item de Custo           | Descrição | Qtd. horas | Valor / hora | Valor total |
|-------------------------|-----------|------------|--------------|-------------|
| Recursos Humanos        |    Desenvolvimento de software, design, teste, suporte e gestão de projeto.       |      1.500 horas      |       R$ 100,00	       |       R$ 150.000,00       |
| Hardware                |     Servidores, dispositivos de monitoramento e equipamentos.	      |      -      |       -       |      R$ 50.000,00       |
| Serviços de Rede        |     Infraestrutura de rede e internet.	      |      -      |       -       |      R$ 10.000,00       |
| Hospedagem e Nuvem      |     Servidores em nuvem e hospedagem.	      |      -      |       -       |       R$ 20.000,00       |
| Software de terceiros   |     Licenças e APIs necessárias.	      |      -      |       -       |      R$ 15.000,00       |
| Serviços e treinamento  |     Treinamento para usuários e suporte técnico.	      |      100 horas	      |      R$ 80,00	        |      R$ 8.000,00       |
| Marketing e Divulgação	  |      Campanhas publicitárias e materiais promocionais.	     |      -      |       -       |      R$ 30.000,00       |
| Licenças e Conformidade	  |     Custos com regulamentações e certificações.	      |      -      |        -      |      R$ 5.000,00       |
| Suporte ao Cliente e Atendimento	  |      Equipe e ferramentas de suporte ao cliente.	     |      -      |        -      |      R$ 12.000,00       |
| Desenvolvimento Futuramente Planejado	  |     Recursos para atualizações e novos recursos.	      |      -      |       -       |      R$ 20.000,00       |
| Contingência e Reserva de Emergência  |     Reserva para imprevistos e emergências.	      |      -      |       -       |      R$ 15.000,00       |
| **Total Geral**         |     -      |      -      |       -       |      R$ 295.000,00       |


## Estimativa de Prazo

### 1. Planejamento e Análise de Requisitos
- **Descrição:** Definição dos requisitos do projeto, análise de viabilidade e planejamento geral
- **Horas Previstas:** 80 horas
- **Duração:** 1 semana

### 2. Design e Prototipagem
- **Descrição:** Criação do design da interface, protótipos e revisões
- **Horas Previstas:** 160 horas
- **Duração:** 2 semanas

### 3. Desenvolvimento
- **Descrição:** Codificação do software, integração de sistemas e desenvolvimento de funcionalidades
- **Horas Previstas:** 640 horas
- **Duração:** 6 semanas

### 4. Testes e QA
- **Descrição:** Testes de funcionalidade, usabilidade e segurança, correção de bugs
- **Horas Previstas:** 160 horas
- **Duração:** 2 semanas

### 5. Implantação e Treinamento
- **Descrição:** Lançamento da plataforma, treinamento de usuários e suporte inicial
- **Horas Previstas:** 80 horas
- **Duração:** 1 semana

### 6. Suporte Pós-Lançamento e Manutenção Inicial
- **Descrição:** Suporte técnico, resolução de problemas iniciais e manutenção
- **Horas Previstas:** 80 horas
- **Duração:** 1 semana

### Resumo do Projeto
- **Total de Horas Previstas:** 1.200 horas
- **Duração Total do Projeto:** Aproximadamente 13 semanas
> A estimativa de prazo orienta tanto o cliente quanto a equipe de desenvolvimento do projeto em termos do tempo necessário para a conclusão do projeto como um todo. 
> Esta estimativa possibilita a criação de um cronograma realista e viável, permitindo o planejamento adequado das fases do projeto, alocação de recursos de maneira eficiente e antecipação de eventuais desafios.
> Uma estimativa precisa orienta a execução do projeto, contribui para a gestão de expectativas e para o estabelecimento de metas alcançáveis.

> Indique:
> * Prazo previsto (em horas) 
> * Data de início
> * Data de término

* Prazo previsto (em horas): 1200 horas
* Data de início: 29 / 08 / 2024
* Data de término: 28 / 11 / 2024

## Escopo Preliminar e Premissas

> Os requisitos preliminares fornecem uma visão inicial do escopo, funcionalidades-chave e as expectativas a serem atendidas. 
> 
> ***A quantidade mínima de requisitos a serem preenchidos nas seções abaixo não incluem os exemplos previamente fornecidos.***

## Declaração de Escopo

> Você pode utilizar como referência o seguinte documento:
- [Declaração de Escopo](artefatos/declaracao-escopo.docx)

> Enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.
> 
> **Links Úteis**:
> 
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


### Requisitos Funcionais

A tabela a seguir apresenta os requisitos funcionais do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-------------------------------------------------------------|-------|
|RF-001| Permitir o cadastro  de tarefas                             |	ALTA |
|RF-002| Emitir um relatório de tarefas do mês	                     | MÉDIA |
|RF-003|  Emitir relatórios de suporte à saúde do idoso com base nos dados capturados pelo sistema embarcado  | ALTA  |
|RF-004| Monitorar sinais vitais em tempo real através do sistema embarcado   | ALTA  |
|RF-005| Registrar e exibir o histórico de sinais vitais monitorados para consulta  | ALTA  |
|RF-006| Emitir alertas sonoros quando os sinais vitais estiverem fora dos limites estabelecidos | ALTA  |
|RF-007| Gerar relatórios periódicos de saúde com os dados capturados pelo sistema embarcado  | MÉDIA |
|RF-008| Exportar lista de tarefas e relatórios de saúde para formatos PDF e Excel   | BAIXA |
|RF-009| Permitir contato direcionado para operado de saúde parceira | BAIXA |
|RF-010| Permitir cadastro e login de usuários	                     | ALTA  |
|RF-011| Registrar histórico de alterações em tarefas	               | MÉDIA |
|RF-012| Permitir conexões simultâneas                               | ALTA  |
|RF-013| Permitir alertar de sinais vitais para os usuários          | ALTA  |

### Requisitos Não Funcionais


A tabela a seguir apresenta os requisitos não funcionais do projeto. 

|ID     | Descrição do Requisito                                             |Prioridade |
|-------|--------------------------------------------------------------------|-----------|
|RNF-001| O sistema terá portabilidade para rodar em um dispositivos móveis  | MÉDIA     | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s              | BAIXA     | 
|RNF-003| Deve seguir as normas lgpd priorizando segurança dos dados         | ALTA      | 
|RNF-004| Precisa ser atualizado frequentemente para se adaptar a novos s.o's| MÉDIA     | 
|RNF-005| Deve seguir as normas lgpd priorizando segurança dos dados         | ALTA      |
|RNF-006| Deve ter equipe de analistas da saúde atualizada conforme feedbacks| ALTA      |

### Restrições

A tabela a seguir apresenta as restrições do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RE-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RE-002| Emitir os relatórios de saúde              | MÉDIA |
|RE-003| Integrar com dispositivos de monitoramento da saúde | ALTA | 
|RE-004| Permitir comunicação com mentores          | MÉDIA |
|RE-005| Permitir postagens e leituras nos fóruns de dúvidas | BAIXA | 
|RE-006| Exibir e sincronizar o calendário de atividades       | ALTA |


### Contra-Escopo

......  ATUALIZE O CONTRA-ESCOPO DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as atividades que não serão executadas no projeto

| ID    | Descrição do Contra-Escopo                                  |  
|-------|-------------------------------------------------------------|  
| CE-001| Treinamento de modelo de LLM                                |  
| CE-002| Estudo de acessibilidade do mercado                         |  
| CE-003| Agendamentos de consultas\exames                            |  
| CE-004| Personalização avançada de relatórios por usuário           |  
| CE-005| Avaliação médica ou diagnóstico                             |  
| CE-006| Suporte técnico 24/7 para usuários finais                   |  
| CE-007| Criação de documentação técnica                             |  
| CE-008| Implementação de criptografia ponta a ponta para comunicações |  


### Condições para início do Projeto

A tabela a seguir, apresente as condições para que o projeto seja iniciado.

|ID    | Descrição de Condições para Início do Projeto    | 
|------|--------------------------------------------------|
|CI-001| Assinatura de contrato de prestação de serviços. |
|CI-002| Apresentação de garantias definidas no contrato. |
|CI-003| Aprovação do plano de projeto pela equipe de gestão e partes interessadas. |
|CI-004| Realização de um levantamento, uma pesquisa, com cuidadores, profissionais de saúde e familiares para definir as funcionalidades mais importantes (prioridades). |
|CI-005| Estabelecimento de parcerias com instituições de saúde para suporte no desenvolvimento e propagação da plataforma, e investimento |
|CI-006| Desenvolvimento e aprovação do escopo preliminar, incluindo a identificação de requisitos funcionais e não funcionais, restrições e contra-escopo. |
|CI-007| Aprovação do orçamento preliminar e cronograma, alinhado com as expectativas das partes interessadas e as metas do projeto. |
|CI-008| Identificação e mapeamento das partes interessadas, com uma avaliação de suas expectativas e influência no projeto. |
|CI-009| Aquisição dos componentes e montagem do hardware (pulseira) para captura dos sinais vitais dos idosos, garantindo a funcionalidade antes do desenvolvimento do aplicativo. |


## Marcos Agendados e Entregas

......  ATUALIZE OS MARCOS AGENDADOS DO PROJETO E AS DATAS PARA ENTREGAS DAS TAREFAS ......

A tabela a seguir, identifique os marcos do projeto e os entregáveis previstos (requisitos).

|ID   | Marco do Projeto                                                  | Data         | 
|-----|-------------------------------------------------------------------|--------------|
|M-1  | Liberação do sistema para cadastro de informações e configuração. | 05/09/2024	 |
|M-2  | Permissão para uso do sistema, por usuários focais.               | 12/09/2024	 |
|M-3  | Finalização da fase de Design e Prototipagem                      | 19/09/2024	 |
|M-4  | Conclusão da primeira versão funcional do software	              | 17/10/2024	 |
|M-5  | Teste Beta 1 para cuidadores	                                    | 24/10/2024	 |
|M-6  | Revisão dos problemas identificados no Teste Beta 1	              | 31/10/2024	 |
|M-7  | Teste Beta 2 para idosos	                                        | 07/11/2024	 |
|M-8  | Revisão dos problemas identificados no Teste Beta 2	              | 14/11/2024	 |
|M-9  | Testes e Qualidade Assegurada (QA) concluídos	                    | 21/11/2024	 |
|M-10  | Lançamento final da plataforma                                    | 28/11/2024	 |
|M-11  | Suporte pós-lançamento e manutenção inicial concluídos	          | 05/12/2024	 |

```diff
+ Tarefa 02
+ Fim da seção a ser atualizada.
```

-----
```diff
+ Tarefa 03:
+ Metodologia do Projeto
```

# Metodologia

Para garantir a eficácia no desenvolvimento e implementação da plataforma CUIDE, adotaremos a metodologia ágil, utilizando o framework Scrum e o sistema Kanban para gerenciar as tarefas e o fluxo de trabalho. Este documento detalha o processo de trabalho baseado em Scrum, a divisão de papéis e tarefas, e o uso do Kanban e ferramentas associadas.

1. Framework Scrum
Scrum é uma abordagem ágil que organiza o trabalho em ciclos iterativos chamados sprints. Cada sprint é uma iteração que dura normalmente de 2 a 4 semanas, durante a qual uma parte funcional do projeto é desenvolvida e entregue. O objetivo é entregar valor continuamente e permitir ajustes conforme o projeto avança.

Principais Papéis no Scrum:

Product Owner (PO): Responsável por definir a visão do produto, priorizar o backlog e garantir que a equipe entenda os requisitos e objetivos. O PO também atua como o ponto de contato principal com as partes interessadas e valida os entregáveis.

Scrum Master: Facilita o processo Scrum, remove impedimentos e garante que a equipe siga as práticas ágeis. O Scrum Master ajuda a manter o time focado e produtivo, promovendo a melhoria contínua.

Equipe de Desenvolvimento: Responsável por criar o produto conforme as especificações do backlog. A equipe é autônoma e multifuncional, composta por desenvolvedores, designers, e outros especialistas necessários.

Cerimônias Scrum:

Planejamento do Sprint: Reunião no início de cada sprint para definir o que será entregue e como o trabalho será realizado. O PO apresenta o backlog priorizado, e a equipe decide quais itens podem ser concluídos no próximo sprint.

Daily Stand-up: Reuniões diárias de 15 minutos para a equipe sincronizar atividades, discutir o progresso e identificar impedimentos.

Revisão do Sprint: Reunião ao final de cada sprint para demonstrar o trabalho concluído e obter feedback dos stakeholders.

Retrospectiva do Sprint: Reunião após a revisão do sprint para refletir sobre o que funcionou bem e o que pode ser melhorado, visando ajustar processos e práticas para o próximo sprint.

2. Implementação do Kanban
Kanban é uma técnica visual de gerenciamento de fluxo de trabalho que ajuda a visualizar, gerenciar e otimizar o trabalho em andamento. Utilizaremos o Kanban para gerenciar e monitorar o progresso das tarefas em cada sprint.

Estrutura do Quadro Kanban:

Backlog: Lista de todas as tarefas e requisitos do projeto que ainda não foram iniciados. O backlog é constantemente atualizado e priorizado pelo Product Owner.

A Fazer: Tarefas que estão prontas para serem iniciadas no próximo sprint. Estas tarefas são selecionadas durante a reunião de planejamento do sprint.

Em Andamento: Tarefas que estão atualmente sendo trabalhadas pela equipe. Cada tarefa é movida para esta coluna assim que a equipe começa a trabalhar nela.

Em Revisão: Tarefas que foram concluídas e estão aguardando revisão ou validação. Esta etapa assegura que o trabalho atende aos critérios de aceitação e padrões de qualidade.

Concluído: Tarefas que foram totalmente concluídas e aceitas. Uma vez que uma tarefa passa por todas as fases de revisão, ela é movida para esta coluna.

Ferramentas Kanban:

GitHub Projects: Utilizaremos o GitHub Projects para criar e gerenciar nosso quadro Kanban. A plataforma permite que as tarefas sejam visualizadas e organizadas em colunas e também fornece recursos para rastrear o progresso e o status das tarefas.

Trello/Jira: Alternativamente, Trello ou Jira podem ser usados, caso o GitHub Projects não atenda todas as necessidades. Ambas as ferramentas oferecem funcionalidades semelhantes para criar quadros Kanban e gerenciar fluxos de trabalho.

Processo de Trabalho
Planejamento Inicial:

Período: 29/08/2024 - 04/09/2024
Descrição: Durante esta fase, o Product Owner definirá o backlog inicial com todos os requisitos e funcionalidades desejadas para a plataforma CUIDE. Este backlog será detalhado e priorizado, e a equipe fará a organização para o primeiro sprint. As reuniões de planejamento garantirão que todos os requisitos estejam claramente definidos e que o plano de desenvolvimento esteja alinhado com os objetivos do projeto.
Desenvolvimento dos Sprints:

Período: 19/09/2024 - 30/10/2024

Descrição: O desenvolvimento será dividido em três sprints:

Sprint 1: 19/09/2024 - 02/10/2024
Sprint 2: 03/10/2024 - 16/10/2024
Sprint 3: 17/10/2024 - 30/10/2024
Durante cada sprint, a equipe se concentrará nas tarefas selecionadas da coluna "A Fazer". O progresso será monitorado através do quadro Kanban, e reuniões diárias de stand-up serão realizadas para discutir o status das tarefas, identificar e resolver impedimentos. A equipe de desenvolvimento também realizará reuniões de revisão de sprint para demonstrar o trabalho concluído e receber feedback.

Revisão e Ajustes:

Período: 31/10/2024 - 13/11/2024
Descrição: Após o desenvolvimento, a fase de testes e QA será conduzida. Esta fase inclui testes de funcionalidade, usabilidade e segurança, além da correção de bugs. A equipe realizará testes beta e fará ajustes conforme necessário para garantir que o produto final atenda aos critérios de qualidade e esteja pronto para o lançamento.
Lançamento e Pós-Lançamento:

Período: 14/11/2024 - 28/11/2024
Descrição: A implantação oficial da plataforma será realizada, incluindo o lançamento da plataforma ao público e o treinamento dos usuários. Após o lançamento, o suporte técnico inicial será fornecido para resolver quaisquer problemas emergentes. O feedback dos usuários será coletado e analisado para planejar melhorias contínuas e ajustes na plataforma, assegurando que as necessidades dos usuários sejam atendidas e o produto continue a evoluir de acordo com as expectativas.

Divisão de Papéis e Tarefas
Product Owner: Define o backlog e prioriza as tarefas; gerencia o feedback dos stakeholders.
Scrum Master: Facilita as cerimônias Scrum, remove impedimentos e ajuda a equipe a seguir as práticas ágeis.
Equipe de Desenvolvimento: Trabalha nas tarefas do backlog, realizando desenvolvimento, design e testes conforme necessário.
Utilizando o framework Scrum e a técnica Kanban, o CUIDE visa garantir um desenvolvimento eficiente e ágil da plataforma, promovendo a entrega contínua de valor e melhorias baseadas no feedback dos usuários.

> Nesta parte do documento, você deve apresentar a metodologia adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, a divisão de papéis e tarefas e as ferramentas empregadas.
>
> Coloque detalhes sobre o processo utilizado e a implementação do Framework Scrum seguido pelo grupo. 
> O grupo deverá gerenciar as tarefas utilizando o GitHub Project para acompanhar o andamento do projeto, a execução das tarefas e o status de desenvolvimento da solução.
> 
> **Links Úteis**:
> - [Github Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/creating-a-project)
> - [O que é o GitHub Projects? | Guia de Iniciantes](https://www.youtube.com/watch?v=vxYTpsFKdiQ&ab_channel=JulioArruda)
> - [Introduction to GitHub Project Boards](https://www.youtube.com/watch?v=idZyqNIrt84&list=PLiO7XHcmTslc5hGrbnnmHIb0SeJLTpOEu&ab_channel=MickeyGousset)
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)

## Divisão de Papéis

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
> Indique as responsabilidades de cada membro do grupo no projeto.

......  COLOQUE AQUI O SEU TEXTO ......

## Ferramentas

> Liste as ferramentas empregadas no desenvolvimento do projeto, justificando a escolha delas, sempre que possível.
> Todas as ferramentas utilizadas devem ser listadas.
> Qualquer tipo de ferramenta que for utilizada para construção de um artefato deve ser identificada, uma vez que podem ser necessárias alterações.
> A necessidade de uso de licenças e possíveis custos relacionados devem ser indicados.

| Ambiente              | Plataforma         | Link de Acesso             | Justificativa |
|-----------------------|--------------------|----------------------------|---------------|
| Quadro Kanban         | Github             | https://github.com/XXXXXXX | Centralização e organização do projeto no próprio repositório. |
| Repositório de código | GitHub             | https://github.com/XXXXXXX |               |
| Protótipo Interativo  | Figma              | https://figma.com/XXXXXXX  |               |
| Documentos Textuais   | Word               | N/A                        |               |
| Planilhas e Gráficos  | Excel              | https://docs.google.com/   |               |
| EAP / WBS             | | | |
| Cronograma do Projeto | | | |
| Matriz RACI           | | | |

```diff
+ Tarefa 03:
+ Fim da seção a ser atualizada.
```

----
