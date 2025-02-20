# Casos de Teste
<br/>

##  Login e Logout
<br/>
CT 01
**Cenário – Login com credenciais válidas**
<br/>

* Dado que o usuário está na tela de login
* Quando inserir um número de conta válido e confirmar
* Então o sistema deve permitir o acesso à conta.

<br/>
CT 02
**Cenário – Login com conta inexistente**
<br/>

* Dado que o usuário está na tela de login
* Quando inserir um número de conta inválido
* Então o sistema deve exibir uma mensagem de erro

<br/>
CT 03
**Cenário – Logout da conta**
<br/>

* Dado que o usuário está logado
* Quando clicar em "Sair da conta"
* Então o sistema deve encerrar a sessão e redirecionar para a tela de login

<br/>


## Consulta de Saldo
<br/>
CT 04 
**Cenário – Exibição correta do saldo**
<br/>

* Dado que o usuário está logado
* Quando acessar a tela inicial
* Então o saldo deve ser exibido corretamente

<br/>


## Depósito
<br/>
CT 05
**Cenário – Depósito de valor positivo**
<br/>

* Dado que o usuário deseja fazer um depósito
* Quando inserir um valor válido e confirmar
* Então o sistema deve adicionar o valor ao saldo e exibir uma mensagem de sucesso

<br/>
CT 06
**Cenário – Depósito de valor negativo ou zero**
<br/>

* Dado que o usuário deseja fazer um depósito
* Quando inserir um valor negativo ou zero
* Então o sistema deve exibir uma mensagem de erro e não alterar o saldo

<br/>


## Saque
<br/>
CT 07
**Cenário – Saque com saldo suficiente**
<br/>

* Dado que o usuário tem saldo suficiente
* Quando inserir um valor válido e confirmar
* Então o sistema deve descontar o valor do saldo e exibir uma mensagem de sucesso

<br/>
CT08
**Cenário – Saque com saldo insuficiente**
<br/>

* Dado que o usuário deseja sacar um valor maior que o saldo disponível
* Quando tentar confirmar o saque
* Então o sistema deve exibir uma mensagem de erro e impedir a transação

<br/>


## Transferência
<br/>
CT 09
**Cenário – Transferência bem-sucedida**
<br/>

* Dado que o usuário deseja transferir um valor para outro destinatário
* Quando inserir um valor válido e um destinatário correto
* Então o sistema deve descontar o saldo do remetente e creditar o destinatário

<br/>
CT 10
**Cenário – Transferência para conta inexistente**
<br/>

* Dado que o usuário deseja transferir um valor
* Quando inserir um número de conta inválido
* Então o sistema deve exibir uma mensagem de erro e não realizar a transferência

<br/>


## Histórico de Transações
<br/>
CT 11
**Cenário – Exibição correta do histórico**
<br/>

* Dado que o usuário realizou transações
* Quando acessar a aba de histórico
* Então todas as transações devem ser exibidas corretamente com data, valor e tipo