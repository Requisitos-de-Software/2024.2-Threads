# Backward-From

## Introdução

A técnica **Backward-From** é uma abordagem utilizada na rastreabilidade de requisitos para estabelecer conexões entre os requisitos e suas origens, sejam elas documentos, stakeholders ou outras fontes. Essa técnica assegura que cada requisito possui uma base justificável e rastreável, facilitando a compreensão de sua necessidade e contexto no projeto.

Por meio do Backward-From, é possível identificar claramente de onde cada requisito se originou. Essa prática contribui para a gestão eficaz de mudanças, evitando a perda de rastreabilidade e garantindo que as funcionalidades desenvolvidas atendam às expectativas e necessidades iniciais. Além disso, o Backward-From permite uma análise crítica de como os requisitos estão alinhados com os objetivos do projeto.

## Metodologia

A rastreabilidade de requisitos é fundamental para o sucesso no desenvolvimento de software, pois permite garantir que todas as fases do projeto estejam alinhadas com as necessidades e os objetivos iniciais. No caso do aplicativo Threads, adotamos a técnica **Backward-From** para rastrear os requisitos de maneira estruturada, garantindo a consistência e o alinhamento das decisões ao longo do desenvolvimento.

## Etapas da Metodologia

### 1. Identificação das Origens dos Requisitos

Para cada requisito, foi realizada uma análise detalhada para identificar sua origem. As fontes de origem incluem **stakeholders**, **documentação inicial**, e **padrões de mercado**. Compreender essas origens foi crucial para conectar cada requisito às necessidades reais do projeto e garantir que todos os requisitos sejam válidos e relevantes.

### 2. Categorização dos Requisitos

Os requisitos foram organizados de maneira a facilitar o acompanhamento e a validação durante o desenvolvimento. Para isso, dividimos os requisitos em duas categorias principais:

- **Requisitos Funcionais (RF)**: Estes requisitos dizem respeito às funcionalidades essenciais do aplicativo, como a criação de postagens, a interação com seguidores, e o gerenciamento de privacidade.
- **Requisitos Não-Funcionais (RNF)**: Refletem os aspectos técnicos e operacionais do sistema, como o desempenho, a segurança e a usabilidade, os quais são fundamentais para garantir a robustez e a confiabilidade da plataforma.

### 3. Mapeamento e Definição de Conexões

Após categorizar os requisitos, realizamos um mapeamento para identificar e definir as conexões entre os requisitos e seus respectivos elementos dentro do projeto. Esse mapeamento incluiu a criação de **elos de rastreabilidade**, classificados da seguinte forma:

- **Dependência Contextual**: Refere-se à relação entre os requisitos e o ambiente ou o contexto operacional do aplicativo Threads. Esses elos garantem que as necessidades do sistema estejam em conformidade com o cenário em que o aplicativo será utilizado.
- **Relacionamento Funcional**: Estabelece um vínculo entre os requisitos e os subsistemas ou componentes específicos do aplicativo. Essa conexão assegura que a funcionalidade do sistema seja implementada conforme o esperado.
- **Documentação de Decisões**: Registra o raciocínio por trás das decisões de definição e priorização dos requisitos, incluindo quaisquer trade-offs ou ajustes realizados para atender aos objetivos do projeto.

### 4. Criação da Matriz Backward-From

Com base nas conexões estabelecidas, foi criada uma **matriz Backward-From** para rastrear o impacto e a origem de cada requisito. A matriz facilita a visualização de como cada requisito está relacionado com as decisões tomadas ao longo do desenvolvimento, permitindo um controle mais eficiente e transparente do progresso do projeto.

### 5. Validação e Refinamento Contínuos

A matriz de rastreabilidade foi revisada periodicamente com os stakeholders para garantir sua precisão e o alinhamento com os objetivos do projeto. Esse processo de validação e refinamento contínuo assegura que todos os requisitos sejam atendidos de forma adequada e que o desenvolvimento permaneça alinhado com as expectativas dos envolvidos.

## Tabela de requisitos funcionais


Este seguimento é destinado para a elaboração da tabela de rastreamento de requisitos funcionais, que está sendo demonstrada na Tabela 1 a seguir:

### Legendas

