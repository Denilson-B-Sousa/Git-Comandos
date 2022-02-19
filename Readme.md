<h1>Repositório sobre comandos e funcionalidades do git</h1>

<p>O git é um gerenciador de controle de versão VCS, foi criado por Linus Torvalds, criador do kernel linux. O seu surgimento deve-se ao fato de uma briga entre a comunidade desenvolvedora do kernel linux e um gerenciador de versões proprietário, após essa discussão o Linus resolveu o problema da falta de um DVCS criando o git que tornou uma ferramenta de extrema importância para diferentes profissionais de programadores a dsigners. </p>

<h2>Comandos Básicos Git</h2>

Pasta Oculta .git Contêm todos os dados referentes ao versionamento do repositório.

Git Init
- Esse comando inicializa um repositório.

Branch master or main
Tempo cronológico Principal

git branch -M "main"
Comando utilizado para renomear o nome da branch, no caso acima será renomeado para <main>

Branch = ramificações

Commit
Ponto na história, quando modificamos os arquivos do repositório.

Git Add
Manda os arquivos para área de state, como se fosse uma área de espera para logo depois fazer o commit.

Changes to be committed: Mudanças que estão esperando para receber o commit.
Untracked files: Arquivos que não foram rastreados, isto é, não estão na área de stage esperando o commit
Git add .
Siginifica que todos os arquivos serão mandados para a área de stage

Git restore <file>
Utilizado para para discartar alterações no diretório de trabalho.

Git Status
Utilizado para informar a situação atual do repositório.

git commit -m 'Primeiro Commit'
[master (root-commit) 7c2f4f7] Primeiro Commit 1 file changed, 13 insertions(+) create mode 100644 Projeto Git/Readme.md
git remote add origin <link>
git remote add origin - remote conexão entre repositório local e remoto e origin refere-se ao repositório do gitHub. 

git push -u origin main 
