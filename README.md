Oi!! Este repositótio foi feito para o site do nosso TCC, o jogo BattleQuizz.




**Tutorial de como clonar o repositório na sua maquina local:**

-Pré-requisitos:
Ter o Git instalado no computador.
Ter uma ferramenta para abrir o código (como o VS Code).


-Copie o link do repositório:
Entre na página do projeto no GitHub.
Clique no botão verde escrito "Code" (perto do topo direito).
Copie o link que aparece lá (https://github.com/anaflasousa/BattleQuizz.git).

-Abra o Terminal na sua máquina:
Crie ou escolha uma pasta no seu computador para guardar o projeto.
Entre nessa pasta, clica com o botão direito num espaço vazio e escolhe "Abrir no Terminal".

-Clone o repositório:
No terminal, digite:
git clone https://github.com/anaflasousa/BattleQuizz.git

-Entra na pasta do projeto:
No terminal, digite:
cd nome-da-pasta-do-projeto




**Comandos Git para mexer com segurança:**

-Antes de mexer em qualquer linha de código, você DEVE puxar as alterações mais recentes!!
git pull origin main

-Criar e entrar em uma nova branch:
git checkout -b nome-da-sua-branch

-Ver em qual branch você está atualmente:
git branch

-Mudar para uma branch que já existe:
git checkout nome-da-branch

**Para eviar as alterações:

-Preparar os arquivos modificados:
git add .
(O ponto significa que você está preparando todos os arquivos que mexeu. (Se quiser preparar apenas um, use git add arquivo.html)

-Criar o ponto de salvamento (Commit):
git commit -m "mensagem"
-m = Explique brevemente o que você fez para os outros integrantes saberem.

-Enviar a sua branch para o GitHub:
git push origin nome-da-sua-branch