- **BF:** Requisitos do Backward-From  
- **BRS:** Requisito Funcional do Brainstorming  
- **ENT:** Requisito da Entrevista  
- **INT:** Requisito da Introspecção  
- **QST:** Requisito do Questionário  
- **RF:** Requisito Funcional  


<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Requisitos funcionais elicitados</p></font>


| **ID** | **Requisito e Versão**                      | **Descrição**                                                                                      | **Implementado** | **Rastreabilidade** | **Elo**  |
|--------|--------------------------------------------|--------------------------------------------------------------------------------------------------|------------------|---------------------|----------|
| BF01   | RF01 / 1.0                                 | O usuário deve poder configurar a visibilidade da conta.                                         | Sim              | ENT                 | ELO01    |
| BF02   | RF02 / 1.0                                 | O usuário deve poder gravar e enviar mensagens de voz.                                           | Sim              | ENT                 | ELO02    |
| BF03   | RF03 / 1.0                                 | O sistema deve exibir Trend Topics para visualização dos tópicos populares.                     | Não              | ENT                 | ELO03    |
| BF04   | RF04 / 1.0                                 | O usuário deve poder definir o tema escuro ou claro no aplicativo.                              | Sim              | ENT                 | ELO04    |
| BF05   | RF05 / 1.0                                 | O sistema deve oferecer uma área de mensagens privadas para interações.                         | Não              | ENT                 | ELO05    |
| BF06   | RF06 / 1.0                                 | O sistema deve verificar contas com número de telefone e email cadastrados.                     | Sim              | ENT                 | ELO06    |
| BF07   | RF07 / 1.0                                 | O sistema deve permitir a tradução automática de publicações.                                   | Não              | ENT                 | ELO07    |
| BF08   | RF08 / 1.0                                 | O sistema deve reduzir a exibição de anúncios intrusivos.                                       | Não              | ENT                 | ELO08    |
| BF09   | RF09 / 1.0                                 | O sistema deve implementar moderação para reduzir bots e publicações irrelevantes.             | Não              | ENT                 | ELO09    |
| BF10   | RF10 / 1.0                                 | O sistema deve permitir o upload de vídeos em alta definição.                                   | Sim              | ENT                 | ELO10    |
| BF11   | RF11 / 1.0                                 | O sistema deve exibir uma confirmação visual ao realizar ações.                                | Sim              | ENT                 | ELO11    |
| BF12   | RF12 / 1.0                                 | O sistema deve oferecer um histórico de interações do usuário.                                  | Sim              | ENT                 | ELO12    |
| BF13   | RF13 / 1.0                                 | O sistema deve permitir respostas anônimas em discussões públicas moderadas.                   | Não              | ENT                 | ELO13    |
| BF14   | RF14 / 1.0                                 | O sistema deve permitir que o usuário salve postagens para leitura posterior.                  | Não              | ENT                 | ELO14    |
| BF15   | RF15 / 1.0                                 | O sistema deve sugerir usuários para seguir, com base nas interações do usuário.               | Sim              | ENT                 | ELO15    |
| BF16   | RF16 / 1.0                                 | O sistema deve permitir a criação de enquetes interativas.                                      | Não              | ENT                 | ELO16    |
| BF17   | RF17 / 1.0                                 | O sistema deve permitir ao usuário denunciar contas ou postagens.                               | Sim              | ENT                 | ELO17    |
| BF18   | RF18 / 1.0                                 | O usuário deve poder ocultar publicações antigas de seu perfil sem excluí-las.                 | Não              | ENT                 | ELO18    |
| BF19   | RF19 / 1.0                                 | O sistema deve permitir backup e restauração de dados, como postagens e configurações.         | Não              | ENT                 | ELO19    |
| BF20   | RF20 / 1.0                                 | O sistema deve permitir filtrar conteúdos no feed com base em categorias específicas.          | Não              | ENT                 | ELO20    |
| BF21   | RF21 / 1.0                                 | O sistema deve permitir que o usuário adicione legendas automáticas aos vídeos enviados.       | Não              | ENT                 | ELO21    |
| BF22   | RF22 / 1.0                                 | O sistema deve sugerir textos gerados por Inteligência Artificial para publicações.            | Não              | ENT                 | ELO22    |
| BF23   | RF23 / 1.0                                 | O sistema deve oferecer reações variadas para publicações.                                      | Não              | ENT                 | ELO23    |
| BF24   | RF24 / 1.0                                 | O sistema deve permitir salvar rascunhos de postagens mesmo sem conexão.                       | Não              | ENT                 | ELO24    |
| BF25   | RF25 / 1.0                                 | O sistema deve permitir agendar postagens para horários futuros.                               | Não              | ENT                 | ELO25    |
| BF26   | RF26 / 1.0                                 | O sistema deve permitir o compartilhamento de postagens externas.                              | Não              | ENT                 | ELO26    |
| BF27   | RF27 / 1.0                                 | O sistema deve permitir criar comunidades ou grupos dentro da plataforma.                      | Não              | ENT                 | ELO27    |
| BF28   | RF28 / 1.0                                 | O sistema deve permitir que o usuário gerencie múltiplas contas no mesmo aplicativo.           | Não              | ENT                 | ELO28    |
| BF29   | RF29 / 1.0                                 | O sistema deve oferecer autenticação avançada para segurança do usuário.                       | Sim              | ENT                 | ELO29    |
| BF30   | RF30 / 1.0                                 | O sistema deve permitir fixar postagens no perfil do usuário.                                  | Não              | ENT                 | ELO30    |
| BF31   | RF31 / 1.0                                 | O sistema deve permitir editar publicações após a postagem.                                    | Não              | QST                 | ELO31    |
| BF32   | RF32 / 1.0                                 | O sistema deve permitir marcar outros usuários em postagens.                                   | Sim              | QST                 | ELO32    |
| BF33   | RF33 / 1.0                                 | O sistema deve permitir ver estatísticas detalhadas sobre as postagens.                       | Não              | QST                 | ELO33    |
| BF34   | RF34 / 1.0                                 | O sistema deve permitir que o usuário receba alertas de menções.                              | Sim              | QST                 | ELO34    |
| BF35   | RF35 / 1.0                                 | O sistema deve permitir reações a comentários em postagens.                                   | Sim              | QST                 | ELO35    |
| BF36   | RF36 / 1.0                                 | O sistema deve permitir criar listas de amigos próximos.                                       | Não              | BRS                 | ELO36    |
| BF37   | RF37 / 1.0                                 | O sistema deve permitir realizar pesquisas de conteúdo.                                        | Sim              | BRS                 | ELO37    |
| BF38   | RF38 / 1.0                                 | O sistema deve permitir denunciar comentários ofensivos.                                       | Sim              | BRS                 | ELO38    |
| BF39   | RF39 / 1.0                                 | O sistema deve sugerir postagens personalizadas de acordo com as preferências do usuário.     | Não              | BRS                 | ELO39    |
| BF40   | RF40 / 1.0                                 | O sistema deve permitir configurar o status online ou offline do usuário.                     | Não              | BRS                 | ELO40    |

