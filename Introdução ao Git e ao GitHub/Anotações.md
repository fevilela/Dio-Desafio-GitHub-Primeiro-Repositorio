# Entendendo o que é Git e sua importância
## Git e Github

- controle de versão
- armazenamento em nuvem
- trabalho em equipe
- melhorar seu código
- reconhecimento

## Comandos básicos para um bom desempenho no terminal

* o Git não tem uma interface gráfica, ele interage por linha de comando
* comandos (prompt)
  * **mudar de pasta**
    * cd / , depois disso digite a pasta
    * cd .. para sair da pasta 
  * **listar as pastas**
    * dir (windows)
    * Is (linux ou mac)
  * **criar pastas/arquivos**
    * pasta: mkdir em seguida crie o nome da pasta
    * arquivo: entre na pasta que você criou (cd nome da pasta), em seguida digite echo o que você quer dentro do arquivo > nome do arquivo que você deseja (não esqueça do tipo, como, .txt…)
  * **deletar pastas/arquivos**
    * del, em seguida digite a pasta, desse jeito vai deletar somente os arquivos dentro da pasta
    * rmdir, para deletar toda a pasta e arquivos que tem dentro (rmdir nome da pasta /S /Q)
  * **limpar a tela do terminal**
    * cls (windows)
    * clear (linux ou mac)

## Realizando a instalação do Git

* entre no site oficial da [Git](git.scm.com) 
* siga passo a passo para a instalação

## Tópicos fundamentais para entender o GIT

* SHA
  * significa Algoritmo de Hash Seguro
  * pega seu arquivo e embaralha de uma forma muito específica
  * é um conjunto de funções hash criptográficas projetada pela NSA (Agência de Segurança Nacional dos Estados Unidos
  * a encriptação gera conjunto de caracteres identificador de 40 dígitos é uma forma curta de representar um arquivo
  * se você alterar uma vírgula, eles geram um novo conjunto de caracteres

## Chaves SSH e Tokens

* chave SSH
  * é uma fórmula segura e encriptada entre duas máquinas
  * comandos para gerar essa chave:
    * abra o GIT Bash
    * digite:
      * ssh-keygen -t ed25519 -c “email que você usa no github"

## Iniciando o Git e criando um commit

* primeiros comandos:
  * iniciar o git
    * git init
    * navegue até a pasta que deseja inicializar o git
    * depois digite git init
  * criando arquivo
    * git add
  * criando um commit
    * git commit
