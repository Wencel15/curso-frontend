# Curso-front-end

#### EBAC

# GIT
## Conceitos de versionamento
 - Histórico
 - Controle de versão
 - Quem alterou
 - O quê alterou
 - Quando alterou
 - Todos os arquivos
 - Evolução contínua
 
 Arquivo A  |  Versão 1  |  Versão 2
 Arquivo B  |  Versão 1  |  Versão 2
 
 ## Instalação do GIT
 https://git-scm.com/
 
 - Windows: https://git-scm.com/download/win
 - Linux: (apt-get): sudo apt-get install git
 - Mac: (brew): brew install git

## Criar conta no Github

## Clonar o projeto
git clone git@github.com:Wencel15/curso-frontend.git

## Comits
Informação de alteração
- Após testado todo o seu código
- git add *
- git commit -m "mensagem
- git push (para enviar alteraçõespara o repositório)
- git pull (puxar / trazer alterações do GitHub para sua máquina)


## GitFlow
Fluxo do Git

### Branchs
São ramificações / versões paralelas

 - main / master ( vai para produção, quando o projeto é publicado)
 - develop
 - DOD Definition of Done: critérios de aceite
 - versionamento 0.1.10

 git checkout -b dev (cria uma branch)
 git checkout master (mudar de branch)
 ### Merge
 Mescla de branch
 Você pode precisar resolver conflitos manualmente

 git merge main

 ### Pull Request
 Mescla de branchs no repositório
 Permite code review
 O  repositório resolve os conflitos automaticamente


### Configura o GitFlow
git flow init
git flow feature star {nome-da-feature}