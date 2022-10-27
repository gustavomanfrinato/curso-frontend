# Curso Front-end
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

 Arquivo A | Versão 1 | Versão 2
 Arquivo B | Versão 1 | Versão 2

## Instalação do Git
https://git-scm.com/

Windows: https://git-scm.com/download/win
Linux (apt-get): sudo apt-get install git
Mac (brew): brew install git

## Criar conta no GitHub

## Clonar o projeto

 ## Commits
 Informação de alteração
 - após testado todo seu código
 - git add *
 - git commit -m "mensagem"
 - git push (enviar alterações para o repositório)
 - git pull (puxar / trazer alterações do GitHub para sua máquina)

 ## GitFlow
 Fluxo do Git

### Branchs
são ramificações / versões paralelas

- main / master (vai para produção, quando o projeto é publicado)
- develop (utilizada para desenvolvimento / testes)
- DOD - Definition of Done (critérios de aceite)
- versionamento 1.0.0

git checkout -b dev (cria uma branch)
git checkout master (muda de branch)

### Merge
Mescla de branchs