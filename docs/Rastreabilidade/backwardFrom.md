# Backward-From

## Introdução

A técnica **Backward-From** é uma abordagem utilizada na rastreabilidade de requisitos para estabelecer conexões entre os requisitos e suas origens, sejam elas documentos, stakeholders ou outras fontes. Essa técnica assegura que cada requisito possui uma base justificável e rastreável, facilitando a compreensão de sua necessidade e contexto no projeto.

Por meio do Backward-From, é possível identificar claramente de onde cada requisito se originou. Essa prática contribui para a gestão eficaz de mudanças, evitando a perda de rastreabilidade e garantindo que as funcionalidades desenvolvidas atendam às expectativas e necessidades iniciais. Além disso, o Backward-From permite uma análise crítica de como os requisitos estão alinhados com os objetivos do projeto.

# Metodologia

A rastreabilidade de requisitos desempenha um papel essencial no desenvolvimento de software, garantindo que cada etapa do projeto esteja conectada às necessidades e objetivos iniciais. Para o aplicativo Threads, adotamos a técnica **Backward-From** para rastrear os requisitos de maneira sistemática, assegurando a consistência e alinhamento ao longo do projeto.

## Etapas da Metodologia

1. **Identificação das Origens dos Requisitos**  
   Cada requisito foi analisado para identificar sua origem, seja ela stakeholders, documentação inicial ou padrões de mercado. Esse entendimento foi essencial para conectar os requisitos às necessidades reais do projeto.

2. **Categorização dos Requisitos**  
   Os requisitos foram organizados em:
   - **Requisitos Funcionais (RF):** Funcionalidades essenciais como criação de postagens, interação com seguidores e gerenciamento de privacidade.
   - **Requisitos Não-Funcionais (RNF):** Aspectos relacionados ao desempenho, segurança e usabilidade, garantindo a robustez da plataforma.

3. **Mapeamento e Definição de Conexões**  
   Os requisitos foram associados às suas origens e a outros elementos do projeto por meio de elos de rastreabilidade, categorizados como:
   - **Dependência Contextual:** Relação com o ambiente ou contexto operacional do Threads.
   - **Relacionamento Funcional:** Vínculo com subsistemas ou componentes específicos do aplicativo.
   - **Documentação de Decisões:** Registro de como e por que os requisitos foram definidos e priorizados.

4. **Criação da Matriz Backward-From**  
   Com base no mapeamento, foi criada uma matriz para rastrear o impacto e a origem dos requisitos. Essa matriz permite identificar rapidamente como cada requisito está conectado às decisões tomadas durante o desenvolvimento.

5. **Validação e Refinamento Contínuos**  
   A matriz foi revisada com os stakeholders para garantir precisão e alinhamento com os objetivos do projeto, promovendo uma rastreabilidade robusta e confiável.

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

### Elos de Rastreabilidade

Os elos de rastreabilidade estabelecem conexões importantes entre os requisitos, suas origens e as dependências existentes. A tabela a seguir apresenta os principais elos identificados no projeto Threads.

#### Legendas

- **ID BCF:** Identificador do Backward-From relacionado  

<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Elos de rastreabilidade</p></font>


| **ID** | **ID BCF** | **Tipo de Elo**         | **Descrição do Elo**                                              |
|--------|------------|-------------------------|-------------------------------------------------------------------|
| E1     | BCF1       | Dependência Contextual  | Relaciona requisitos ao ambiente operacional do Threads          |
| E2     | BCF2       | Relacionamento Funcional| Conecta requisitos a subsistemas ou funcionalidades específicas  |
| E3     | BCF3       | Documentação de Decisões| Registra as justificativas e motivos por trás das escolhas feitas|  



























## Histórico de Versões

| Versão | Data       | Descrição                                             | Autor                                              | Revisor                                            |
| :----: | ---------- | ----------------------------------------------------- | -------------------------------------------------- | -------------------------------------------------- |
|  1.0   | 17/01/2025 | Criação do documento                                  | [Samuel Ribeiro](https://github.com/SamuelRicosta) | [Alana Gabriele](https://github.com/alanagabriele) |

## Referência

PUC-Rio. **Rastreabilidade de requisitos: fundamentos e técnicas**. Disponível em: [https://www.dbd.puc-rio.br/pergamum/tesesabertas/1121794_2014_cap_2.pdf](https://www.dbd.puc-rio.br/pergamum/tesesabertas/1121794_2014_cap_2.pdf). Acesso em: 17 jan. 2025.


