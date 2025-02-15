# Teste Exploratório - Banco Teste

## Persona
**Nome:** Carlos Mendes  
**Idade:** 38 anos  
**Profissão:** Pequeno empresário  
**Perfil:** Carlos tem uma conta bancária que utiliza para gerenciar suas finanças pessoais e empresariais. Ele realiza depósitos frequentes, faz transferências para funcionários e precisa sacar dinheiro ocasionalmente. Ele está acostumado a usar aplicativos bancários, mas não é um especialista em tecnologia.

## Cenários de Teste Exploratório

### 1. Depósito bem-sucedido
**Ação:**
- Carlos insere um valor válido e clica em "Depositar".
- Verifica se o saldo é atualizado corretamente.

**Expectativa:**
- O saldo deve aumentar conforme o valor depositado.
- O sistema deve exibir uma mensagem de sucesso.

---

### 2. Saque bem-sucedido
**Ação:**
- Carlos tenta sacar um valor dentro do saldo disponível.
- Confirma se o saldo diminui corretamente.

**Expectativa:**
- O saldo deve ser reduzido corretamente.
- O sistema deve exibir uma mensagem de sucesso.

---

### 3. Tentativa de saque maior que o saldo
**Ação:**
- Carlos tenta sacar um valor superior ao saldo atual (exemplo: saldo R$1000, saque de R$1500).

**Expectativa:**
- O sistema deve impedir a operação e exibir uma mensagem de erro.

---

### 4. Transferência para outra conta
**Ação:**
- Carlos insere um número de conta válido e um valor para transferência.
- O sistema confirma a transação e reduz o saldo corretamente.

**Expectativa:**
- O saldo deve ser reduzido conforme o valor transferido.
- O destinatário deve receber o valor corretamente.
- O sistema deve exibir uma mensagem de sucesso.

---

### 5. Transferência para uma conta inexistente
**Ação:**
- Carlos tenta transferir dinheiro para um número de conta inválido.

**Expectativa:**
- O sistema deve exibir uma mensagem de erro clara informando que a conta não existe.
- O saldo não deve ser alterado.

---

### 6. Sessão e Segurança
**Ação:**
- Carlos sai da conta e tenta acessar novamente sem login.

**Expectativa:**
- O sistema deve impedir ações sem autenticação.
- O usuário deve ser redirecionado para a tela de login.

---

**Observações:**
- Testar mensagens de erro para garantir clareza ao usuário.
- Avaliar a responsividade da interface durante as interações.
- Verificar se há logs de transações disponíveis no histórico.


