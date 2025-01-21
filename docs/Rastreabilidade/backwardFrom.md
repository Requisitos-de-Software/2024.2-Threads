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

| **ID**                                                  | **Requisito e Versão**                                                                | **Descrição**                                                                             | **Implementado** | **Rastreabilidade**                                                      | **Elo** |
| ------------------------------------------------------- | ------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ---------------- | ------------------------------------------------------------------------ | ------- |
| <a id="anchor_BF01" style="visibility: hidden"></a>BF01 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF01">RF01 </a> / 1.0 | O usuário deve poder configurar a visibilidade da conta.                                  | Sim              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E01">ENT1-01 </a>  | ELO01   |
| <a id="anchor_BF02" style="visibility: hidden"></a>BF02 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF02">RF02 </a> / 1.0 | O usuário deve poder gravar e enviar mensagens de voz.                                    | Sim              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E02">ENT1-02 </a>  | ELO02   |
| <a id="anchor_BF03" style="visibility: hidden"></a>BF03 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF03">RF03 </a> / 1.0 | O sistema deve exibir Trend Topics para visualização dos tópicos populares.               | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E03">ENT1-03 </a>  | ELO03   |
| <a id="anchor_BF04" style="visibility: hidden"></a>BF04 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF04">RF04 </a> / 1.0 | O usuário deve poder definir o tema escuro ou claro no aplicativo.                        | Sim              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E04">ENT1-04 </a>  | ELO04   |
| <a id="anchor_BF05" style="visibility: hidden"></a>BF05 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF05">RF05 </a> / 1.0 | O sistema deve oferecer uma área de mensagens privadas para interações.                   | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E05">ENT1-05 </a>  | ELO05   |
| <a id="anchor_BF06" style="visibility: hidden"></a>BF06 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF06">RF06 </a> / 1.0 | O sistema deve verificar contas com número de telefone e email cadastrados.               | Sim              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E06">ENT1-06 </a>  | ELO06   |
| <a id="anchor_BF07" style="visibility: hidden"></a>BF07 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF07">RF07 </a> / 1.0 | O sistema deve permitir a tradução automática de publicações.                             | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E07">ENT1-07 </a>  | ELO07   |
| <a id="anchor_BF08" style="visibility: hidden"></a>BF08 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF08">RF08 </a> / 1.0 | O sistema deve reduzir a exibição de anúncios intrusivos.                                 | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E08">ENT1-08 </a>  | ELO08   |
| <a id="anchor_BF09" style="visibility: hidden"></a>BF09 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF09">RF09 </a> / 1.0 | O sistema deve implementar moderação para reduzir bots e publicações irrelevantes.        | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E09">ENT1-09 </a>  | ELO09   |
| <a id="anchor_BF10" style="visibility: hidden"></a>BF10 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF10">RF10 </a> / 1.0 | O sistema deve permitir o upload de vídeos em alta definição.                             | Sim              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E10">ENT1-10 </a>  | ELO10   |
| <a id="anchor_BF11" style="visibility: hidden"></a>BF11 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF11">RF11 </a> / 1.0 | O sistema deve exibir uma confirmação visual ao realizar ações.                           | Sim              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E11">ENT2-01 </a>  | ELO11   |
| <a id="anchor_BF12" style="visibility: hidden"></a>BF12 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF12">RF12 </a> / 1.0 | O sistema deve oferecer um histórico de interações do usuário.                            | Sim              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E12">ENT2-02 </a>  | ELO12   |
| <a id="anchor_BF13" style="visibility: hidden"></a>BF13 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF13">RF13 </a> / 1.0 | O sistema deve permitir respostas anônimas em discussões públicas moderadas.              | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E13">ENT2-03 </a>  | ELO13   |
| <a id="anchor_BF14" style="visibility: hidden"></a>BF14 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF14">RF14 </a> / 1.0 | O sistema deve permitir que o usuário salve postagens para leitura posterior.             | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E14">ENT2-04 </a>  | ELO14   |
| <a id="anchor_BF15" style="visibility: hidden"></a>BF15 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF15">RF15 </a> / 1.0 | O sistema deve sugerir usuários para seguir, com base nas interações do usuário.          | Sim              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E15">ENT2-05 </a>  | ELO15   |
| <a id="anchor_BF16" style="visibility: hidden"></a>BF16 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF16">RF16 </a> / 1.0 | O sistema deve permitir a criação de enquetes interativas.                                | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E16">ENT2-06 </a>  | ELO16   |
| <a id="anchor_BF17" style="visibility: hidden"></a>BF17 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF17">RF17 </a> / 1.0 | O sistema deve permitir ao usuário denunciar contas ou postagens.                         | Sim              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E17">ENT2-07 </a>  | ELO17   |
| <a id="anchor_BF18" style="visibility: hidden"></a>BF18 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF18">RF18 </a> / 1.0 | O usuário deve poder ocultar publicações antigas de seu perfil sem excluí-las.            | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E18">ENT2-08 </a>  | ELO18   |
| <a id="anchor_BF19" style="visibility: hidden"></a>BF19 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF19">RF19 </a> / 1.0 | O sistema deve permitir backup e restauração de dados, como postagens e configurações.    | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E19">ENT2-09 </a>  | ELO19   |
| <a id="anchor_BF20" style="visibility: hidden"></a>BF20 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF20">RF20 </a> / 1.0 | O sistema deve permitir filtrar conteúdos no feed com base em categorias específicas.     | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E20">ENT2-10 </a>  | ELO20   |
| <a id="anchor_BF21" style="visibility: hidden"></a>BF21 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF21">RF21 </a> / 1.0 | O sistema deve permitir que o usuário adicione legendas automáticas aos vídeos enviados.  | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E21">ENT3-01 </a>  | ELO21   |
| <a id="anchor_BF22" style="visibility: hidden"></a>BF22 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF22">RF22 </a> / 1.0 | O sistema deve sugerir textos gerados por Inteligência Artificial para publicações.       | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E22">ENT3-02 </a>  | ELO22   |
| <a id="anchor_BF23" style="visibility: hidden"></a>BF23 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF23">RF23 </a> / 1.0 | O sistema deve oferecer reações variadas para publicações.                                | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E23">ENT3-03 </a>  | ELO23   |
| <a id="anchor_BF24" style="visibility: hidden"></a>BF24 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF24">RF24 </a> / 1.0 | O sistema deve permitir salvar rascunhos de postagens mesmo sem conexão.                  | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E24">ENT3-04 </a>  | ELO24   |
| <a id="anchor_BF25" style="visibility: hidden"></a>BF25 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF25">RF25 </a> / 1.0 | O sistema deve permitir agendar postagens para horários futuros.                          | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E25">ENT3-05 </a>  | ELO25   |
| <a id="anchor_BF26" style="visibility: hidden"></a>BF26 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF26">RF26 </a> / 1.0 | O sistema deve permitir o compartilhamento de postagens externas.                         | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E26">ENT3-06 </a>  | ELO26   |
| <a id="anchor_BF27" style="visibility: hidden"></a>BF27 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF27">RF27 </a> / 1.0 | O sistema deve permitir criar comunidades ou grupos dentro da plataforma.                 | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E27">ENT3-07 </a>  | ELO27   |
| <a id="anchor_BF28" style="visibility: hidden"></a>BF28 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF28">RF28 </a> / 1.0 | O sistema deve permitir que o usuário gerencie múltiplas contas no mesmo aplicativo.      | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E28">ENT3-08 </a>  | ELO28   |
| <a id="anchor_BF29" style="visibility: hidden"></a>BF29 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF29">RF29 </a> / 1.0 | O sistema deve oferecer autenticação avançada para segurança do usuário.                  | Sim              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E29">ENT3-09 </a>  | ELO29   |
| <a id="anchor_BF30" style="visibility: hidden"></a>BF30 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF30">RF30 </a> / 1.0 | O sistema deve permitir fixar postagens no perfil do usuário.                             | Não              | <a href="../../Elicitacao/tecnicas/entrevista/#anchor_E30">ENT3-10 </a>  | ELO30   |
| <a id="anchor_BF31" style="visibility: hidden"></a>BF31 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF31">RF31 </a> / 1.0 | O sistema deve permitir editar publicações após a postagem.                               | Não              | <a href="../../Elicitacao/tecnicas/questionario/#anchor_Q01">QST01 </a>  | ELO31   |
| <a id="anchor_BF32" style="visibility: hidden"></a>BF32 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF32">RF32 </a> / 1.0 | O sistema deve permitir marcar outros usuários em postagens.                              | Sim              | <a href="../../Elicitacao/tecnicas/questionario/#anchor_Q02">QST02 </a>  | ELO32   |
| <a id="anchor_BF33" style="visibility: hidden"></a>BF33 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF33">RF33 </a> / 1.0 | O sistema deve permitir ver estatísticas detalhadas sobre as postagens.                   | Não              | <a href="../../Elicitacao/tecnicas/questionario/#anchor_Q03">QST03 </a>  | ELO33   |
| <a id="anchor_BF34" style="visibility: hidden"></a>BF34 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF34">RF34 </a> / 1.0 | O sistema deve permitir que o usuário receba alertas de menções.                          | Sim              | <a href="../../Elicitacao/tecnicas/questionario/#anchor_Q04">QST04 </a>  | ELO34   |
| <a id="anchor_BF35" style="visibility: hidden"></a>BF35 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF35">RF35 </a> / 1.0 | O sistema deve permitir reações a comentários em postagens.                               | Sim              | <a href="../../Elicitacao/tecnicas/questionario/#anchor_Q05">QST05 </a>  | ELO35   |
| <a id="anchor_BF36" style="visibility: hidden"></a>BF36 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF36">RF36 </a> / 1.0 | O sistema deve permitir criar listas de amigos próximos.                                  | Não              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B01">BRS01 </a> | ELO36   |
| <a id="anchor_BF37" style="visibility: hidden"></a>BF37 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF37">RF37 </a> / 1.0 | O sistema deve permitir realizar pesquisas de conteúdo.                                   | Sim              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B02">BRS02 </a> | ELO37   |
| <a id="anchor_BF38" style="visibility: hidden"></a>BF38 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF38">RF38 </a> / 1.0 | O sistema deve permitir denunciar comentários ofensivos.                                  | Sim              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B03">BRS03 </a> | ELO38   |
| <a id="anchor_BF39" style="visibility: hidden"></a>BF39 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF39">RF39 </a> / 1.0 | O sistema deve sugerir postagens personalizadas de acordo com as preferências do usuário. | Não              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B04">BRS04 </a> | ELO39   |
| <a id="anchor_BF40" style="visibility: hidden"></a>BF40 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RF40">RF40 </a> / 1.0 | O sistema deve permitir configurar o status online ou offline do usuário.                 | Não              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B05">BRS05 </a> | ELO40   |

