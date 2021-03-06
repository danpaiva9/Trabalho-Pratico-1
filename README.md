# Trabalho Prático 1

Técnicas de Programação – 2019.1 – Prof. Wendley Silva

Trabalho Prático Individual: 01
Universidade Federal do Ceará – UFC Sobral

Nome: Daniel Araujo Paiva - Matrícula: 432312


Para iniciar a execução do programa, basta executar o  "Principal.java".

Apresentando o projeto: Inicia-se com uma janela dando as Boas Vindas ao 
usuário. Em seguida, o usuário terá que cadastrar 3 contas (Comum, Poupança 
e Especial). 

~> Conta Comum: O usuário deverá inserir seu nome, o número da sua conta 
(apenas números, caso contrário dará ERRO), valor de saldo inicial (usar um 
ponto (.) para separar reais de centavos). Após inserir todas as informações, 
salvá-las. 

~> Conta Poupança: Será necessário adicionar um nome, um número de conta, 
um valor de saldo inicial e um valor percentual para a taxa de reajuste (valor 
inteiro e sem símbolos). Obs: Caso o usuário não preencha o campo "Taxa de 
Reajuste", será adotado o valor de 10%. Para finalizar esta etapa, salva-se as 
informações. 

~> Conta Especial: Adiciona-se nome, número da conta, saldo inicial, um valor 
de limite para o saque e um valor percentual (inteiro e sem símbolos) para a 
multa desejada. Para finalizar essa primeira etapa, salvam-se as informações.
A segunda etapa é a das Operações (Sacar, Depositar Transferência, Reajuste
e Ver Saldo).


~> Sacar: O usuário deverá inserir o número da conta e o valor e deve-se clicar 
em "Continuar", caso clicado em "Cancelar" o usuário retornará para as 
operações. Em seguida, surgirá uma nova janela com o nome associado ao 
número da conta digitado, o usuário deverá clicar em "sim", para confirmar a 
operação e em "não", caso deseje voltar para a janela de operações. Tendo o 
valor do saldo maior ou igual ao valor de saque desejado, será emitida a seguinte 
mensagem: "Saque efetuado com sucesso". Caso o valor do saldo seja menor 
que o valor desejado de saque, a mensagem emitida será a seguinte: "Saldo 
insuficiente". Nas situações em que for utilizada a Conta Especial, o sistema irá 
avaliar se o valor de saque desejado, é menor ou igual que a soma do saldo com 
o limite (emitindo a seguinte mensagem: Saque efetuado usando Cheque 
Especial"). Mas nas situações em que o valor do saque é maior que essa soma, 
a mensagem é: "Saldo Insuficiente". Obs.: Nas situações em que forem utilizado 
o Cheque Especial, o saldo será atualizado através da soma entre o valor de 
limite utilizado na transação e o percentual da multa, resultando em um valor de 
débito.

~> Depósito: O usuário deverá informar o número da conta e o valor desejado. 
Após informado, o usuário pode clicar em "cancelar" para voltar às operações ou 
"continuar", para prosseguir. Clicando em "continuar" surgirá uma janela de 
confirmação, onde o usuário irá clicar em "sim" pra confirmar o depósito e caso 
queira voltar para as operações, clica-se em "não".  Se o valor de depósito for 
incoerente, surgirá a seguinte mensagem: "Depósito não realizado", se o valor 
de depósito for possível, aparecerá a mensagem: "Depósito realizado com 
sucesso". 

~> Transferência: Deve-se informar os números das contas (origem e destino) 
e o valor. Caso clique em cancelar, o sistema retornará para as operações. 
Clicando em continuar aparecerá uma mensagem de confirmação com as 
opções de "não" (ocasionando no retorno às operações) e "sim" (o sistema irá 
verificar se a Conta de origem tem saldo suficiente, se sim, surgirá a mensagem: 
"Transferência realizada com sucesso", se não, aparecerá a mensagem: 
"Transferência não realizada".)

~> Reajuste: Deve se colocar o número da conta poupança e o valor da nova 
taxa (Caso o campo da Taxa não seja preenchido, será mantido o valor do 
cadastro inicial).

Obs.: Caso o usuário não digite um valor pra taxa no campo "Reajuste" e não 
tenha digitado um valor pra taxa no cadastro inicial, o valor adotado será de 
10%).

Caso o usuário registre um valor para a taxa, aparecerá uma mensagem de 
confirmação com a opção "não", onde não altera o valor da taxa e aparece a 
mensagem de confirmação do reajuste. A opção "sim" confirma a alteração de 
valor da taxa, após confirmado, aparecerá uma nova janela de confirmação do 
reajuste, com as opções "não", que retorna para as operações, e "sim", 
aparecerá a mensagem de "Reajuste efetuado com sucesso".

~> Ver Saldo: Ao clicar nessa opção, surgirá uma nova janela informando os 
nomes dos titulares de cada conta e os respectivos saldos. 

Obs.: A opção "Sair" encerra o programa.
