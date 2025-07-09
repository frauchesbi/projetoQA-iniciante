GIT 
.O que é Git e Github: os primeiros passos nessas ferramentas;
São ferramentas distintas, mas colaboram de maneira integrada para tornar o desenvolvimento de software mais eficiente.

O Github é uma “rede social dev” em que é possível armazenar e compartilhar projetos de desenvolvimento de software.

O Git é um sistema de controle de versão de arquivos; em outras palavras, é responsável por guardar o histórico de alterações sempre que alguém modificar algum arquivo que está sendo monitorado por ele.

Desta maneira, o Git e o GitHub são pilares fundamentais que auxiliam as equipes de desenvolvimento a controlar o versionamento de código, rastrear mudanças, colaborar de forma eficiente e garantir que o trabalho em equipe flua sem problemas.

Na imagem a seguir, podemos exemplificar melhor essas diferenças:
![comparativo-git-github](https://github.com/user-attachments/assets/5f343d1c-d429-42b8-88b4-50bee502de52)

==
Quais são os principais comandos do Git?
O Git é uma ferramenta bastante robusta e oferece diversos utilitários para gerenciar as versões de um projeto em linha de comando. Confira os principais comandos da ferramenta:

Git init;
Git clone;
Git status;
Git add;
Git commit;
Git log;
Git branch;
Git checkout;
Git diff.

1) Git init
É utilizado para inicializar um repositório Git dentro de um diretório do sistema. Após sua utilização, a ferramenta passa a monitorar o estado dos arquivos no projeto.

2) Git clone
É utilizado para criar uma cópia de um repositório remoto em um diretório da máquina. Este repositório poder ser criado a partir de um repositório armazenado localmente, através do caminho absoluto ou relativo, ou pode ser remoto, através do URI na rede.

A partir de um repositório clonado, é possível acompanhar o estado de um projeto e suas modificações, além de contribuir com o projeto, a partir do envio das suas modificações ao repositório central.

3) Git status
É utilizado para verificar o status de um repositório git, bem como o estado do repositório central. O comando mostra informações sobre se o projeto local está sincronizado com o central, quais arquivos estão sendo monitorados pelo Git e em qual branch você está no projeto.

4) Git add
É utilizado para adicionar arquivos ao pacote de alterações a serem feitas. É possível adicionar um único arquivo, múltiplos arquivos de uma vez, como git add <-arquivo1-> <-arquivo2-> ..., ou até mesmo um diretório, a partir de seu caminho. Uma vez que um arquivo é adicionado ao pacote de alterações com o comando add, ele está pronto para entrar no próximo commit.

5) Git commit
git commit -m "mensagem do commit"
É utilizado para criar uma nova versão do projeto a partir de um pacote de alterações. O commit pega o pacote de modificações adicionado através do comando git add, fecha essas alterações num pacote e o identifica através de um Hashcode.

Além disso, para cada commit é necessário escrever uma mensagem para identificá-lo, com uma mensagem clara de quais alterações foram feitas neste commit.

6) Git log
git log
É utilizado para ver o histórico de alterações do projeto, onde aparecerão todos os commits feitos, com suas respectivas mensagens e códigos identificadores.

O comando é muito útil quando precisamos rastrear o andamento de um projeto e verificar em qual ponto cada funcionalidade foi implementada.

Além disso, o comando conta com várias opções para mostrar o histórico de forma resumida, gráfica e até mesmo mostrando a diferença entre os commits, que podem ser vistas na documentação oficial do comando.

7) Git branch
É utilizado para criar novos ramos de desenvolvimento, bem como visualizar quais são os ramos existentes.

Para criar um novo ramo, basta utilizar o comando git branch seguido do nome do novo ramo, e para visualizar quais os ramos existentes a utilização do comando é bem similar: basta não informar um nome para a nova branch, e serão listadas todas as já criadas.

8) Git checkout
É utilizado para navegar entre as versões do projeto, bem como entre as diferentes ramificações criadas. Para navegar entre as versões, basta usar o comando:

git checkout <- Hashcode do commit ->
E todo o estado do projeto se modificará ao estado no qual o commit foi feito.

Similarmente, para navegar entre as ramificações podemos usar o comando:

git checkout <- nome da branch ->
E a branch será alterada. O comando também permite criar uma branch e imediatamente mudar para ela, através do comando:

git checkout -b <- nome da branch ->
Que vai criar a ramificação e navegar até ela.

9) Git diff
É utilizado para visualizar modificações feitas entre commits, sejam eles entre um commit arbitrário e o estado atual do projeto, dois commits arbitrários, ou até mesmo todas alterações entre dois commits distintos.

Para visualizar as alterações entre um commit distinto e o atual, basta usar o comando:

git diff <- Hashcode do commit anterior ->
E serão listadas todas as diferenças no projeto entre os dois commits.

Para conhecer mais sobre o comando git diff e seus casos de uso, além de outros comandos e utilitários do Git, confira a documentação do Git e o curso de Git e Github da Alura.

Git config
O comando git config é usado para configurar e personalizar o ambiente Git no seu sistema. Ele permite que você defina informações como seu nome de usuário, endereço de e-mail, editor padrão e muitas outras configurações que definem como o Git interage com seus repositórios.

A estrutura básica do comando é:

git config <opções> chave valor
<opções>: Pode ser global (--global) para definir configurações para todos os repositórios no seu sistema ou local (--local) para definir configurações específicas para um repositório em particular.
chave: A chave de configuração que você deseja definir (por exemplo, user.name para o nome de usuário).
valor: O valor que você deseja atribuir à chave (por exemplo, seu nome de usuário ou endereço de e-mail).
Por exemplo, para configurar seu nome de usuário globalmente, você pode usar o comando:

git config --global user.name "Seu Nome"
Isso é útil para garantir que todos os commits que você fizer em qualquer repositório Git no seu sistema tenham o seu nome associado a eles.

Além disso, o comando git config pode ser usado para personalizar muitos outros aspectos do seu ambiente Git, tornando-o mais adaptado às suas preferências e necessidades.
