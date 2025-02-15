# Relatório de Teste
<br/>

##  Login e Logout
<br/>

**Cenário 1 – Login com credenciais válidas**
<br/>

* Dado que o usuário está na tela de login
* Quando inserir um número de conta válido e confirmar
* Então o sistema deve permitir o acesso à conta

(![alt text](<../assets/cenario 1.png>))
(![alt text](<../assets/cenario 1 2.png>))
(![alt text](<../assets/cenario1 mariana.png>))
(![alt text](<../assets/cenario pedro.png>))



<br/>

**Cenário 2 – Login com conta inexistente**
<br/>

* Dado que o usuário está na tela de login
* Quando inserir um número de conta inválido
* Então o sistema deve exibir uma mensagem de erro

(![alt text](<../assets/cenario 1.png>))
(![alt text](<../assets/cenario 1 2.png>))
(![alt text](<../assets/cenario1 mariana.png>))
(![alt text](<../assets/cenario pedro.png>))


<br/>

**Cenário 3 – Logout da conta**
<br/>

* Dado que o usuário está logado
* Quando clicar em "Sair da conta"
* Então o sistema deve encerrar a sessão e redirecionar para a tela de login


(![alt text](<../assets/cenario 1 2.png>))
(![alt text](<../assets/cenario 1.png>))
(![alt text](<../assets/cenario1 mariana.png>))
(![alt text](<../assets/cenario 1.png>))
(![alt text](<../assets/cenario pedro.png>))
(![alt text](<../assets/cenario 1.png>))

<br/>


## Consulta de Saldo
<br/>

**Cenário 4 – Exibição correta do saldo**
<br/>

* Dado que o usuário está logado
* Quando acessar a tela inicial
* Então o saldo deve ser exibido corretamente

(![alt text](<../assets/cenario 1 2.png>))
(![alt text](<../assets/cenario1 mariana.png>))
(![alt text](<../assets/cenario pedro.png>))

<br/>


## Depósito
<br/>

**Cenário 5 – Depósito de valor positivo**
<br/>

* Dado que o usuário deseja fazer um depósito
* Quando inserir um valor válido e confirmar
* Então o sistema deve adicionar o valor ao saldo e exibir uma mensagem de sucesso

(![alt text](<../assets/joao silva deposito 1.png>))
(![alt text](<../assets/joao deposito 2.png>))
(![alt text](<../assets/mariana deposito.png>))
(![alt text](<../assets/mariana deposito 2.png>))
(![alt text](<../assets/pedro deposito.png>))
(![alt text](<../assets/pedro deposito 2.png>))

<br/>

**Cenário 6 – Depósito de valor negativo ou zero**
<br/>

* Dado que o usuário deseja fazer um depósito
* Quando inserir um valor negativo ou zero
* Então o sistema deve exibir uma mensagem de erro e não alterar o saldo

(![alt text](<../assets/joao deposito negativo.png>))
(![alt text](<../assets/joao deposito negativo 2.png>))
(![alt text](<../assets/mariana deposito negativo.png>))
(![alt text](<../assets/mariana deposito negativo 2.png>))
(![alt text](<../assets/pedro deposito negativo.png>))
(![alt text](<../assets/pedro deposito negativo 2.png>))


<br/>


## Saque
<br/>

**Cenário 7 – Saque com saldo suficiente**
<br/>

* Dado que o usuário tem saldo suficiente
* Quando inserir um valor válido e confirmar
* Então o sistema deve descontar o valor do saldo e exibir uma mensagem de sucesso

(![alt text](<../assets/joao saque.png>))
(![alt text](<../assets/joao saque 2.png>))
(![alt text](<../assets/mariana saque.png>))
(![alt text](<../assets/mariana saque 2.png>))
(![alt text](<../assets/pedro saque.png>))
(![alt text](<../assets/pedro saque 2.png>))

<br/>

**Cenário 8 – Saque com saldo insuficiente**
<br/>

* Dado que o usuário deseja sacar um valor maior que o saldo disponível
* Quando tentar confirmar o saque
* Então o sistema deve exibir uma mensagem de erro e impedir a transação

(![alt text](<../assets/joao saque negativo.png>))
(![alt text](<../assets/joao saque negativo 2.png>))
(![alt text](<../assets/mariana saque negativo.png>))
(![alt text](<../assets/mariana saque negativo 2.png>))
(![alt text](<../assets/pedro saque negativo.png>))
(![alt text](<../assets/pedro saque negativo 2.png>))

<br/>


## Transferência
<br/>

**Cenário 9 – Transferência bem-sucedida**
<br/>

* Dado que o usuário deseja transferir um valor para outro destinatário
* Quando inserir um valor válido e um destinatário correto
* Então o sistema deve descontar o saldo do remetente e creditar o destinatário

(![alt text](<../assets/joao transferencia.png>))
(![alt text](<../assets/joao transferencia 2.png>))
(![alt text](<../assets/mariana transferencia.png>))
(![alt text](<../assets/mariana transferencia 2.png>))
(![alt text](<../assets/pedro transferencia.png>))
(![alt text](<../assets/pedro transferencia 2.png>))

<br/>

**Cenário 10 – Transferência para conta inexistente**
<br/>

* Dado que o usuário deseja transferir um valor
* Quando inserir um número de conta inválido
* Então o sistema deve exibir uma mensagem de erro e não realizar a transferência

<br/>


## Histórico de Transações
<br/>

**Cenário 11 – Exibição correta do histórico**
<br/>

* Dado que o usuário realizou transações
* Quando acessar a aba de histórico
* Então todas as transações devem ser exibidas corretamente com data, valor e tipo



[def]: ssets