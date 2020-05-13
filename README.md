Esse é um projeto para o conteúdo da semana 16, sobre `RTL`.

### Antes de iniciar

Crie um fork desse projeto, para isso siga esse [tutorial de como realizar um fork](https://github.com/facebook/create-react-app).

Ápos feito o fork, clone o repositório criado para o seu computador.

Rode o `npm install`.

Vá para a branch master do seu projeto e execute o comando:
- `git branch`, verifique se apareceu as branches:

  `exercise-one`
  `exercise-two`
  `exercise-three`

- Cada branch dessas será um exercício.
- Mude para a branch `exercise-one`: `git checkout exercise-one`. Nessa branch é onde vocẽ realizará a solução para o exercício 1, e assim por diante.

Observe o que deve ser feito nas instruções para cada exercício.

Ápos a solução dos exercícios, abra um PR no repositório, se quiser pode merger para a master, fique livre!

Atenção, quando for criar o PR você se deparará com essa tela:

![PR do exercício](images/example-pr.png)

É necessário realizar uma mudança, clique no *base repository* como na imagem abaixo:

![Mudando a base do repositório](images/change-base.png)

Mude para o seu repositório, seu nome estará na frente do nome dele, exemplo `antonio/TicTacToe`. Depois desse passo a página deve ficar assim:

![Ápos mudança](images/after-change.png)

Ai só criar o pr clicando no botão `Create Pull Request`.

Para cada PR realize esse processo.

### COMEÇANDO OS EXERCÍCIOS

#### Exercício 1

Descrição do exercício, realize os teste:
- Necessário um botão para adicionar a tarefa..
- Botão precisa conter o texto "Adicionar" .
- Ao ser clicado a tarefa digitada pelo o usuário precisa ser salva.

Pode adicionar mais testes que acha relevantes para verificar a funcionalidade desse botão.

---

#### Exercício 2

Descrição do exercício, teste a aplicação, atenção ao o que o test orienta:

- Use o array já disponibilizado no código para realizar os testes, cada elemento do array será uma tarefa, simule a adição todas e depois verifique se eles estão aparecendo.
- Teste apenas o componente Item, ao passar uma string ela precisa aparecer na tela.
---

#### Exercício 3 

Diferente dos outros, testes já estão pronto, necessário criar a funcionalidade.

- Adicionar funcionalidade de selecionar uma task.
- Botão para apagar a task selecionada.
- Observe bem como os teste estão escritos, todos devem passar quando terminar a funcionalidade.
