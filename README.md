<h1 align="center">
<img src="https://hermes.dio.me/tracks/2a3a2d2b-7de7-457c-b4df-dcd327eae9eb.png" height="150" tittle="nome imagem"/>
</h1>

# DIO | First repository for test

Repositório para armazenar resumos sobre Git e Github do curso de versionamento de Código com Git e Github da [Digital Innovation One](https://www.dio.me/).

## 📜 Documents

- [Documentação Git](https://git-scm.com/doc)
- [Documentação Github](https://docs.github.com/)

## 📲 Resumo das Aulas

| Aulas | Códigos | Descrição |
|-------|---------|-----------|
| Configurando Git | ```git config user.name <nome>``` | Escolhe nome de usuário |
| Configurando Git | ```git config user.email <email>``` | Escolhe email de usuário |
| Configurando Git | ```git config init.defaultBranch <branch>``` | Altera a branch |
| Configurando Git | ``` --global / --system / --local ```| Local onde será setado a configuração |
| Configurando Git | ``` --list ``` | lista as configurações |
| Configurando Git | ``` git config --global credential.helper store ``` | Credências de usuario, email e token |
| Criando e clonando repositórios | ``` git init ``` | Inicia Repositório Git |
| Criando e clonando repositórios | ```git clone <URL> <nome-pasta>``` | Clona Repositório Git |
| Criando e clonando repositórios | ``` mkdir ``` | Cria nova pasta |
| Salvando Alterações no Repositório Local | ``` git status ``` | Verifica status dos arquivos do repositório |
| Salvando Alterações no Repositório Local | ``` git add <Arquivo>``` | Prepara os arquivos para enviar de forma por arquivo|
| Salvando Alterações no Repositório Local | ``` git add .``` | Prepara todos os arquivos para enviar |
| Salvando Alterações no Repositório Local | ``` git commit -m "Menssagem" ``` | Envia os arquivo para repositório remoto |
| Desfazendo Alterações no Repositório Local | ``` rm -rf .git ``` | Removendo o git init da pasta |
| Desfazendo Alterações no Repositório Local | ``` git restore <Arquivo> ``` | Restaurando a versão anterior |
| Desfazendo Alterações no Repositório Local | ``` git commit --amend ``` | Alterando mensagem do git commit |
| Desfazendo Alterações no Repositório Local | ``` git reset --soft <hash do commit> ``` | Retorna a um commit anterior desfazendo o atual |
| Desfazendo Alterações no Repositório Local | ``` git reset --mixed <hash do commit> ``` | O commit escolhido torna-se untracked |
| Desfazendo Alterações no Repositório Local | ``` git reset --hard <hash do commit> ``` | O commit Escolhido será apagado |
| Desfazendo Alterações no Repositório Local | ``` git log ``` | Log dos commits feitos |
| Desfazendo Alterações no Repositório Local | ``` git reflog ``` | Log de todos os commits feitos |
| Desfazendo Alterações no Repositório Local | ``` touch <Arquivo> ``` | Cria arquivo na pasta |
| Desfazendo Alterações no Repositório Local | ``` git reset <Arquivo> ``` | Retirar arquivo do ``` git add ``` |
| Desfazendo Alterações no Repositório Local | ``` git restore --staged <Arquivo> ``` | Retirar arquivo do ``` git add ``` |
| Enviando e Baixando Alterações com o repositório Remoto | ``` git remote add origin <Arquivos> ``` | Adcionar caminho para enviar repositório |
| Enviando e Baixando Alterações com o repositório Remoto | ``` git branch -M main ``` | Alterar branch master para main |
| Enviando e Baixando Alterações com o repositório Remoto | ``` git push ``` | Enviar arquivos para diretório selecionado |
| Enviando e Baixando Alterações com o repositório Remoto | ``` git pull ``` | Baixa repositório com alterações do remoto |
| Trabalhando com Branches - Criando, Mesclando, Deletando e Tratando Conflitos | ``` git checkout -b <nome> ``` | Criar nova Branch |
| Trabalhando com Branches - Criando, Mesclando, Deletando e Tratando Conflitos | ``` git checkout <nome> ``` | Trocar entre as Branches |
| Trabalhando com Branches - Criando, Mesclando, Deletando e Tratando Conflitos | ``` echo "Informação dentro do arquivo" > <Arquivo.txt> ``` | Criar arquivo e colocar informação dentro |
| Trabalhando com Branches - Criando, Mesclando, Deletando e Tratando Conflitos | ``` git branch -v ``` | Lista das Branches e ultimos commits de cada |
| Trabalhando com Branches - Criando, Mesclando, Deletando e Tratando Conflitos | ``` git merge <Branch> ``` | Insere as alterações do ultimo commit da branch selecionada à branch atual |
| Trabalhando com Branches - Criando, Mesclando, Deletando e Tratando Conflitos | ``` git branch ``` | Lista das Branches |
| Trabalhando com Branches - Criando, Mesclando, Deletando e Tratando Conflitos | ``` git branch -d <Branch> ``` | Deleta a branch selecionada |
| Trabalhando com Branches - Comando Úteis no dia a dia | ``` git fetch ``` | Baixar informações sem mesclar com o repositório local |
| Trabalhando com Branches - Comando Úteis no dia a dia | ``` git diff <branch> origin/<branch>``` | Verifica as diferenças entre as brnaches |
| Trabalhando com Branches - Comando Úteis no dia a dia | ``` git clone <URL> --branch <Branch> --single-branch ``` | Clona repositório da branch selecionada |
| Trabalhando com Branches - Comando Úteis no dia a dia | ``` git stash ``` | Arquiva a ultima mudança e retorna a anterior |
| Trabalhando com Branches - Comando Úteis no dia a dia | ``` git stash list ``` | List as ultimas mudanças arquivadas |
| Trabalhando com Branches - Comando Úteis no dia a dia | ``` git stash pop ``` | Excluir ultima alteração arquivada |
| Trabalhando com Branches - Comando Úteis no dia a dia | ``` git stash apply ``` | Manter a alteração na lista |
| Extra | ``` git commit --amend -m <Commit> ``` | Alterar mensagem do commit |

## 🔍 Referências

- [Digital Innovation One](https://www.dio.me/)
- [Documentação Git](https://git-scm.com/doc) 
- [Documentação Github](https://docs.github.com/)

<h5 align="center">
<img src="https://hermes.digitalinnovation.one/assets/diome/logo-full.svg" height="20" tittle="nome imagem"/> 

<hr>

![Static Badge](https://img.shields.io/badge/Git-f6522f?style=for-the-badge&logo=git&logoColor=000000) ![Static Badge](https://img.shields.io/badge/Github-c3c3c3?style=for-the-badge&logo=github&logoColor=000000) 
</h5>
