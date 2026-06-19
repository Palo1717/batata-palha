Documento de Acompanhamento – Atividade Prática de Versionamento de Código com Git e GitHub

Dupla: Paloma e Sabrina

Turma: 3°A Desenvolvimento de sistemas

Disciplina: Versionamento de Código

Objetivo

O objetivo desta atividade foi aprender a usar o Git e o GitHub para realizar o versionamento de código em equipe, utilizando branches, commits, push, pull e merge durante o desenvolvimento de um projeto simples.

Etapa 1 – Criação do Projeto

Primeiro foi criada uma pasta de atividade-versionamento e ela foi aberta no Visual Studio Code. Em seguida, foi inicializado um repositório Git utilizando o comando "git init". Depois foram criados os arquivos "index.html" e "login.html", acrescentados ao Git e realizados o primeiro commit.

Comandos utilizados

git init git add . git commit -m "Projeto inicial"

Etapa 2 – Criação do Repositório no GitHub

Foi criado um novo repositório no GitHub sem arquivo README. Depois que o repositório local foi conectado ao repositório remoto utilizando a URL fornecida pelo GitHub. Por fim, os arquivos foram enviados para o GitHub.

Comandos utilizados

git remote add origin (https://github.com/Palo1717/batata-palha.git) git branch -M Main git push -u origin Main

Etapa 3 – Clonagem do Projeto

O segundo membro clonou o repositório utilizando o comando "git clone" e abriu o projeto no Visual Studio Code para iniciar o desenvolvimento.

Comando utilizado

git clone https://github.com/Palo1717/batata-palha.git

Etapa 4 – Criação das Filiais

Cada membro criou sua própria filial para trabalhar separadamente. Um membro criou o ramo "Sabrina" e o outro criou o ramo "Paloma".

Comandos utilizados

git checkout -b Paloma git checkout -b Sabrina git branch

Etapa 5 – Desenvolvimento

Cada membro desenvolveu sua parte do projeto.

O Integrante 1 criou a página Home. (Paloma)
O Integrante 2 criou uma página Login. (Sabrina)
Após finalizar as alterações, cada um realizou um commit e inveja seu branch para o GitHub.

Comandos utilizados

adicione. git commit -m "Criação da página Home" git push origin Paloma

adicione. git commit -m "Criação da página Login" git push origin Sabrina

Etapa 6 – Mesclar as Filiais

Após finalizar o desenvolvimento, foram criados Pull Requests no GitHub para unir as ramificações "Paloma" e "Sabrina" à ramificação "Principal". Depois das fusões foram realizadas.

Etapa 7 – Atualização do Projeto

Depois do merge, o projeto foi atualizado utilizando o comando abaixo para baixar as alterações da branch principal.

Comandos utilizados

git checkout Main git pull origin Main

Todos os comandos utilizados

git init git add . git commit -m "Projeto inicial"

git remote add origin https://github.com/Palo1717/batata-palha.git git branch -M Main git push -u origin Main

git clone https://github.com/Palo1717/batata-palha.git

git checkout -b Sabrina heckout -b Ploma

ramificação git

adicione. git commit -m "Criação da página Home" git push origin Paloma

adicione. git commit -m "Criação da página Login" git push origin Sabrina

git checkout Main git pull origin Main

Dificuldades

Durante a atividade houve algumas dificuldades para usar os comandos do Git corretamente e entender como funcionam as filiais. Também houve atenção na hora de enviar as alterações para o GitHub e realizar o merge sem erros.

Soluções adotadas

Verificamos os comandos antes de repeti-los, verificamos se estávamos na branch correta e utilizamos o GitHub para realizar os Pull Requests e os merges. Após isso, atualizamos o projeto com "git pull" para que todos precisem da versão mais recente.

Conclusão

A atividade foi importante para aprender como funciona o versionamento de código utilizando Git e GitHub. Foi possível praticar o trabalho em equipe, a criação de filiais, os commits, o envio das alterações para o GitHub e a fusão entre diferentes versões do projeto. Esses conhecimentos são muito utilizados no desenvolvimento de software e serão úteis em projetos futuros.