<p style="text-align: center; font-size: 14px;">
    Autores: <a href="https://github.com/GenilsonJrs" target="_blank">Genilson Silva,</a> <a href="https://github.com/alanagabriele" target="_blank">Alana Gabriele,</a> <a href="https://github.com/dudupaz" target="_blank">Carlos Paz,</a> <a href="https://github.com/SamuelRicosta" target="_blank"> Samuel Ribeiro. </a>
</p>

### Tabela de Requisitos Não-Funcionais

Este seguimento é destinado para a elaboração da tabela de rastreamento de requisitos não-funcionais, que está sendo demonstrado na Tabela 2 a seguir:

#### Legendas

- **BF:** Requisitos do Backward-From  
- **BRS:** Requisito Funcional do Brainstorming  
- **ENT:** Requisito da Entrevista  
- **INT:** Requisito da Introspecção  
- **QST:** Requisito do Questionário   
- **RNF:** Requisito Não Funcional   

<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Requisitos não-funcionais elicitados</p></font>



| **ID** | **Requisito e Versão**                      | **Descrição**                                                                                      | **Implementado** | **Rastreabilidade** | **Elo**  |
|--------|--------------------------------------------|--------------------------------------------------------------------------------------------------|------------------|---------------------|----------|
| BF41   | RNF01 / 1.0                                 | O sistema deve reduzir anúncios intrusivos e ajustar algoritmos para maior transparência.       | Não              | INT                 | ELO41    |
| BF42   | RNF02 / 1.0                                 | O sistema deve melhorar o algoritmo para priorizar conteúdos relevantes ao usuário.             | Não              | INT                 | ELO42    |
| BF43   | RNF03 / 1.0                                 | O sistema deve evitar a sobrecarga de notificações irrelevantes.                                | Não              | INT                 | ELO43    |
| BF44   | RNF04 / 1.0                                 | O sistema deve implementar moderação para reduzir bots e publicações irrelevantes.             | Sim              | INT                 | ELO44    |
| BF45   | RNF05 / 1.0                                 | O sistema deve oferecer autenticação avançada para segurança do usuário.                       | Sim              | INT                 | ELO45    |
| BF46   | RNF06 / 1.0                                 | O sistema deve garantir tempos de resposta inferiores a 1 segundo para interações usuais.       | Sim              | INT                 | ELO46    |
| BF47   | RNF07 / 1.0                                 | O aplicativo deve minimizar o consumo de bateria em dispositivos móveis, garantindo uma taxa de consumo inferior a 5%. | Não              | INT                 | ELO47    |
| BF48   | RNF08 / 1.0                                 | O sistema deve ser compatível com dispositivos móveis de versões Android 8.0 e iOS 12 ou superiores. | Sim              | INT                 | ELO48    |
| BF49   | RNF09 / 1.0                                 | O sistema deve ser compatível com versões de navegador mais antigas, garantindo funcionalidade em Chrome 70+ e Firefox 70+. | Não              | BRS                 | ELO49    |
| BF50   | RNF10 / 1.0                                 | O sistema deve garantir alta disponibilidade, com menos de 1% de tempo de inatividade mensal.   | Sim              | BRS                 | ELO50    |
| BF51   | RNF11 / 1.0                                 | O sistema deve criptografar todos os dados de login e autenticação para garantir a segurança das informações. | Sim              | BRS                 | ELO51    |
| BF52   | RNF12 / 1.0                                 | O sistema deve ser otimizado para uso em dispositivos com pouca memória RAM.                   | Não              | BRS                 | ELO52    |
| BF53   | RNF13 / 1.0                                 | O sistema deve ser compatível com os navegadores mais recentes, como Google Chrome, Safari e Edge. | Sim              | BRS                 | ELO53    |
| BF54   | RNF14 / 1.0                                 | O sistema deve garantir que o feed de publicações seja carregado rapidamente, mesmo com grande volume de conteúdo. | Sim              | BRS                 | ELO54    |
| BF55   | RNF15 / 1.0                                 | O sistema deve garantir que os dados do usuário sejam armazenados de forma segura, com backup regular. | Sim              | BRS                 | ELO55    |
| BF56   | RNF16 / 1.0                                 | O sistema deve garantir que o conteúdo do usuário seja sempre acessível, com um tempo de recuperação abaixo de 10 segundos. | Sim              | BRS                 | ELO56    |
| BF57   | RNF17 / 1.0                                 | O sistema deve permitir que o usuário configure o status online ou offline.                     | Não              | BRS                 | ELO57    |
| BF58   | RNF18 / 1.0                                 | O sistema deve permitir a criação de listas de amigos próximos.                                 | Não              | BRS                 | ELO58    |
| BF59   | RNF19 / 1.0                                 | O sistema deve permitir respostas anônimas em discussões públicas moderadas.                   | Não              | BRS                 | ELO59    |
| BF60   | RNF20 / 1.0                                 | O sistema deve permitir salvar rascunhos de postagens mesmo sem conexão.                       | Não              | BRS                 | ELO60    |


