#como baixar repositório pela primeira vez
git clone <url-do-repositório>

#sobre .gitignore
#evita versionar arquivos de determinada extensão

#README.md
#Página principal com informações sobre o repositório.

#como saber quais arquivos foram ou não versionado...
#e como saber quais arquivos mudara...
git status

#se quisermos versionar um arquivo que não era versionado...
#ou quisermos incluir uma mudança em um arquivo que já era versionado...
git add <nome-do-arquivo-ou-pasta>

#quando quisermos salvar o estado do projeto, usamos o commit
git commit -m "Mensagem que indica o que foi mudado"

#para enviar as mudanças para a nuvem (github) usamos o git push
git push
git push origin master

#para baixar as informaçes (arquivos e pastas) do servidor remoto 
#para o contexto local (seu notebook)
git pull               # executar este comando
git pull origin master # ou executar este comando

#issues são problemas que precisam de revisão por parte de algum desenvolvedor ou mantenedor do projeto

Dicas de configuração do git no terminal:
 - git config --global user.name "Seu Nome"
 - git config --global user.email "seuemail@gmail.com"
