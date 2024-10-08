# 🏦 Sistema Bancário em Python
Este projeto é uma aplicação de um sistema bancário básico escrito em Python, utilizando conceitos de orientação a objetos (OO), como herança e polimorfismo. O sistema gerencia contas correntes de clientes, permitindo realizar depósitos, saques e visualizar extratos de forma simples

⚙️ Funcional
Criar clientes:

Criar contas correntes:

Realizar depósitos e saques :

Exibir extratos :

Limites de saque:

🏗️ Estrutura das
1. Cliente
Uma aulaClienterepresentantePessoaFisicaherdaClientee

2.
A classe Contaé

3. ContaCorr
Uma aulaContaCorrentedelaContae

4. Transação
Classe abstrata que define o comportamento de transações bancárias, como saques e depósitos. A aula Saquee Depositoimplementei essa abstração.

5. Histórico
Responsável por armazenar todas as transações realizadas em uma conta. Também é capaz de gerar relatórios detalhados sobre essas transações.

6. ContasIterador
Implemente um iterador que permite listar as contas do sistema de maneira simplificada.

7. Decoradores
@log_transacao: Usado para registrar e exibir o log quando uma transação é realizada.
🚀 Como Usar
1. Crie um novo cliente
O cliente pode ser fornecido com as seguintes informações:

Nome
CPF
Data de nascimento
Endereço
2. Crie uma nova conta
Após criar o cliente, você pode criar uma conta corrente fornecendo um número de conta exclusivo para o cliente.

3. Realizar depósitos
Selecione um cliente existente e realize um depósito na conta correspondente.

4. Realizar saques
Realize saques da conta do cliente, desde que haja saldo disponível e o limite de saques não tenha sido excedido.

5. Exibir extrato
Visualize todas as transações realizadas por um cliente, incluindo depósitos, saques e o saldo atual.

📋 Fluxo do Sistema
O sistema segue um fluxo contínuo através de um menu interativo, onde o usuário pode escolher as seguintes opções:

Depositário
Sacar
Exibir Extrato
Criar Cliente
Criar Conta
Listar Contas
Sair
🛠️ Requisitos
Python 3.6 ou superior.
