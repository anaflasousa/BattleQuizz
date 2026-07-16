Oi!! Este repositótio foi feito para o controle de versão do site do nosso TCC.
-------------------------------------------------------------------------------
->PRÉ REQUISITOS<-

  -Ter o Git e VSCODE instalados no computador.

------------------------------------------------------------------------------
**->Tutorial de como clonar o repositório na sua maquina local:**

1)Copie o link do repositório:

-Entre na página do projeto no GitHub.

-Clique no botão verde escrito "Code" (perto do topo direito).

-Copie o link que aparece lá (https://github.com/anaflasousa/BattleQuizz.git).

2)Abra o Terminal na sua máquina:

-No terminal, digite:

--git clone https://github.com/anaflasousa/BattleQuizz.git

--cd BattleQuizz

--code .

----------------------------------------------------------------------------------------------------------
**->Comandos Git para mexer com segurança:**

-Puxar as alterações mais recentes:
git pull origin main

-Criar e entrar em uma *nova* branch:
git checkout -b nome-da-sua-branch

-Ver em qual branch você está atualmente:
git branch

-Mudar para uma branch que já existe:
git checkout nome-da-branch

**Para eviar as alterações:**

-Preparar os arquivos modificados:

git add .
(O ponto significa que você está preparando todos os arquivos que mexeu. (Se quiser preparar apenas um, use git add arquivo.html)

-Criar o ponto de salvamento (Commit):

git commit -m "mensagem
-m = Explique brevemente o que você fez para os outros integrantes saberem.

-Enviar a sua branch para o GitHub:

git push origin nome-da-sua-branch