<p style="text-align: center; font-size: 14px;">
    Autores: <a href="https://github.com/GenilsonJrs" target="_blank">Genilson Silva,</a> <a href="https://github.com/alanagabriele" target="_blank">Alana Gabriele,</a> <a href="https://github.com/dudupaz" target="_blank">Carlos Paz,</a> <a href="https://github.com/SamuelRicosta" target="_blank"> Samuel Ribeiro. </a>
</p>


## Elos de Rastreabilidade

Os elos de rastreabilidade estabelecem conexões importantes entre os requisitos, suas origens e as dependências existentes. A tabela 3 a seguir apresenta os principais tipos de elos identificados no projeto Threads, com suas respectivas descrições:

### Tipos de Elos:

- **Elos de Satisfação (ES)**: Relacionam um requisito a partes do sistema que o atendem, mostrando como as funcionalidades foram projetadas ou implementadas para satisfazer um requisito específico.
- **Elos de Dependência (ED)**: Relacionam requisitos que dependem de outros para serem implementados ou validados. Esses elos ajudam a identificar sequências ou pré-condições necessárias para o desenvolvimento de certos requisitos.
- **Elos de Evolução (ER)**: Mostram como um requisito foi alterado ao longo do tempo, incluindo versões anteriores e modificações realizadas, ajudando a entender a evolução dos requisitos e o impacto das mudanças.
- **Elos de Rationale (Justificativa) (RJ)**: Documentam as razões por trás da criação ou modificação de um requisito, fornecendo contexto e justificativas para decisões tomadas durante o desenvolvimento.
- **Elos de Validação (IV)**: Relacionam um requisito à atividade de teste ou verificação que confirma sua implementação ou conformidade. Esses elos são fundamentais para garantir que o requisito tenha sido atendido e validado adequadamente.
- **Elos de Implementação (IM)**: Estabelecem a conexão entre os requisitos e as atividades ou componentes responsáveis por sua implementação no código. Esses elos ajudam a monitorar o progresso de desenvolvimento.
- **Elos de Rejeição (RJ)**: Indicam requisitos que foram analisados mas rejeitados durante o processo de desenvolvimento, explicando os motivos da exclusão.
- **Elos de Impacto (IP)**: Representam como uma mudança em um requisito pode afetar outros requisitos ou componentes do sistema, sendo úteis para gerenciar alterações e prever consequências.

