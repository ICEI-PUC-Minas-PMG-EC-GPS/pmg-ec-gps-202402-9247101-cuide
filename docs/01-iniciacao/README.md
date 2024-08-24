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

Sabemos que o envelhecimento é uma realidade crescente, no qual, resulta em um aumento significativo que números de pessoas idosas, assim aumentando o nível de cuidados especiais. No entanto, o cenário acaba colocando uma pressão maior sobre os cuidadores, em que, muitas vezes são familiares ou profissionais de saúde sem treinamento adequado ou recursos suficientes para lidar com a complexidade das necessidades dos idosos. Diante disso, sabe-se que esses profissionais enfrentam uma série de desafio contínuos, sendo como principal a falta de importantes  informações precisas e acessíveis sobre os cuidados geriátricos, com isso gera uma dificuldade maior na gestão de rotinas, tratamentos e o isolamento emocional decorrente da intensa carga de trabalho.

A carga colocada em cima dos cuidadores, e a falta de um suporte emocional, pode acabar gerando um declínio na qualidade dos cuidados prestados, afetando diretamente o bem-estar dos idosos. Visto que, a ausência de uma plataforma centralizada e integrada que ofereça suporte abrangente e acessível a esses cuidadores representa uma lacuna crítica no sistema de saúde e bem-estar.

Este problema é ainda mais agravado pela fragmentação dos recursos disponíveis, que são sempre mais complicados de acessar, assim tornando o cuidado com os idosos um processo ainda mais desafiador. A falta de um sistema de apoio estruturado e eficiente não só compromete a qualidade de vida dos idosos, mas também coloca em risco a saúde física e mental dos próprios cuidadores, que muitas vezes trabalham em condições extremas e sem o reconhecimento ou apoio adequado.

> Problem corresponde a uma lacuna a ser preenchida, uma necessidade a ser atendida, ou uma dificuldade a ser superada.
> A definição precisa do problema ajuda a orientar as atividades do projeto, direcionando os esforços em sua solução.
> Seu entendimento facilita a comunicação eficaz entre os membros da equipe e as partes interessadas, estabelecendo uma base comum para a colaboração.
> Nesta seção, deve ser descrito apenas o problema e seu contexto.
> Soluções para o problema devem ser descritas na seção correspondente.

## Objetivos

Objetivo Geral

Aprimorar a qualidade de vida de cuidadores e idosos.

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
|  Ana Oliveira       |   Sucesso geral do projeto e ROI	 | Alta	  |Alta	 |    Positivo	     | Controle financeiro |
|      João Silva	 |   Facilidade de uso no ambiente de produção	 |  Média	   | Média    |    Neutro| Feedback sobre UX |
|    Carla Santos	     | Impacto positivo na imagem corporativa	 |  Alta	   |  Alta	 |  Positivo	      | Decisões estratégicas |
|      Lucas Almeida	     | Integração eficaz com os sistemas do cliente	| Alta	  |  Alta    |  Positivo	 | Coordena a integração |
|   Fernanda Costa	        | Implementação de um back-end robusto	  | Média    | Alta    | Positivo | Coordena a arquitetura |
|   Marcos Pereira	      |     Interface de usuário moderna e responsiva		    | Média |  Alta	   |  Positivo    | Design da interface |
|   Amanda Ribeiro |  Definição clara dos requisitos do sistema	 | Alta	 | Alta	  |  Positivo	| Acompanhamento de demandas |
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

......  COLOQUE AQUI O SEU TEXTO ......

> A avaliação da viabilidade econômica busca determinar a sustentabilidade financeira e o retorno sobre o investimento do empreendimento. 
> Este processo envolve a análise dos custos associados ao projeto, incluindo investimentos iniciais, despesas operacionais e potenciais custos de manutenção. 
> Simultaneamente, são examinados os benefícios esperados, como receitas, economias de custos e ganhos tangíveis e intangíveis. 
> A elaboração de projeções financeiras realistas e a aplicação de métricas como o Valor Presente Líquido (VPL) e a Taxa Interna de Retorno (TIR) contribuem para uma avaliação abrangente da viabilidade econômica do projeto. 
> Este processo permite que os gestores de projeto e as partes interessadas tomem decisões informadas sobre a continuidade, ajustes ou mesmo a interrupção do projeto, garantindo uma alocação eficiente de recursos e maximizando os benefícios econômicos esperados.

......  ATUALIZE OS ITENS DE CUSTO DO SISTEMA. ADICIONE NOVOS OU SUBDIVIDA ITENS, CASO NECESSÁRIO ......

