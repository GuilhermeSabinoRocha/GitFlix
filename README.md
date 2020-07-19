# GitFlix

Bem vindo(a), e aproveite!

Esse projeto nasceu da necessidade, por parte dos alunos da Residência de Software do Serratec – 2020, de se treinar o uso prático do Git e sua dinâmica.

A forma escolhida foi contar uma história colaborativa, onde cada participante escreve a partir do ponto em que a história se encontra (exceção abaixo). Com isso deixamos o “escrever código” de lado um pouco pra focarmos no fluxo de trabalho do Git. Isso tudo no mínimo vai render uma boa risada, e de quebra vamos ficar mais preparados pro mercado de trabalho.

Leia o arquivo “Brooklyn99.doc”, que é o start da história, e que introduz os personagens e possibilidades. O ambiente inicial é a série “Brooklyn Nine-Nine” do Netflix. Imagine que os personagens estão vivos, vivendo tudo o que acontece nos episódios, e de repente, talvez por um bug no site, vão parar fora do episódio, dentro da tela do computador, olhando pra pagina inicial do Netflix.

A idéia é que cada um de vocês continue a história do colega, de onde ela parou (ou escrevam um trecho juntos), continuando no ambiente inicial, ou ampliar o leque, fazendo os personagens viverem outras séries (inclusive as descontinuadas) ou filmes (qualquer um). Pode inventar personagens novos na trama… pode manipular a passagem do tempo, pode não usar os personagens iniciais e começar uma outra idéia… e pode, também, inventar a continuação (que você esperava e não foi produzida) daquela sua série preferida.

Solte a imaginação à vontade, aqui ninguém vai julgar ninguém. Se estiver sem tempo/idéias, escreva uma frase curta, às vezes só uma frase pode dar uma pista pra alguém continuar. Claro que não precisa escrever um livro, mas quanto mais participarmos, mais a história vai ganhando características e volume de um gitflow real.


# Comandos:

A forma indicada é usar os comandos em um terminal/Bash, para se ter mais controle no processo.

Sua história/trecho pode ser criada em qualquer arquivo .txt/.doc/.docx ou outro formato de texto.

- O primeiro passo é clonar o repositório (isso vai criar em sua máquina sua cópia de desenvolvimento, de todo o repositório):

git clone https://github.com/GuilhermeSabinoRocha/GitFlix.git

- Depois, e sempre antes de escrever algo na história (o comando abaixo atualiza seu repo local):

git pull

- Crie seu branch:

git branch <nome_do_branch> (isso cria o branch onde vai desenvolver seu ambiente escolhido, com o <nome_do_branch> que você escolher – não digite os sinais <>)

git checkout <nome_do_branch> (deixa o branch como ativo, saindo do master)

git status (a qualquer momento, cheque em qual branch você se encontra. Isso é importante pois o arquivo txt/doc em que você vai escrever deve estar na branch correta)

- Abra um arquivo txt/doc, escreva seu trecho, e salve-o (dando ao nome do arquivo o nome do ambiente/série/filme) na pasta Gitflix da sua máquina, a que foi criada pelo git clone.

- Esse seu arquivo ainda não está sendo trackeado pelo git. Digite o comando:

git add . (não esqueça do ponto)

Nesse ponto, leia este artigo, curtinho e muito importante:
https://www.atlassian.com/br/git/tutorials/saving-changes


- Faça o commit, deixando entre aspas seu comentário do que foi feito, observações, ou algo que identifique o commit:

git commit -m "<sua_mensagem>"

- Faça o push

git push origin <nome_do_branch>

- Faça o pull request:

https://docs.github.com/pt/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request


# Ética:

Educação e respeito sempre!

Não faça o git push direto pra master, faça para seu branch.

Fique à vontade pra editar um trecho da história escrito por alguém, desde que você comunique e combine previamente com o(a) autor(a)!


# Conclusão

Finalizando, espero que essa experiência seja interessante, e que te ajude, lá na frente, a trabalhar de forma natural com o Git em sua carreira e nos seus futuros projetos.

Agradeço ao Serratec ppr abrir um canal com a turma de Teresópolis, e ao Raul, Rafael e Gabriela, po toda ajuda e insights. Sem vcs isso não se realizaria! Agradeço de coração