#### Legendas

- **ID BCF:** Identificador do Backward-From relacionado  


<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Elos de rastreabilidade</p></font>


| ID  | ID BCF  | Tipo de Elo              | Descrição do Elo                                      |
| --- | ------- | ------------------------ | ----------------------------------------------------- |
| E1  | BCF1    | Satisfação               | Relaciona o requisito à parte do sistema que o atende |
| E2  | BCF2    | Dependência              | Relaciona requisitos que dependem de outros para serem validados |
| E3  | BCF3    | Evolução                 | Registra modificações e versões anteriores de requisitos |
| E4  | BCF4    | Rationale (Justificativa) | Justifica a criação ou modificação do requisito       |
| E5  | BCF5    | Validação                | Relaciona o requisito à atividade de teste que o valida |
| E6  | BCF6    | Implementação            | Relaciona o requisito às atividades de implementação |
| E7  | BCF7    | Rejeição                 | Indica um requisito rejeitado, com justificativa      |
| E8  | BCF8    | Impacto                  | Relaciona como uma mudança em um requisito impacta outros |


## Conclusão


Este trabalho descreveu a aplicação da rastreabilidade de requisitos no desenvolvimento do aplicativo Threads, utilizando a técnica Backward-From. Foram identificados e mapeados diversos elos de rastreabilidade, que abrangem diferentes aspectos dos requisitos, como suas origens, dependências, evolução e justificativas. Esses elos proporcionaram uma visão clara das inter-relações entre os requisitos e os componentes do sistema, garantindo que os requisitos estivessem alinhados aos objetivos do projeto e atendendo às expectativas dos stakeholders. A metodologia aplicada contribuiu para assegurar a consistência, completude e qualidade dos requisitos, promovendo um gerenciamento eficiente das mudanças e impactos ao longo do ciclo de desenvolvimento.


## Referência

PUC-Rio. **Rastreabilidade de requisitos: fundamentos e técnicas**. Disponível em: [https://www.dbd.puc-rio.br/pergamum/tesesabertas/1121794_2014_cap_2.pdf](https://www.dbd.puc-rio.br/pergamum/tesesabertas/1121794_2014_cap_2.pdf). Acesso em: 17 jan. 2025.


## Histórico de Versões

| Versão | Data       | Descrição                                             | Autor                                              | Revisor                                            |
| :----: | ---------- | ----------------------------------------------------- | -------------------------------------------------- | -------------------------------------------------- |
|  1.0   | 17/01/2025 | Criação do documento                                  | [Samuel Ribeiro](https://github.com/SamuelRicosta) | [Alana Gabriele](https://github.com/alanagabriele) |
|  1.2   | 18/01/2025 | Adição das tabelas                                  | [Genilson Silva](https://github.com/GenilsonJrs) | [Samuel Ribeiro](https://github.com/SamuelRicosta) |


