![]('https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1200px-Git-logo.svg.png
')

# Passo a Passo 
## Como usar o Git HUB


1. Criar uma pasta para o projeto
2. Iniciar na pasta o git
3. Abre a pasta em um terminal
4. `git init`
5. Configuando o git na pasta
6. `git config user.name '<seu_nome>'`
7. `git config user.email '<seu_email>'`
8. Acesse o site https://github.com
9. Crie um repositorio com o mesmo nome da pasta
10. Crie um link entre o repositório do github e sua pasta no pc `git remote add origin https://github.com/<seu_usuario_github>/<seu_repositorio>.git`
11. Copiar ou criar os arquivos na pasta
12. Adiciobar os arquivo no observador do git `git add .`
13. Verificar se foram adicionados `git status`
14. Confirmar as mudanças `git commit -m ' Mensagem de confirmação'`
15. Enviar as mundaçs para o servidor github `git push -u origin master`