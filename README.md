# Fundamentos do Desenvolvimento Java
Repositório para manter os projetos da disciplina de Fundamentos do Desenvolvimento Java.

## Começando
Para executar o projetos, será necessário instalar os seguintes programas:

JDK 11 | Eclipse IDE for Java EE Developers

## Desenvolvimento
Para iniciar o desenvolvimento, é necessário clonar o projeto do GitHub num diretório de sua preferência:
git clone https://github.com/andressaguerra/tp1fundamentosjava.git

## TP1
Ao ser iniciado, o programa deve exibir um menu com as seguintes opções:
[1] Registrar as notas de um novo aluno.
[2] Consultar boletim de um aluno.
[3] Consultar notas da turma.
[4] Sair.

A estrutura de dados do programa consiste em três vetores com 100 posições cada.

Quando o primeiro aluno for registrado, a partir da opção 1 do menu, o programa deve solicitar ao usuário o nome, a nota da AV1 e a nota da AV2.
Após a gravação, o programa deve informar ao usuário que o registro foi feito com o código 0.
Se todas as posições forem ocupadas, o programa deve informar ao usuário uma mensagem informando sobre a impossibilidade de inserir novo registro.

Caso a opção 2 seja escolhida, então o programa deve solicitar ao usuário o código informado no registro do aluno para que ele possa ser consultado.
O programa deve exibir na tela o nome e as notas do aluno, além da média final e da situação do aluno (se a média for inferior a 4, imprimir "Reprovado"; igual ou superior a 4 e menor que 7, imprimir "Prova final"; igual ou superior a 7, imprimir "Aprovado").

Se a opção 3 for escolhida no menu do programa, então o programa deverá imprimir na tela todos os alunos.