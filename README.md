# LevelUp English — App pessoal A2 → B1/B2

Protótipo de app web para estudar inglês pelo celular, com foco em sair do nível **A2** e evoluir para **B1/B2 inicial**.

## O que tem no app

- Trilha de níveis: A2.0, A2.1, A2.2, A2+, B1.1, B1.2, B1+, B2.0
- Pontuação por XP
- Quizzes com explicações
- Treino de tempo verbal
- Vocabulário natural
- Estrutura de frases
- Listening com voz do navegador
- Speaking usando microfone
- Conversa guiada com a treinadora Maya
- Avaliações quinzenais
- Revisão dos pontos fracos

## Como usar localmente

1. Baixe este repositório ou o arquivo ZIP.
2. Abra o arquivo `index.html` no navegador.
3. No celular, prefira abrir pelo Chrome para usar melhor microfone e voz.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie os arquivos deste projeto para o repositório.
3. Vá em **Settings → Pages**.
4. Em **Build and deployment**, escolha:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Clique em **Save**.
6. O GitHub vai gerar um link público para abrir o app.

## Observações importantes

Este projeto roda somente no navegador. Não tem servidor, login ou banco de dados.

O progresso fica salvo no próprio navegador usando `localStorage`. Se você limpar os dados do navegador ou trocar de aparelho, o progresso pode ser perdido.

A avaliação de fala é aproximada porque usa o reconhecimento de voz disponível no navegador. Para avaliação profissional de pronúncia, seria necessário integrar uma API especializada ou usar apoio de professor.
