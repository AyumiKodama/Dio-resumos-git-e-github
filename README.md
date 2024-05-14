
# Dio | Resumos Git e Github    

    Repósitorio para armazenar resumos do curso de versionamento de codigo com git e github.

## 📚 Documentação
- [Documentação git](https://git-scm.com/docs/git/pt_BR)
- [Documentação github](https://docs.github.com/)

## ⌨ Comandos

- ```Git add .``` (adiciona todos os arquivos que estão disponíveis para mandar para a área de standing)

- ```Git checkout <nome branch>``` (para alternar a branch)

- ```Mkdir <nome diretório>``` (cria um diretorio)

- ```Cd <nome pasta>``` (entra na pasta)
- ```Cd .. Ou cd ../.. ```(Para voltar uma pasta)

## 🗑 Desfazendo alterações no Repósitorio local
| Comando | Descrição |
|---------|-----------|
| ```git restore <nome arquivo>```| restaura todas as modificações.|
| ```git commit -ammend -m "nova mensagem"``` |para alterar nome do ultimo commit.|
| ```git reset --soft <hash do commit>``` | volta para o commit, com os arquivos na area de preparação.|
|```git reset --mixed <hash do commit>```| volta para o commit, porém os arquivos não estão rastreados.|
|```git reset --hard <hash do commit>```| volta para o commit, sem senhum arquivo.|
|```git reset <nome arquivo>```| coloca o arquivo como não rastreado.

## 🔗 Trabalhando com branchs
|Comando | Descrição |
|--------|-----------|
|git checkout -b <nome branch nova>| cria uma nova branch e entra nela.|
|git branch -v| lista o ultimo commit de cada branch.|
|git merge <nome branch>| mescla o <nome branch> com a branch atual.|
|git branch -d <nome>| deleta a brach.|
|git fetch origin main| baixa as alterações, porem não mescla na branch.|
|git clone url --branch <nome branch> --single branch| clona somente a branch desejada.