| Item de Custo           | Descrição | Qtd. horas | Valor / hora | Valor total |
|-------------------------|-----------|------------|--------------|-------------|
| Recursos Humanos        |           |            |              |             |
| Hardware                |           |            |              |             |
| Serviços de Rede        |           |            |              |             |
| Hospedagem e Nuvem      |           |            |              |             |
| Software de terceiros   |           |            |              |             |
| Serviços e treinamento  |           |            |              |             |
| **Total Geral**         |           |            |              |             |


## Estimativa de Prazo

......  COLOQUE AQUI O SEU TEXTO ......

> A estimativa de prazo orienta tanto o cliente quanto a equipe de desenvolvimento do projeto em termos do tempo necessário para a conclusão do projeto como um todo. 
> Esta estimativa possibilita a criação de um cronograma realista e viável, permitindo o planejamento adequado das fases do projeto, alocação de recursos de maneira eficiente e antecipação de eventuais desafios.
> Uma estimativa precisa orienta a execução do projeto, contribui para a gestão de expectativas e para o estabelecimento de metas alcançáveis.

> Indique:
> * Prazo previsto (em horas) 
> * Data de início
> * Data de término

* Prazo previsto (em horas): XX horas
* Data de início: __ / __ / _____
* Data de término: __ / __ / _____

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

......  ATUALIZE OS REQUISITOS FUNCIONAIS DO SISTEMA (MÍNIMO 10) ......

A tabela a seguir apresenta os requisitos funcionais do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

### Requisitos Não Funcionais

......  ATUALIZE OS REQUISITOS NÃO FUNCIONAIS DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta os requisitos não funcionais do projeto. 

|ID     | Descrição do Requisito                                            |Prioridade |
|-------|-------------------------------------------------------------------|-----------|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA     | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s             | BAIXA     | 


### Restrições

......  ATUALIZE AS RESTRIÇÕES DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as restrições do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RE-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RE-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Contra-Escopo

......  ATUALIZE O CONTRA-ESCOPO DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as atividades que não serão executadas no projeto

|ID    | Descrição do Contra-Escopo          | 
|------|-------------------------------------|
|CE-001| Treinamento de modelo de LLM        |
|CE-002| Pesquisa de viabilidade do mercado. |

### Condições para início do Projeto

......  ATUALIZE AS CONDIÇÕES PARA INÍCIO DOS PROJETOS (MÍNIMO 3) ......

A tabela a seguir, apresente as condições para que o projeto seja iniciado.

|ID    | Descrição de Condições para Início do Projeto    | 
|------|--------------------------------------------------|
|CI-001| Assinatura de contrato de prestação de serviços. |
|CI-002| Apresentação de garantias definidas no contrato. |

## Marcos Agendados e Entregas

......  ATUALIZE OS MARCOS AGENDADOS DO PROJETO E AS DATAS PARA ENTREGAS DAS TAREFAS ......

A tabela a seguir, identifique os marcos do projeto e os entregáveis previstos (requisitos).

|ID   | Marco do Projeto                                                  | 
|-----|-------------------------------------------------------------------|
|M-1  | Liberação do sistema para cadastro de informações e configuração. |
|M-2  | Permissão para uso do sistema, por usuários focais.               |
|M-3  |                                                                   |
|M-4  |                                                                   |
|M-5  |                                                                   |
|M-6  |                                                                   |

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

......  COLOQUE AQUI O SEU TEXTO ......

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

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
> Indique as responsabilidades de cada membro do grupo no projeto.

## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

> Liste as ferramentas empregadas no desenvolvimento do projeto, justificando a escolha delas, sempre que possível.
> Todas as ferramentas utilizadas devem ser listadas.
> Qualquer tipo de ferramenta que for utilizada para construção de um artefato deve ser identificada, uma vez que podem ser necessárias alterações.
> A necessidade de uso de licenças e possíveis custos relacionados devem ser indicados.

| Ambiente              | Plataforma         | Link de Acesso             | Justificativa |
|-----------------------|--------------------|----------------------------|---------------|
| Quadro Kanban         | Github             | https://github.com/XXXXXXX | Centralização e organização do projeto no próprio repositório. |
| Repositório de código | GitHub             | https://github.com/XXXXXXX |               |
| Protótipo Interativo  | MavelApp ou Figma  | https://figma.com/XXXXXXX  |               |
| Documentos Textuais   | LibreOffice Writer | N/A                        |               |
| Planilhas e Gráficos  | Google Planilhas   | https://docs.google.com/   |               |
| EAP / WBS             | | | |
| Cronograma do Projeto | | | |
| Matriz RACI           | | | |

```diff
+ Tarefa 03:
+ Fim da seção a ser atualizada.
```

----
