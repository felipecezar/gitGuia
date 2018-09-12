# Passo a Passo 
# Como usar o Git HUB

1.Criar uma pasta para o projeto
2.Iniciar na pasta o git
2.1. Abre a pasta em um terminal
2.2. `git init`
3.Configuando o git na pasta
3.1. `git config user.name '<seu_nome>'`
3.2. `git config user.email '<seu_email>'`
4. Acesse o site https://github.com
4.1. Crie um repositorio com o mesmo nome da pasta
5. Crie um link entre o repositório do github e sua pasta no pc `git remote add origin https://github.com/<seu_usuario_github>/<seu_repositorio>.git`
6. Copiar ou criar os arquivos na pasta
7. Adiciobar os arquivo no observador do git `git add .`
7.1. Verificar se foram adicionados `git status`
8. Confirmar as mudanças `git commit -m ' Mensagem de confirmação'`
9. Enviar as mundaçs para o servidor github `git push -u origin master`