<p style="text-align: center; font-size: 14px;">
    Autores: <a href="https://github.com/GenilsonJrs" target="_blank">Genilson Silva,</a> <a href="https://github.com/alanagabriele" target="_blank">Alana Gabriele,</a> <a href="https://github.com/dudupaz" target="_blank">Carlos Paz,</a> <a href="https://github.com/SamuelRicosta" target="_blank"> Samuel Ribeiro. </a>
</p>

## Tabela de Requisitos Não-Funcionais

Este seguimento é destinado para a elaboração da tabela de rastreamento de requisitos não-funcionais, que está sendo demonstrado na Tabela 2 a seguir:

#### Legendas

- **BF:** Requisitos do Backward-From
- **BRS:** Requisito Funcional do Brainstorming
- **ENT:** Requisito da Entrevista
- **INT:** Requisito da Introspecção
- **QST:** Requisito do Questionário
- **RNF:** Requisito Não Funcional

<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Requisitos não-funcionais elicitados</p></font>

| **ID**                                                  | **Requisito e Versão**                                                                  | **Descrição**                                                                                                               | **Implementado** | **Rastreabilidade**                                                      | **Elo** |
| ------------------------------------------------------- | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | ---------------- | ------------------------------------------------------------------------ | ------- |
| <a id="anchor_BF41" style="visibility: hidden"></a>BF41 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF01">RNF01 </a> / 1.0 | O sistema deve reduzir anúncios intrusivos e ajustar algoritmos para maior transparência.                                   | Não              | <a href="../../Elicitacao/tecnicas/introspeccao/#anchor_I01">INT01 </a>  | ELO41   |
| <a id="anchor_BF42" style="visibility: hidden"></a>BF42 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF02">RNF02 </a> / 1.0 | O sistema deve melhorar o algoritmo para priorizar conteúdos relevantes ao usuário.                                         | Não              | <a href="../../Elicitacao/tecnicas/introspeccao/#anchor_I02">INT02 </a>  | ELO42   |
| <a id="anchor_BF43" style="visibility: hidden"></a>BF43 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF03">RNF03 </a> / 1.0 | O sistema deve evitar a sobrecarga de notificações irrelevantes.                                                            | Não              | <a href="../../Elicitacao/tecnicas/introspeccao/#anchor_I03">INT03 </a>  | ELO43   |
| <a id="anchor_BF44" style="visibility: hidden"></a>BF44 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF04">RNF04 </a> / 1.0 | O sistema deve implementar moderação para reduzir bots e publicações irrelevantes.                                          | Sim              | <a href="../../Elicitacao/tecnicas/introspeccao/#anchor_I04">INT04 </a>  | ELO44   |
| <a id="anchor_BF45" style="visibility: hidden"></a>BF45 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF05">RNF05 </a> / 1.0 | O sistema deve oferecer autenticação avançada para segurança do usuário.                                                    | Sim              | <a href="../../Elicitacao/tecnicas/introspeccao/#anchor_I05">INT05 </a>  | ELO45   |
| <a id="anchor_BF46" style="visibility: hidden"></a>BF46 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF06">RNF06 </a> / 1.0 | O sistema deve garantir tempos de resposta inferiores a 1 segundo para interações usuais.                                   | Sim              | <a href="../../Elicitacao/tecnicas/introspeccao/#anchor_I06">INT06 </a>  | ELO46   |
| <a id="anchor_BF47" style="visibility: hidden"></a>BF47 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF07">RNF07 </a> / 1.0 | O aplicativo deve minimizar o consumo de bateria em dispositivos móveis, garantindo uma taxa de consumo inferior a 5%.      | Não              | <a href="../../Elicitacao/tecnicas/introspeccao/#anchor_I07">INT07 </a>  | ELO47   |
| <a id="anchor_BF48" style="visibility: hidden"></a>BF48 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF08">RNF08 </a> / 1.0 | O sistema deve ser compatível com dispositivos móveis de versões Android 8.0 e iOS 12 ou superiores.                        | Sim              | <a href="../../Elicitacao/tecnicas/introspeccao/#anchor_I08">INT08 </a>  | ELO48   |
| <a id="anchor_BF49" style="visibility: hidden"></a>BF49 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF09">RNF09 </a> / 1.0 | O sistema deve ser compatível com versões de navegador mais antigas, garantindo funcionalidade em Chrome 70+ e Firefox 70+. | Não              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B06">BRS06 </a> | ELO49   |
| <a id="anchor_BF50" style="visibility: hidden"></a>BF50 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF10">RNF10 </a> / 1.0 | O sistema deve garantir alta disponibilidade, com menos de 1% de tempo de inatividade mensal.                               | Sim              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B07">BRS07 </a> | ELO50   |
| <a id="anchor_BF51" style="visibility: hidden"></a>BF51 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF11">RNF11 </a> / 1.0 | O sistema deve criptografar todos os dados de login e autenticação para garantir a segurança das informações.               | Sim              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B08">BRS08 </a> | ELO51   |
| <a id="anchor_BF52" style="visibility: hidden"></a>BF52 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF12">RNF12 </a> / 1.0 | O sistema deve ser otimizado para uso em dispositivos com pouca memória RAM.                                                | Não              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B09">BRS09 </a> | ELO52   |
| <a id="anchor_BF53" style="visibility: hidden"></a>BF53 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF13">RNF13 </a> / 1.0 | O sistema deve ser compatível com os navegadores mais recentes, como Google Chrome, Safari e Edge.                          | Sim              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B10">BRS10 </a> | ELO53   |
| <a id="anchor_BF54" style="visibility: hidden"></a>BF54 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF14">RNF14 </a> / 1.0 | O sistema deve garantir que o feed de publicações seja carregado rapidamente, mesmo com grande volume de conteúdo.          | Sim              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B11">BRS11 </a> | ELO54   |
| <a id="anchor_BF55" style="visibility: hidden"></a>BF55 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF15">RNF15 </a> / 1.0 | O sistema deve garantir que os dados do usuário sejam armazenados de forma segura, com backup regular.                      | Sim              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B12">BRS12 </a> | ELO55   |
| <a id="anchor_BF56" style="visibility: hidden"></a>BF56 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF16">RNF16 </a> / 1.0 | O sistema deve garantir que o conteúdo do usuário seja sempre acessível, com um tempo de recuperação abaixo de 10 segundos. | Sim              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B13">BRS13 </a> | ELO56   |
| <a id="anchor_BF57" style="visibility: hidden"></a>BF57 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF17">RNF17 </a> / 1.0 | O sistema deve permitir que o usuário configure o status online ou offline.                                                 | Não              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B14">BRS14 </a> | ELO57   |
| <a id="anchor_BF58" style="visibility: hidden"></a>BF58 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF18">RNF18 </a> / 1.0 | O sistema deve permitir a criação de listas de amigos próximos.                                                             | Não              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B15">BRS15 </a> | ELO58   |
| <a id="anchor_BF59" style="visibility: hidden"></a>BF59 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF19">RNF19 </a> / 1.0 | O sistema deve permitir respostas anônimas em discussões públicas moderadas.                                                | Não              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B16">BRS16 </a> | ELO59   |
| <a id="anchor_BF60" style="visibility: hidden"></a>BF60 | <a href="../../Elicitacao/tecnicas/requisitoselicitados/#anchor_RNF20">RNF20 </a> / 1.0 | O sistema deve permitir salvar rascunhos de postagens mesmo sem conexão.                                                    | Não              | <a href="../../Elicitacao/tecnicas/brainstorming/#anchor_B17">BRS17 </a> | ELO60   |

