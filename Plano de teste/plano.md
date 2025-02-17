Descrição
Plano de Testes
Informações gerais :

 

# Visão geral
<br/>

 ## Um plano de testes para clarificar a todos envolvidos o que será testado.
<br/>

## Identificador único
<br/>

#0001
<br/>

## Organizador responsável
<br/>

* Lucas Oliveira Rodrigues
<br/>

## Aprovadores
<br/>

Fulano de tal (QA Specialist)
<br/>
 

Histórico de mudanças

* 16/Fevereiro/2025 crie o Plano 
* 16/Fevereiro/2025 finalizei o Plano
<br/>
 

## Escopo geral
<br/>

* Projeto do Banco Teste 

* Teste Funcional Banco Teste
<br/>

## Não está no escopo da User Story do Banco Teste testar as funcionalidades de:
<br/>

N/A
<br/>
 

## Referências
<br/>

Mapa mental do Banco Teste.

(![alt text](<../assets/mapa mental desafio.png>))

 

<br/>
 
 
Glossário de Termos



 

Contexto do teste

 

Projetos ou Sub-processos de Teste

Banco Teste
<br/>
 

## Itens de teste
<br/>

Banco Teste
<br/>
 

## Escopo do teste
<br/>

**Serão Testados:**
<br/>

* Banco Teste Funcional


<br/>
 

## Não serão testados:
<br/>

* N/A

<br/>


## Stakeholders
<br/>

* Fulano de tal (QA Specialist)
<br/>


## Registro de risco de comunicação de teste :
<br/>
 

* Riscos do produto

* Cobertura Incompleta de Testes : ( testes manuais podem deixar passar alguns cenários ) .

* Erros Humanos : (O teste manual está sujeito a erros humanos e pode haver inconsistência na forma como os testes são realizados) .

* Rastreabilidade : (Pode ser difícil rastrear quais testes foram executados, quais cenários foram cobertos, e quais resultados foram obtidos) .

* Tela de cadastro e Login : (Devido a falta de criação dessas duas telas, projeto já está comprometido) .
<br/>
 

## Riscos do projeto
<br/>

*  Devida a pouca experiência , esse plano possa ter a execução ineficiente de testes e planejamento de testes inadequado .

 

## Estratégia de teste :
<br/>
 

* O planejamento de testes para o Banco Teste  visa garantir que todas as funcionalidades sejam testadas de forma abrangente e estruturada .
<br/>

## Teste de sub-processos
<br/>

* Banco Teste
<br/>
 

## Entregáveis de teste
<br/>

* Plano de teste ;

* Cenário Macro ;

* Matriz de rastreabilidade ;

* Relatório de teste ;

* Critérios para Seleção de Testes para Automação .


 <br/>

## Técnicas de teste
<br/>

* Partição de Equivalência ;
* Valor Limite ;
* Criação de Persona .

<br/>
 

## Critérios de conclusão de teste
<br/>

* 100% dos incidentes com prioridade média , alta e critica , foram corrigidos e fechados
<br/>

## Métricas a serem coletadas .
<br/>

* 100% de defeitos corrigidos e fechados .
<br/>
 

## Requisitos de dados de teste
<br/>

* Que as telas do Banco Teste já estejam prontas .
<br/>
 

## Requisitos do ambiente de teste
<br/>

* Os testes serão realizados exclusivamente na web, utilizando o banco de  testes disponível.

<br/>

## Novos testes e testes de regressão
<br/>

* Novos testes a cada nova entrega

* Testes regressivos antes da entrega para a próxima fase
<br/>
 

## Critérios de suspensão e retomada
<br/>

* Banco Teste ficar sem a cosntruçao da tela de cadastro e login por mais de 3 dias (Suspensão)

* Banco Teste retornou a operação e está no ar por mais de 24 horas (Retomada)
<br/>
 

## Desvios da Estratégia de Teste Corporativa
<br/>

* Nesse projeto, dado a pequena quantidade a ser testada , será necessário só um testador .
<br/>
 

## Cenários Macro
<br/>
              Funcional
<br/>

* Cenário 1 :  Login com credenciais válidas
* Cenário 2 :  Login com conta inexistente
* Cenário 3 :  Logout da conta
* Cenário 4 :  Exibição correta do saldo
* Cenário 5 :  Depósito de valor positivo
* Cenário 6 :  Depósito de valor negativo ou zero
* Cenário 7 :  Saque com saldo suficiente
* Cenário 8 :  Saque com saldo insuficiente
* Cenário 9 :  Transferência bem-sucedida
* Cenário 10 : Transferência para conta inexistente
* Cenário 11 : Exibição correta do histórico

