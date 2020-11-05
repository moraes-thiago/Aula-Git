# Iniciar Git
`git init`   -  Inicia o git no terminal

# Adicionar Arquivos no Repositório
`git add`    -  Adiciona o arquivo
`git commit` -  Põem o marco dele, um nome (Ex.: git commit -m "adicionado home page")

# Mostrar Atualizações
`git log`    -  Mostra todas as atualizações e seu número do commit

# Ver status dos Arquivos
`git status` -  Mostra quais arquivos não foram enviados para o repositório e também os arquivos que não foram
                atualizados no git

# Mostrar as mudanças das atualizações
git show     -  Mostra o que foi editado na atualização. Tem que pegar o número do commit, usando o "git log".

# Criar e Tirar novas funcionalidades (Sem estregar o que foi feito)
git branch   -  Cria a nova funcionalidade (Ex.: "feature/cart")
git merge D  -  Deleta a nova funcionalidade

git checkout -  Muda para a nova "linha" (Ex.: git checkout "feature/cart")

# Colocar a nova funcionalidade no projeto em produção
git merge    -  Coloca as novas funcionalidades no projeto (Ex.: git merge feature/cart)
