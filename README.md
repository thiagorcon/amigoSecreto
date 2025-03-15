# Desafio Amigo Secreto - Projeto JavaScript

Este repositório contém o código do projeto **Amigo Secreto**, desenvolvido como parte de um desafio de programação. O objetivo do projeto era criar uma aplicação web simples que permitisse aos usuários adicionar nomes à lista de amigos, e então, ao clicar em um botão, realizar um sorteio aleatório para definir o "amigo secreto" de cada pessoa.

## Desafios e Aprendizados

Durante o desenvolvimento deste projeto, enfrentei alguns desafios técnicos que exigiram soluções criativas. Abaixo estão os principais pontos do processo de desenvolvimento:

### 1. **Estrutura do HTML**
   - **Desafio**: Criar uma estrutura HTML básica para capturar entradas dos usuários e exibir os resultados.
   - **Solução**: Comecei com a criação de um formulário simples contendo um campo de texto para inserir o nome de amigos, um botão para adicionar os nomes à lista, uma lista não ordenada (`<ul>`) para exibir os amigos e outro botão para realizar o sorteio.
   - **Aprendizado**: Compreendi a importância de uma estrutura limpa e intuitiva para interação com o usuário.

### 2. **Adicionando Amigos à Lista com JavaScript**
   - **Desafio**: Criar uma função em JavaScript que permitisse ao usuário adicionar nomes à lista ao clicar no botão "Adicionar".
   - **Solução**: Utilizei o método `.push()` para adicionar o nome inserido a um array (`amigos[]`). A entrada foi validada para garantir que o campo não estivesse vazio. Após a adição, o campo de entrada foi limpo para uma nova inserção.
   - **Aprendizado**: Aprendi como manipular eventos no DOM e como trabalhar com arrays em JavaScript.

### 3. **Exibindo a Lista de Amigos**
   - **Desafio**: Atualizar a lista de amigos na interface sempre que um nome fosse adicionado.
   - **Solução**: Criei uma função para percorrer o array de amigos e adicionar cada nome como um item (`<li>`) dentro de uma lista HTML. Utilizei `innerHTML` para atualizar a lista de amigos e garantir que não houvesse duplicação.
   - **Aprendizado**: Foi uma boa prática de manipulação do DOM, onde entendi como adicionar elementos dinamicamente a uma página web.

### 4. **Sortear um Amigo Secreto Aleatório**
   - **Desafio**: Implementar a lógica para sortear aleatoriamente um amigo da lista.
   - **Solução**: Utilize o método `Math.random()` para gerar um número aleatório e `Math.floor()` para arredondar esse número para o índice do array. Em seguida, obtive o nome correspondente e exibi o resultado na página.
   - **Aprendizado**: Aprendi como gerar números aleatórios em JavaScript e utilizá-los para manipulação de dados em arrays.

### 5. **Problema com Git**
   - **Desafio**: Durante o processo de versionamento, encontrei dificuldades ao tentar usar comandos Git, como `git add`, `git commit`, e `git push`. O Git apresentava erros sobre branches não existentes e problemas ao tentar enviar o código para o repositório remoto.
   - **Solução**: Resolvi os problemas configurando corretamente o repositório remoto com `git remote add origin <URL-do-repositório>`. Além disso, após algumas tentativas de usar o comando `git push`, consegui corrigir o nome do branch e realizar o envio do código com o comando adequado.
   - **Aprendizado**: O erro inicial me ensinou a importância de sempre verificar o nome do branch e a configuração do repositório remoto antes de usar o `git push`.

### 6. **Problema ao Tentar Fazer Push para `main`**
   - **Desafio**: Durante o processo de envio para o repositório remoto, recebi a mensagem de erro **"src refspec main does not match any"**.
   - **Solução**: A solução foi verificar se o branch correto estava sendo usado no meu repositório local. Eu estava tentando fazer o push para o branch `main`, mas o meu repositório estava no branch `master`. Então, alterei o nome do branch para `main` ou fiz o push diretamente para `master`.
   - **Aprendizado**: Aprendi a diferença entre os branches `master` e `main`, e como corrigir esse tipo de erro com o Git.

### 7. **Erro "origin does not appear to be a git repository"**
   - **Desafio**: Ao tentar fazer o push para o repositório remoto, encontrei o erro **"fatal: 'origin' does not appear to be a git repository"**.
   - **Solução**: Isso ocorreu porque eu não havia configurado um repositório remoto corretamente. O erro foi corrigido configurando o repositório remoto com o comando `git remote add origin <URL-do-repositório>`.
   - **Aprendizado**: Aprendi como adicionar corretamente o repositório remoto e como verificar a configuração com `git remote -v`.

### 8. **Deploy e Envio para o Repositório GitHub**
   - **Desafio**: Enviar o código para o repositório GitHub de forma organizada e sem realizar o deploy de um site.
   - **Solução**: Segui a instrução de enviar apenas o **link do repositório GitHub** sem me preocupar com o deploy do site, como o desafio pedia. Isso garantiu que o código estivesse visível e acessível para revisão, sem complicações com deploys desnecessários.
   - **Aprendizado**: Compreendi a importância de organizar o código no GitHub de maneira limpa e sem necessidade de serviços de deploy para este tipo de desafio.

## Tecnologias Utilizadas

- **HTML**: Estrutura básica da página web.
- **CSS**: Estilização para tornar a página mais atrativa.
- **JavaScript**: Implementação da lógica de adicionar amigos e sortear aleatoriamente o amigo secreto.
- **Git**: Versionamento de código e controle de alterações.

## Como Rodar o Projeto

Para rodar este projeto localmente em seu computador, siga os passos abaixo:

1. Clone este repositório:
   ```bash
   git clone https://github.com/usuario/nome-do-repositorio.git
# amigoSecreto
