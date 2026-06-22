# ENaPP — pacote com perguntas variadas e privacidade por usuário

Este pacote substitui o `index.html` atual do app ENaPP.

## O que foi corrigido

- Cada usuário/testador começa com o app zerado.
- Cada perfil fica separado no navegador.
- É possível mandar links individuais usando `?tester=nome-do-teste`.
- As perguntas mudam a cada acesso/início de exercício.
- As alternativas são embaralhadas, então a resposta correta não fica sempre no mesmo lugar.
- O histórico não salva alternativas escolhidas, perguntas respondidas nem respostas corretas.
- O histórico salva só: data, tema do exercício, pontuação, XP, nível estimado e foco geral de revisão.
- Se duas pessoas usarem o mesmo aparelho, há botão “Novo testador zerado”.
- Há botão para apagar somente os dados do perfil atual.

## Como aplicar pelo GitHub

1. Abra o repositório: `https://github.com/leidehart/ENaPP`.
2. Clique no arquivo `index.html`.
3. Clique no lápis de edição.
4. Apague todo o conteúdo antigo.
5. Cole o conteúdo do `index.html` deste pacote.
6. Clique em `Commit changes`.
7. Aguarde o GitHub Pages atualizar.
8. Abra: `https://leidehart.github.io/ENaPP/`.

## Links para enviar aos amigos

Use links assim:

```text
https://leidehart.github.io/ENaPP/?tester=amiga-1
https://leidehart.github.io/ENaPP/?tester=amigo-2
https://leidehart.github.io/ENaPP/?tester=teste-03
```

Cada link cria uma área separada no navegador da pessoa.

## Observação importante

Este app não tem login nem banco de dados online. Os dados ficam no navegador de quem usa.

Se cada pessoa abrir no próprio celular/computador, cada uma terá seu app zerado e separado.

Se várias pessoas usarem o mesmo aparelho, use o botão **Novo testador zerado** antes da próxima pessoa começar.
