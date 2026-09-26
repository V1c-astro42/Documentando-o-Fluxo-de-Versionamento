# O Passo a Passo da Criação e Envio de um porjeto

Para criar um repositório no GitHub é bem simples. Primeiramente, você deve acessar sua conta do GitHub e clicar no **“+”** que aparece na parte de cima da página. Depois, selecione a opção **“Novo repositório”**.

Em seguida, você deve escolher um nome para o projeto e, se necessário, adicionar uma breve descrição para explicar qual é o objetivo dele. Também é necessário escolher se o repositório será **público** ou **privado**.

Na criação do repositório, existe a opção de ativar o README, aperte o botaão para ativá-lo.

Depois de conferir todas as configurações, basta clicar em **“Criar repositório”**. Assim, o repositório estará criado e pronto para receber os arquivos do projeto.

![imagem para identificar o "+"](imagem/CriarMais.png)

Depois de criar o repositório no GitHub, é necessário conectar ele a uma pasta do seu computador, onde estão os arquivos do projeto. Para isso, abra a pasta do projeto no VS Code e acesse o terminal. Em seguida, utilize os comandos do Git para iniciar o controle de versão da pasta e conectá-la ao repositório criado no GitHub:

Primeiro, utilize o comando "git init", que inicia o Git dentro da pasta do projeto. Depois, copie o link do meu repositório no GitHub e utilize o comando "git remote add origin", seguido do link, para estabelecer a conexão entre a pasta local e o repositório remoto.

Dessa forma, o Git passa a reconhecer a pasta do seu computador como um projeto que pode ser conectado ao GitHub, permitindo que você envie os arquivos e futuras alterações para a nuvem.

Por fim, para enviar os arquivos da sua máquina para o GitHub, acesse o repositório e clique no “+”, depois selecione a opção “Upload files”. Em seguida, escolha os arquivos que quer adicionar e finalize clicando em “Commit changes”. Depois disso, os arquivos ficam disponíveis na página do repositório.

![imagem para identificar o "+"](imagem/Arquivos.png)

***

#  A Anatomia do README Perfeito


O README.md é um documento importante porque funciona como uma apresentação e o guia do projeto. Ele ajuda outras pessoas a entenderem rapidamente qual é o objetivo do projeto, quais tecnologias foram utilizadas e como ele pode ser instalado ou utilizado. Além disso, uma documentação bem organizada facilita a compreensão e a colaboração entre as pessoas que trabalham no projeto.
O arquivo "README.md" serve para apresentar e explicar um projeto. Ele funciona como uma espécie de guia para que outras pessoas consigam entender o que é o projeto, para que ele serve e como utilizá-lo. O público-alvo pode ser outras pessoas que tenham acesso ao projeto, como professores, colegas, desenvolvedores ou até pessoas que tenham interesse em conhecer o projeto.

Um README profissional deve conter algumas informações importantes, como:

* **Título:** identifica o nome do projeto.
* **Descrição:** explica de forma resumida o que é o projeto e qual é o seu objetivo.
* **Tecnologias utilizadas:** informa quais linguagens, ferramentas ou tecnologias foram usadas no desenvolvimento.
* **Como instalar e executar:** apresenta os passos necessários para instalar e utilizar o projeto.
* **Status do projeto:** mostra se o projeto está em desenvolvimento, concluído ou se ainda possui melhorias a serem feitas.
* **Licença:** informa as regras de uso, alteração e distribuição do projeto.

No desenvolvimento de um README é importante o uso de Markdown, pois permite organizar o conteúdo de forma simples, utilizando símbolos e comandos para criar títulos, listas, textos em destaque, links, imagens e outros elementos. Isso deixa o documento mais organizado e facilita a leitura, fazendo com que as informações importantes sejam encontradas com mais facilidade.


***

# O Mapa das Atualizações (Commits e Pushes)

Existem várias portas de entrada para atualizar o seu código. Você deve descrever as diferentes possibilidades e ferramentas para enviar atualizações para um repositório, comparando-as com suas próprias palavras:

A Filosofia da Atualização: Finalize o texto explicando por que é crucial atualizar o repositório continuamente e em pequenas partes, em vez de enviar tudo de uma só vez no final do mês.


Existem diferentes formas de atualizar um projeto no GitHub, e cada uma pode ser mais adequada dependendo da situação.

**GitHub Online:** uma forma simples de atualizar um arquivo é acessar o repositório pelo navegador, abrir o arquivo que deseja modificar e clicar na opção de edição. Depois de fazer as alterações, basta salvá-las por meio de um **commit**. Essa opção é útil para pequenas alterações e correções rápidas, mas pode ser limitada para projetos maiores, pois não oferece a mesma praticidade de um editor de código.

**Git via Linha de Comando (Terminal):** pelo terminal, é possível controlar as atualizações utilizando comandos do Git. Depois de alterar os arquivos, normalmente o fluxo envolve adicionar as alterações com `git add`, registrá-las com `git commit` e enviá-las para o GitHub com `git push`. Essa é uma das formas mais tradicionais porque permite ter um controle maior sobre as alterações e pode ser utilizada em diferentes ambientes.

**IDEs, como o VS Code:** o VS Code possui uma interface gráfica que facilita o uso do Git. Por ela, é possível visualizar os arquivos que foram alterados, selecionar as mudanças, fazer o **commit** e depois realizar o **push**, sem precisar digitar todos os comandos no terminal. Na minha experiência, essa forma é mais visual e facilita bastante a organização das alterações.

**GitHub Desktop:** é uma ferramenta criada para facilitar o uso do Git por meio de uma interface gráfica. Ela permite visualizar quais arquivos foram modificados, comparar as alterações, criar commits e enviar as mudanças para o GitHub. Dessa forma, não é necessário utilizar o terminal para realizar essas ações.

**IMPORTANTE:** Sempre atualize o repositório de forma continua e em pequenas partes, pois isso mantém o projeto organizado e facilita o acompanhamento do desenvolvimento. Fazer commits menores também ajuda a identificar quando uma alteração causou algum problema e facilita a correção. Se todas as mudanças forem enviadas de uma só vez no final do mês, fica muito mais difícil entender o que foi alterado e encontrar possíveis erros.