<br/>

        

## Matriz de Rastreabilidade
<br/>
# Matriz de Rastreabilidade

| ID do Cenário | Cenário de Teste                           | Status        |
|--------------|-------------------------------------------|--------------|
| 1            | Login com credenciais válidas            | Concluída ✅ |
| 2            | Login com conta inexistente              | Concluída ✅ |
| 3            | Logout da conta                          | Concluída ✅ |
| 4            | Exibição correta do saldo               | Concluída ✅ |
| 5            | Depósito de valor positivo              | Concluída ✅ |
| 6            | Depósito de valor negativo ou zero      | Concluída ✅ |
| 7            | Saque com saldo suficiente              | Concluída ✅ |
| 8            | Saque com saldo insuficiente            | Concluída ✅ |
| 9            | Transferência bem-sucedida              | Concluída ✅ |
| 10           | Transferência para conta inexistente    | Concluída ✅ |
| 11           | Exibição correta do histórico          | Concluída ✅ |

<br/>



 
<br/>

## Testes Candidatos à Automação

<br/>
### **Filmes**

- **Cenário 1**: Login com credenciais válidas
  - **Justificativa**: Pode ser testado com automação verificando a resposta do servidor e a sessão ativa .

- **Cenário 2**: Login com conta inexistente
  - **Justificativa**: Pode ser testado verificando se o sistema retorna erro adequado.

- **Cenário 4**: Exibição correta do saldo .
  - **Justificativa**: Pode ser validado automaticamente verificando se o saldo exibido corresponde ao esperado.

- **Cenário 5**: Depósito de valor positivo .
  - **Justificativa**: O teste pode validar a atualização do saldo após o depósito.

- **Cenário 6**: Depósito de valor negativo ou zero .
  - **Justificativa**: Pode ser automatizado verificando se o sistema impede a operação e exibe uma mensagem de erro.

- **Cenário 7**: Saque com saldo suficiente .
  - **Justificativa**: Pode ser validado verificando a atualização correta do saldo após o saque.

- **Cenário 8**: Saque com saldo insuficiente .
  - **Justificativa**: Pode ser testado automatizando a resposta do sistema ao bloquear o saque.

- **Cenário 9**: Transferência bem-sucedida .
  - **Justificativa**: Pode ser automatizado verificando a atualização do saldo das contas envolvidas.

- **Cenário 10**: Transferência para conta inexistente .
  - **Justificativa**: Pode ser testado verificando a resposta do sistema ao impedir a operação.



<br/>
 



## Tipos de Testes Funcional
<br/>

* Teste de Interface

<br/>




## Ambiente de Teste
<br/>

* Testes realizados em ambiente web ;
* Sistemas operacionais: Windows 10 home pro .


<br/>

## Ferramentas Utilizadas
<br/>

* Git 
* Github
* Xmind

  
<br/>

## Execução do Teste
<br/>

* Acessar a página do linkedin e encontrar a publicação da vaga

* Clicar no link do teste

* Baixar o Vs Code
<br/>

## Atividades e estimativas :
<br/>
 
**Atividades de teste e estimativas**
<br/>

* Revisão de documentos, Lucas e 1 dia .

* Elaboração de cenários de teste, Lucas e 1 dia .
 

## Equipe :
<br/>
 

**Funções, atividades e responsabilidades**
<br/>

* Analista de Testes, Lucas , Criar cenários e casos de teste e executa-los .

  
   
<br/>
 

## Necessidades de contratação
<br/>

* Pra esse projeto não houve necessidade da contratação de nenhum serviço .
<br/>

## Necessidades de treinamento
<br/>

* N/A


<br/>
 

## Cronograma :
<br/>
 

* 15 de Fevereiro ~ 15 de Fevereiro : Criação do Mapa Mental;
* 15 de Fevereiro ~ 15 de Fevereiro : Criação do Plano de teste;
* 15 de Fevereiro ~ 15 de Fevereiro : Criação do Cenário de teste;
* 15 de Fevereiro ~ 15 de Fevereiro : Criação do Caso de teste;
* 15 de Fevereiro ~ 15 de Fevereiro : Execução do Caso de teste;
* 15 de Fevereiro ~ 15 de Fevereiro : Criação do Relatorio de teste;
* 15 de Fevereiro ~ 15 de Fevereiro : Criação do Reporter Bug;
* 15 de Fevereiro ~ 15 de Fevereiro : Revisão de todos os documentos feitos;
* 15 de Fevereiro ~ 15 de Fevereiro : Entrega do Projeto via email para a Empresa;
