Estudo dos comandos git, através do vídeo da Rocketseat

https://www.youtube.com/watch?v=2alg7MQ6_sI&t=33s

Conteúdos abordados:

- Você deseja criar pontos na história da produção do seu projeto

- Você deseja verificar mudanças feitas no seu projeto

  

- Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.
- Você adiciona as novas funcionalidades ao seu projeto em produção.
- Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.
- Você quer colocar o projeto na nuvem
- Você vai pegar um projeto já iniciado, para trabalhar com o time
- Você precisa resolver um conflito
- Antes de enviar a resolução, precisamos atualizar o projeto local.





-------

Comandos:

git add <nome do arquivo> - Adiciona o arquivo ou as alterações do arquivo ao projeto. Para inserir todos os arquivos e alterações, é possível colocar o ponto "." ao invés do nome do arquivo.

git commit -m "<mensagem>" - cria o ponto da história do projeto

git log - exibe os pontos da história do projeto

git status - Verifica a situação dos arquivos que estão no projeto e se algum arquivo não foi inserido.

*Ao realizar uma alteração, é necessário informar ao git que a alteração será válida, utilizando o git add. Em seguida usar o git commit para acrescentar ao projeto*

git show <hash do ponto da história> - visualiza as ações realizadas naquele ponto da história, como por exemplo o acréscimo ou remoção de uma informação. Caso seja colocado sem o hash, será exibida apenas o último ponto da história

branch: é uma ramificação do seu projeto. Cada projeto costumam ter várias ramificações, conforme a conveniência.

git branch <nome da ramificação> - cria uma nova ramificação no projeto.

git checkout <localização> - permite navegar entre os pontos da história ou ramificações.

git branch -D <nome da ramificação> - remove a branch do projeto.

git remote add <projeto> <endereço remoto> - vincula um repositório remoto

git remote - v - exibe os mapeamentos dos repositórios remotos

git push <projeto> <ramificação> - envia o repositório local para o repositório remoto

git clone <endereço> - copia um projeto remoto para o seu repositório local

git commit -am "<comentário>" - realizar o git add .  e commit ao mesmo tempo.