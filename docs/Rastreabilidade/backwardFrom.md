# Backward-From

## Introdução

A técnica **Backward-From** é uma abordagem utilizada na rastreabilidade de requisitos para estabelecer conexões entre os requisitos e suas origens, sejam elas documentos, stakeholders ou outras fontes. Essa técnica assegura que cada requisito possui uma base justificável e rastreável, facilitando a compreensão de sua necessidade e contexto no projeto.

Por meio do Backward-From, é possível identificar claramente de onde cada requisito se originou. Essa prática contribui para a gestão eficaz de mudanças, evitando a perda de rastreabilidade e garantindo que as funcionalidades desenvolvidas atendam às expectativas e necessidades iniciais. Além disso, o Backward-From permite uma análise crítica de como os requisitos estão alinhados com os objetivos do projeto.

# Metodologia

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

- **BCF:** Requisitos do Backward-From  
- **BF:** Requisito Funcional do Brainstorm  
- **GF:** Requisito do Grupo de Foco  
- **IT:** Requisito da Introspecção  
- **GLO:** Requisito do Glossário  
- **RF:** Requisito Funcional  


<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Requisitos funcionais elicitados</p></font>


| **ID** | **Requisito e Versão** | **Descrição**              | **Implementado** | **Rastreabilidade** |
|--------|------------------------|----------------------------|------------------|---------------------|
| RF1    | Versão 1.0            | Criar postagens no Threads| Sim              | BCF, BF             |
| RF2    | Versão 1.0            | Curtir postagens           | Não              | GF, IT              |
| RF3    | Versão 1.1            | Gerenciar privacidade      | Sim              | GLO, BCF            |

### Tabela de Requisitos Não-Funcionais

Este seguimento é destinado para a elaboração da tabela de rastreamento de requisitos não-funcionais, que está sendo demonstrado na Tabela 2 a seguir:

#### Legendas

- **BCF:** Requisitos do Backward-From  
- **BFN:** Requisito Não Funcional do Brainstorm  
- **GF:** Requisito do Grupo de Foco  
- **IT:** Requisito da Introspecção  
- **GLO:** Requisito do Glossário  
- **RNF:** Requisito Não Funcional  

<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Requisitos não-funcionais elicitados</p></font>


| **ID** | **Requisito e Versão** | **Descrição**                  | **Implementado** | **Rastreabilidade** |
|--------|------------------------|--------------------------------|------------------|---------------------|
| RNF1   | Versão 1.0            | Garantir tempo de resposta <1s| Sim              | BCF, GF             |
| RNF2   | Versão 1.0            | Criptografia ponta a ponta     | Sim              | IT, GLO             |
| RNF3   | Versão 1.1            | Suporte para múltiplos idiomas | Não              | BCF, BFN            |


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


