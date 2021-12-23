# Download do Git

[Git - Downloads (git-scm.com)](https://git-scm.com/downloads)

# Instalação do Git

[Git - Instalando o Git (git-scm.com)](https://git-scm.com/book/pt-br/v2/Começando-Instalando-o-Git)

# Configurações iniciais

Após instalar o Git em seu sistema operacional, essas configurações são necessárias para seu funcionamento.

### Configurar nome e identidade

Substituir nome de usuário e email pelos suas informações.

- git config --global user.name "nomedeusuário"
- git config --global user.email fulanodetal@exemplo.com

### Escolher editor padrão

- git config --global core.editor vim

### Testando suas configurações

Listar suas configurações e observar se user.name e user.email foram adicionados corretamente.
- git config --list

# Iniciar terminal
#### Utilizando o Windows 10
- Iniciar o terminal do git bash na pasta em que deseja iniciar o repositório.
Clicar com o botão direito >> Git Bash Here

# Comandos iniciais 

Para simular alguns comandos criei uma pasta "teste" no diretório raiz contendo um arquivo de texto "README.txt".

###### Iniciar linha do tempo

- git init 

    ###### Saída esperada:

    Initialized empty Git repository in C:/teste/.git/

###### Estado do projeto

- git status // informa estado das alterações do projeto

    ###### Saída esperada:
    On branch master

    No commits yet

    Untracked files:
    (use "git add <file>..." to include in what will be committed)
            README.txt

    nothing added to commit but untracked files present (use "git add" to track)

###### Adicionar ou atualizar mudanças na linha do tempo

- git add // exemplo adicionando o arquivo README.txt >> git add README.txt
Comando alternativo:
- git add . // adiciona todos os arquivos do diretório

###### Adicionar o ponto na linha do tempo

- git commit // exemplo adicionando um comentário ao ponto >> git commit -m 'primeiro commit README'

###### Cria uma branch principal

- git branch // exemplo adicionando a branch com o nome de main >> git branch -M main


# Comandos adicionais

- git log // mostra os pontos na linha do tempo que realizou commit
- git show // mostra último ponto da história >> git show "sha1" // mostra ponto específico
- git branch // mostra e gerencia as linhas do tempo
- git checkout // permite "se deslocar" entre as linhas do tempo
- git merge // unir linhas do tempo
- git push // envia alterações locais para o repositório remoto (envia para nuvem do GitHub)
- git clone // clonar um repositório para acesso local (clona da nuvem do GitHub)
- git pull // puxa e compara repositório remoto (puxa e compara com o repositório da nuvem do GitHub)