<p style="text-align: center; font-size: 14px;">
    Autores: <a href="https://github.com/GenilsonJrs" target="_blank">Genilson Silva,</a> <a href="https://github.com/alanagabriele" target="_blank">Alana Gabriele,</a> <a href="https://github.com/dudupaz" target="_blank">Carlos Paz,</a> <a href="https://github.com/SamuelRicosta" target="_blank"> Samuel Ribeiro. </a>
</p>

## Elos de Rastreabilidade

Os elos de rastreabilidade estabelecem conexões importantes entre os requisitos, suas origens e as dependências existentes. A tabela 3 a seguir apresenta os principais tipos de elos identificados no projeto Threads, com suas respectivas descrições:

Cada membro do grupo ficou responsável por documentar ao menos 5 requisitos funcionais e 1 requisito não-funcional, garantindo a elaboração dos elos de rastreabilidade. Isso promoveu uma divisão equitativa das tarefas e uma visão abrangente do projeto Threads.

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

- **ID BF:** Identificador do Backward-From relacionado

<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Elos de rastreabilidade</p></font>

| ID    | ID BF                                                   | Tipo de Elo | Descrição do Elo                                                                                                                    |
| ----- | ------------------------------------------------------- | ----------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| ELO01 | [BF01](../../Rastreabilidade/backwardFrom/#anchor_BF01) | ES          | Relaciona o requisito de configuração de visibilidade a componentes responsáveis por gerenciar privacidade.                         |
| ELO02 | [BF02](../../Rastreabilidade/backwardFrom/#anchor_BF02) | IM          | Representa a conexão entre o requisito de gravação de mensagens de voz e o módulo de captura de áudio.                              |
| ELO03 | [BF03](../../Rastreabilidade/backwardFrom/#anchor_BF03) | IP          | Indica o impacto da implementação dos Trend Topics em outros módulos, como feed principal.                                          |
| ELO04 | [BF04](../../Rastreabilidade/backwardFrom/#anchor_BF04) | RJ          | Justifica a criação do requisito de temas escuro e claro com base em pesquisas de usabilidade.                                      |
| ELO05 | [BF05](../../Rastreabilidade/backwardFrom/#anchor_BF05) | IV          | Valida a funcionalidade da área de mensagens privadas com base em testes de segurança e usabilidade.                                |
| ELO06 | [BF06](../../Rastreabilidade/backwardFrom/#anchor_BF06) | IM          | Liga o requisito de verificação de contas ao módulo de autenticação do sistema.                                                     |
| ELO07 | [BF07](../../Rastreabilidade/backwardFrom/#anchor_BF07) | ED          | Relaciona a tradução automática a módulos de IA e serviços de tradução integrados.                                                  |
| ELO08 | [BF08](../../Rastreabilidade/backwardFrom/#anchor_BF08) | IP          | Mostra como a redução de anúncios afeta a experiência do usuário e os algoritmos de sugestão.                                       |
| ELO09 | [BF09](../../Rastreabilidade/backwardFrom/#anchor_BF09) | IV          | Valida o requisito de moderação com base em testes de detecção de bots.                                                             |
| ELO10 | [BF10](../../Rastreabilidade/backwardFrom/#anchor_BF10) | IM          | Conecta o upload de vídeos em alta definição ao componente de armazenamento e compressão.                                           |
| ELO11 | [BF11](../../Rastreabilidade/backwardFrom/#anchor_BF11) | RJ          | Justifica o requisito de confirmação visual para evitar erros nas ações realizadas.                                                 |
| ELO12 | [BF12](../../Rastreabilidade/backwardFrom/#anchor_BF12) | ER          | Descreve como o requisito de histórico de interações evoluiu desde versões iniciais.                                                |
| ELO13 | [BF13](../../Rastreabilidade/backwardFrom/#anchor_BF13) | RJ          | Explica a criação do requisito de respostas anônimas para promover discussões mais inclusivas.                                      |
| ELO14 | [BF14](../../Rastreabilidade/backwardFrom/#anchor_BF14) | ES          | Relaciona o requisito de salvar postagens ao sistema de armazenamento local.                                                        |
| ELO15 | [BF15](../../Rastreabilidade/backwardFrom/#anchor_BF15) | IV          | Valida a sugestão de usuários com base em testes de recomendação.                                                                   |
| ELO16 | [BF16](../../Rastreabilidade/backwardFrom/#anchor_BF16) | IM          | Liga a funcionalidade de criação de enquetes ao módulo de interatividade.                                                           |
| ELO17 | [BF17](../../Rastreabilidade/backwardFrom/#anchor_BF17) | RJ          | Justifica o requisito de denúncias para aumentar a segurança do ambiente.                                                           |
| ELO18 | [BF18](../../Rastreabilidade/backwardFrom/#anchor_BF18) | ED          | Relaciona o requisito de ocultar publicações à funcionalidade de gestão de perfil.                                                  |
| ELO19 | [BF19](../../Rastreabilidade/backwardFrom/#anchor_BF19) | ES          | Conecta o backup e restauração de dados ao módulo de armazenamento em nuvem.                                                        |
| ELO20 | [BF20](../../Rastreabilidade/backwardFrom/#anchor_BF20) | ED          | Mostra como o filtro de conteúdos depende do sistema de categorização.                                                              |
| ELO21 | [BF21](../../Rastreabilidade/backwardFrom/#anchor_BF21) | IM          | Relaciona a adição de legendas automáticas ao módulo de processamento de mídia.                                                     |
| ELO22 | [BF22](../../Rastreabilidade/backwardFrom/#anchor_BF22) | RJ          | Justifica o uso de IA para sugerir textos com base em aumento de engajamento.                                                       |
| ELO23 | [BF23](../../Rastreabilidade/backwardFrom/#anchor_BF23) | IV          | Valida as reações variadas em publicações com base em testes de interação.                                                          |
| ELO24 | [BF24](../../Rastreabilidade/backwardFrom/#anchor_BF24) | IM          | Conecta o requisito de salvar rascunhos offline ao sistema de armazenamento local.                                                  |
| ELO25 | [BF25](../../Rastreabilidade/backwardFrom/#anchor_BF25) | ED          | Relaciona o agendamento de postagens ao módulo de gerenciamento de tempo.                                                           |
| ELO26 | [BF26](../../Rastreabilidade/backwardFrom/#anchor_BF26) | RJ          | Justifica o compartilhamento de postagens externas com base em estudos de integração social.                                        |
| ELO27 | [BF27](../../Rastreabilidade/backwardFrom/#anchor_BF27) | IM          | Relaciona a criação de comunidades ao módulo de gestão de grupos.                                                                   |
| ELO28 | [BF28](../../Rastreabilidade/backwardFrom/#anchor_BF28) | IP          | Indica como a gestão de múltiplas contas impacta outros componentes de login.                                                       |
| ELO29 | [BF29](../../Rastreabilidade/backwardFrom/#anchor_BF29) | IV          | Valida a autenticação avançada com base em testes de segurança.                                                                     |
| ELO30 | [BF30](../../Rastreabilidade/backwardFrom/#anchor_BF30) | RJ          | Justifica o requisito de fixar postagens no perfil para maior visibilidade.                                                         |
| ELO31 | [BF31](../../Rastreabilidade/backwardFrom/#anchor_BF31) | ED          | Relaciona a edição de publicações ao módulo de edição de conteúdo.                                                                  |
| ELO32 | [BF32](../../Rastreabilidade/backwardFrom/#anchor_BF32) | IM          | Conecta a marcação de usuários ao módulo de interatividade social.                                                                  |
| ELO33 | [BF33](../../Rastreabilidade/backwardFrom/#anchor_BF33) | IV          | Valida as estatísticas detalhadas com base em relatórios analíticos.                                                                |
| ELO34 | [BF34](../../Rastreabilidade/backwardFrom/#anchor_BF34) | RJ          | Justifica os alertas de menções com base em feedback de usuários.                                                                   |
| ELO35 | [BF35](../../Rastreabilidade/backwardFrom/#anchor_BF35) | IM          | Relaciona as reações a comentários ao módulo de interações.                                                                         |
| ELO36 | [BF36](../../Rastreabilidade/backwardFrom/#anchor_BF36) | ED          | Mostra como as listas de amigos próximos dependem do sistema de preferências.                                                       |
| ELO37 | [BF37](../../Rastreabilidade/backwardFrom/#anchor_BF37) | IM          | Conecta as pesquisas de conteúdo ao sistema de busca do aplicativo.                                                                 |
| ELO38 | [BF38](../../Rastreabilidade/backwardFrom/#anchor_BF38) | IV          | Valida a denúncia de comentários ofensivos com base em testes de moderação.                                                         |
| ELO39 | [BF39](../../Rastreabilidade/backwardFrom/#anchor_BF39) | RJ          | Justifica as postagens personalizadas com base em algoritmos de recomendação.                                                       |
| ELO40 | [BF40](../../Rastreabilidade/backwardFrom/#anchor_BF40) | IV          | Valida o status online/offline com base em testes de estado de usuário.                                                             |
| ELO41 | [BF41](../../Rastreabilidade/backwardFrom/#anchor_BF41) | IP          | Mostra o impacto da redução de anúncios na performance e na experiência do usuário.                                                 |
| ELO42 | [BF42](../../Rastreabilidade/backwardFrom/#anchor_BF42) | RJ          | Justifica a melhoria do algoritmo para priorização de conteúdos relevantes, baseada em feedbacks dos usuários.                      |
| ELO43 | [BF43](../../Rastreabilidade/backwardFrom/#anchor_BF43) | IV          | Valida o requisito de evitar sobrecarga de notificações por meio de testes de notificações em cenários de alta carga.               |
| ELO44 | [BF44](../../Rastreabilidade/backwardFrom/#anchor_BF44) | IM          | Conecta a moderação para redução de bots ao módulo de inteligência artificial responsável pela análise de comportamentos suspeitos. |
| ELO45 | [BF45](../../Rastreabilidade/backwardFrom/#anchor_BF45) | IV          | Valida a implementação de autenticação avançada com testes de segurança, como análise de vulnerabilidades.                          |
| ELO46 | [BF46](../../Rastreabilidade/backwardFrom/#anchor_BF46) | IM          | Relaciona o requisito de tempos de resposta inferiores a 1 segundo ao subsistema de otimização de consultas no banco de dados.      |
| ELO47 | [BF47](../../Rastreabilidade/backwardFrom/#anchor_BF47) | RJ          | Justifica a criação do requisito de economia de bateria para melhorar a experiência em dispositivos móveis.                         |
| ELO48 | [BF48](../../Rastreabilidade/backwardFrom/#anchor_BF48) | ES          | Relaciona o requisito de compatibilidade com versões Android e iOS ao módulo de adaptação de sistema operacional.                   |
| ELO49 | [BF49](../../Rastreabilidade/backwardFrom/#anchor_BF49) | ED          | Relaciona a compatibilidade com navegadores antigos ao suporte de APIs e frameworks de versões legadas.                             |
| ELO50 | [BF50](../../Rastreabilidade/backwardFrom/#anchor_BF50) | ER          | Mostra a evolução do requisito de alta disponibilidade desde o conceito inicial até sua implementação atual.                        |
| ELO51 | [BF51](../../Rastreabilidade/backwardFrom/#anchor_BF51) | RJ          | Justifica o requisito de design acessível baseado nas diretrizes de acessibilidade universal.                                       |
| ELO52 | [BF52](../../Rastreabilidade/backwardFrom/#anchor_BF52) | IV          | Valida a funcionalidade de backup de dados por meio de testes em cenários de falha do sistema.                                      |
| ELO53 | [BF53](../../Rastreabilidade/backwardFrom/#anchor_BF53) | ES          | Relaciona o requisito de personalização de notificações ao subsistema de gestão de preferências de usuário.                         |
| ELO54 | [BF54](../../Rastreabilidade/backwardFrom/#anchor_BF54) | IM          | Conecta a funcionalidade de reações de emoji ao módulo de resposta interativa.                                                      |
| ELO55 | [BF55](../../Rastreabilidade/backwardFrom/#anchor_BF55) | IV          | Valida a implementação de moderação em tempo real com base em algoritmos de análise de conteúdo.                                    |

<p style="text-align: center; font-size: 14px;">
    Autores: <a href="https://github.com/GenilsonJrs" target="_blank">Genilson Silva,</a> <a href="https://github.com/alanagabriele" target="_blank">Alana Gabriele,</a> <a href="https://github.com/dudupaz" target="_blank">Carlos Paz,</a> <a href="https://github.com/SamuelRicosta" target="_blank"> Samuel Ribeiro. </a>
</p>

## Conclusão

Este trabalho descreveu a aplicação da rastreabilidade de requisitos no desenvolvimento do aplicativo Threads, utilizando a técnica Backward-From. Foram identificados e mapeados diversos elos de rastreabilidade, que abrangem diferentes aspectos dos requisitos, como suas origens, dependências, evolução e justificativas. Esses elos proporcionaram uma visão clara das inter-relações entre os requisitos e os componentes do sistema, garantindo que os requisitos estivessem alinhados aos objetivos do projeto e atendendo às expectativas dos stakeholders. A metodologia aplicada contribuiu para assegurar a consistência, completude e qualidade dos requisitos, promovendo um gerenciamento eficiente das mudanças e impactos ao longo do ciclo de desenvolvimento.

## Referência

PUC-Rio. **Rastreabilidade de requisitos: fundamentos e técnicas**. Disponível em: [https://www.dbd.puc-rio.br/pergamum/tesesabertas/1121794_2014_cap_2.pdf](https://www.dbd.puc-rio.br/pergamum/tesesabertas/1121794_2014_cap_2.pdf). Acesso em: 17 jan. 2025.

## Histórico de Versões

| Versão | Data       | Descrição                           | Autor                                                                                                                                                                                                  | Revisor                                            |
| :----: | ---------- | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------- |
|  1.0   | 17/01/2025 | Criação do documento                | [Samuel Ribeiro](https://github.com/SamuelRicosta)                                                                                                                                                     | [Alana Gabriele](https://github.com/alanagabriele) |
|  1.2   | 18/01/2025 | Adição das tabelas                  | [Genilson Silva](https://github.com/GenilsonJrs)                                                                                                                                                       | [Alana Gabriele](https://github.com/alanagabriele) |
|  1.3   | 19/01/2025 | Adição da tabela Elo                | [Carlos Eduardo](https://github.com/dudupaz), [Samuel Ribeiro](https://github.com/SamuelRicosta), [Alana Gabriele](https://github.com/alanagabriele), [Genilson Silva](https://github.com/GenilsonJrs) | [Alana Gabriele](https://github.com/alanagabriele) |
|  1.4   | 19/01/2025 | Adição dos links de rastreabilidade | [Genilson Silva](https://github.com/GenilsonJrs)                                                                                                                                                       | [Alana Gabriele](https://github.com/alanagabriele) |
