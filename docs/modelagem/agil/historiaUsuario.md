## Introdução

## Metodologia

<font size="2"><p style="text-align: center">Tabela 1 - Modelo </p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Título</th>
 <td>Criterio de Aceitação</td>
 <td>Prioridade</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>USX</td>
      <td>Eu, como xxx, posso xxx para xxx</td>
       <td> Lista com os critérios de aceitação <br>
       <b> Critério y - xxx </b> <br>
        <b>Dado</b> xxx <br>
         <b>Quando</b> xxx <br> 
         <b>E</b> xxx<br>
        <b> Então</b> xxx
      </td>
      <td>Alta, média ou baixa</td>
    </tr>
  </tbody>
</table>

<p style="text-align: center; font-size: 14px;">
    Autor: <a href="https://github.com/alanagabriele" target="_blank">Alana Gabriele</a>
  </p>

## Histórias de Usuário

<details>
  <summary>US01 - Configurar a visibilidade da conta como pública ou privada</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 2 - Configurar visibilidade</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US01</td>
        <td>Eu, como usuário, posso configurar a visibilidade da minha conta como pública ou privada para controlar quem pode ver minhas publicações.</td>
        <td>
          <b>Critério 1 - Configuração de Visibilidade</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu acessar as configurações da conta, <br>
          <b>E</b> selecionar a opção de visibilidade, <br>
          <b>Então</b> minha conta deve ser marcada como pública ou privada com base na minha escolha. <br><br>
          <b>Critério 2 - Indicação Visual</b> <br>
          <b>Dado</b> que a visibilidade da minha conta está configurada como privada, <br>
          <b>Quando</b> outro usuário tentar acessar meu perfil, <br>
          <b>Então</b> ele deve visualizar uma mensagem indicando que o perfil é privado.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US02 - Gravar e enviar mensagens de voz diretamente em uma thread</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 3 - Mensagens de voz</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US02</td>
        <td>Eu, como usuário, posso gravar e enviar mensagens de voz diretamente em uma postagem ou como resposta a um comentário para compartilhar ideias rapidamente.</td>
        <td>
          <b>Critério 1 - Gravação de Voz</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu acessar uma thread ou comentário, <br>
          <b>E</b> clicar no botão de gravação, <br>
          <b>Então</b> o sistema deve iniciar a gravação de uma mensagem de voz. <br><br>
          <b>Critério 2 - Envio de Voz</b> <br>
          <b>Dado</b> que gravei uma mensagem de voz, <br>
          <b>Quando</b> eu clicar no botão de envio, <br>
          <b>Então</b> a mensagem de voz deve ser anexada à postagem ou ao comentário correspondente.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US03 - Visualizar Trend Topics</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 4 - Trend Topics</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US03</td>
        <td>Eu, como usuário, posso visualizar os assuntos mais discutidos em uma lista de Trend Topics para identificar rapidamente tópicos populares.</td>
        <td>
          <b>Critério 1 - Exibição de Tendências</b> <br>
          <b>Dado</b> que existem tópicos populares no sistema, <br>
          <b>Quando</b> eu acessar a página inicial, <br>
          <b>Então</b> devo visualizar uma lista com os Trend Topics atualizados. <br><br>
          <b>Critério 2 - Atualização em Tempo Real</b> <br>
          <b>Dado</b> que um novo tópico se torna popular, <br>
          <b>Quando</b> ele atingir o volume necessário, <br>
          <b>Então</b> ele deve ser incluído automaticamente na lista de tendências.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US04 - Verificar contas com número de telefone e email cadastrados</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 5 - Verificação de contas</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US04</td>
        <td>Eu, como usuário, posso verificar minha conta com número de telefone e email cadastrados para aumentar a segurança do meu perfil.</td>
        <td>
          <b>Critério 1 - Verificação de Telefone</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu informar meu número de telefone, <br>
          <b>E</b> receber um código de verificação, <br>
          <b>Então</b> devo conseguir validar minha conta inserindo o código corretamente. <br><br>
          <b>Critério 2 - Verificação de Email</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu informar meu email, <br>
          <b>E</b> receber um código de verificação, <br>
          <b>Então</b> devo conseguir validar minha conta inserindo o código corretamente.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US05 - Responder anonimamente em discussões públicas moderadas</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 6 - Respostas Anônimas</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US05</td>
        <td>Eu, como usuário, posso responder anonimamente em discussões públicas moderadas para compartilhar opiniões sem revelar minha identidade.</td>
        <td>
          <b>Critério 1 - Resposta Anônima</b> <br>
          <b>Dado</b> que estou participando de uma discussão pública moderada, <br>
          <b>Quando</b> eu optar por responder anonimamente, <br>
          <b>Então</b> minha resposta deve ser exibida sem associar meu perfil ao conteúdo publicado. <br><br>
          <b>Critério 2 - Moderação de Respostas</b> <br>
          <b>Dado</b> que respondi anonimamente, <br>
          <b>Quando</b> minha resposta for publicada, <br>
          <b>Então</b> ela deve passar por moderação antes de ser exibida publicamente.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US06 - Tradução automática de publicações</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 7 - Tradução Automática</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US06</td>
        <td>Eu, como usuário, posso traduzir automaticamente publicações para meu idioma preferido para entender conteúdos em outros idiomas.</td>
        <td>
          <b>Critério 1 - Tradução Automática</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu acessar uma publicação em outro idioma, <br>
          <b>E</b> clicar no botão de traduzir, <br>
          <b>Então</b> o sistema deve exibir a publicação traduzida no idioma configurado.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US07 - Reduzir anúncios intrusivos e ajustar algoritmos para maior transparência</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 8 - Anúncios e Algoritmos</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US07</td>
        <td>Eu, como usuário, desejo que os anúncios sejam menos intrusivos e os algoritmos mais transparentes para melhorar minha experiência.</td>
        <td>
          <b>Critério 1 - Redução de Anúncios</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu navegar pelo feed, <br>
          <b>Então</b> devo visualizar anúncios em menor frequência e com menor impacto visual. <br><br>
          <b>Critério 2 - Algoritmos Transparentes</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu interagir com publicações, <br>
          <b>Então</b> devo ser informado de como minha interação influencia as recomendações futuras.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US08 - Implementar moderação para reduzir bots e publicações irrelevantes</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 9 - Moderação de Bots e Conteúdo</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US08</td>
        <td>Eu, como administrador, posso moderar publicações para reduzir bots e publicações irrelevantes.</td>
        <td>
          <b>Critério 1 - Detecção de Bots</b> <br>
          <b>Dado</b> que sou administrador, <br>
          <b>Quando</b> eu identificar contas com comportamento suspeito, <br>
          <b>Então</b> devo ter ferramentas para revisar e excluir essas contas. <br><br>
          <b>Critério 2 - Moderação de Conteúdo</b> <br>
          <b>Dado</b> que sou administrador, <br>
          <b>Quando</b> eu revisar publicações, <br>
          <b>Então</b> devo poder marcar conteúdos irrelevantes para remoção ou revisão.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US09 - Upload de vídeos em alta definição</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 10 - Upload de Vídeos</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US09</td>
        <td>Eu, como usuário, posso fazer upload de vídeos em alta definição para compartilhar conteúdos de qualidade.</td>
        <td>
          <b>Critério 1 - Upload de Vídeos</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu clicar no botão de upload de vídeo, <br>
          <b>Então</b> devo conseguir selecionar e enviar vídeos em alta definição para o sistema. <br><br>
          <b>Critério 2 - Qualidade do Vídeo</b> <br>
          <b>Dado</b> que enviei um vídeo, <br>
          <b>Quando</b> ele for reproduzido no sistema, <br>
          <b>Então</b> a qualidade original do vídeo deve ser mantida.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US10 - Exibir confirmação visual para ações do usuário</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 11 - Confirmação Visual</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US11</td>
        <td>Eu, como usuário, quero visualizar uma confirmação visual ao interagir com uma postagem para ter certeza de que minha ação foi concluída.</td>
        <td>
          <b>Critério 1 - Confirmação de Curtir</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu clicar no botão de curtir em uma publicação, <br>
          <b>Então</b> o sistema deve exibir uma animação de preenchimento do ícone de curtida. <br><br>
          <b>Critério 2 - Confirmação de Salvar</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu clicar no botão de salvar uma publicação, <br>
          <b>Então</b> o sistema deve exibir um alerta de sucesso informando que o conteúdo foi salvo. <br><br>
          <b>Critério 3 - Confirmação de Compartilhar</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu clicar no botão de compartilhar uma publicação, <br>
          <b>Então</b> o sistema deve exibir uma mensagem indicando que o link ou conteúdo foi copiado ou enviado.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<p style="text-align: center; font-size: 14px;">
    Autor: <a href="https://github.com/alanagabriele" target="_blank">Alana Gabriele</a>
</p>

## Referências

> SERRANO, Milene e Maurício. Requisitos - Aula 15. Disponível em: [https://aprender3.unb.br/pluginfile.php/2972504/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf](https://aprender3.unb.br/pluginfile.php/2972504/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf).

> Ministério da agricultura, Pecuária e Abastecimento. Template Estoria de Usuário. Disponível em: [https://www.gov.br/agricultura/pt-br/acesso-a-informacao/licitacoes-e-contratos/edital/2019/pregao-eletronico-no-05-2018/templates-artefatos/estoria-de-usuario.doc/view](https://www.gov.br/agricultura/pt-br/acesso-a-informacao/licitacoes-e-contratos/edital/2019/pregao-eletronico-no-05-2018/templates-artefatos/estoria-de-usuario.doc/view)

## Histórico de Versões

| Versão | Data       | Descrição           | Autor                                              | Revisor                                      |
| :----: | ---------- | ------------------- | -------------------------------------------------- | -------------------------------------------- |
|  1.0   | 16/12/2024 | História do usuário | [Alana Gabriele](https://github.com/alanagabriele) | [Carlos Eduardo](https://github.com/dudupaz) |