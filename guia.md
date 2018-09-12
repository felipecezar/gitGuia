# Passo a Passo para enviar trabalhos pelo GitHub

## Configurando

1. Crie uma pasta para o projeto
2. Inicie na pasta o git
3. Abra a pasta em um terminal
4. Execute o comando `git init` no terminal
5. Configue seu nome e email para o git com os comandos no terminal
    - `git config user.name '<seu_nome>'`
    - `git config user.email '<seu_email>'`
6. Acesse o site https://github.com
7. Crie um repositorio com o mesmo nome da pasta no github
8. Crie um link entre o repositório do github e sua pasta, execultando no terminal o comando
    - `git remote add origin https://github.com/<seu_usuario_github>/<seu_repositorio>.git`

## Incluindo atualizações

9. Copie ou crie os arquivos dos exercícios em sua pasta
12. Adicione os arquivo para o git observar as mudanças com o comando `git add .` no terminal
13. Verificque se os arquvos foram adicionados com o comando `git status` no terminal
14. Confire as mudanças com o comando `git commit -m ' Mensagem de confirmação'` no terminal
15. Envie as mundaças para o servidor do github executando no terminal o comando `git push -u origin master`


