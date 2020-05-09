# GIT E GITHUB 

Guia prático para iniciantes.

### Instalação 

https://git-scm.com/download

# SCENES

- [x] Você deseja criar pontos na História da produção do seu projeto ?
# git add + 'nome do arquivo'
# git commit -m "mensagem aqui"

- [x] Você deseja verificar mudanças feitas no seu projeto ?
# git status / git log

- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito. 
# git branch + (nome da nova branch)
# quer mudar para nova branch? git checkout + 'nome da branch' e git status
# faça as alterações no arquivo, adicione a linha do tempo e faça o commit, as alterações não vão aparecer na branch master

- [x] Você adiciona as novas funcionalidades ao seu projeto, sem estragar o que já foi feito.
# git merge + (nome da branch)

- [x] Você deleta a branch da nova funcionalidade, depois aplica em seu projeto.
# git branch -D feature/cart

- [x] Você quer adicionar seu projeto na nuvem.
# git remote add origin wenderson-me/Git-Guia-Iniciante.git
# git push -u origin master


 
- `git init` // inicia a linha do tempo
- `git add` // adiciona ou atualiza mudanças do para irem para linha do tempo
- `git commit`// adiciona um ponto na linha do tempo
- `git log` // visualiza os ponto na linha do tempo / commit
- `git status` // informa o estado das alterações do nosso projeto
- `git show` // apresenta determinado ponto na historia