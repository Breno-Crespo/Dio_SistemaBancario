# Sistema Bancário em Python
Este projeto é uma aplicação de um sistema bancário básico escrito em Python, utilizando conceitos de orientação a objetos (OO), como herança e polimorfismo. O sistema gerencia contas correntes de clientes, permitindo depósitos, saques, e visualização

Funcional
    .Criar clientes :
    .Criar contas correntes :
    .Realizar depósitos e saques: Os
    .Exibir extratos :
    .Limites:
    .Estrutura das Classes
    .Cliente
A classe Clienterepresenta um cliente do banco. A classe PessoaFisicaherdada Clientee adiciona atributos específicos como CPF e dados de nascimento.

Conta
A classe Contaé uma classe base para diferentes tipos de contas bancárias. Ela contém informações como saldo, número de conta e agência. Além disso, a classe gerencia transações como saque e depósito.

ContaCorrente
Herda de Contaregras adicionais específicas, como limite de saques e valor máximo de saque por transação.

Transacao
Classe abstrata que define o comportamento de transações bancárias, como saques e depósitos.

Historico
Responsável por armazenar todas as transações realizadas em uma conta e gerar relatórios com essas transações.

ContasIterador
Implementa um iterador que permite listar as contas do sistema de forma simplificada.

Decoradores
@log_transacao: Usado para registrar e exibir quando uma transação foi realizada.
Como usar
1. Crie um novo cliente
O cliente pode ser criado fornecendo informações básicas como nome, CPF, data de nascimento e endereço.

2. Crie uma nova conta
Depois de criar um cliente, é possível criar uma conta corrente para esse cliente, fornecendo um número de conta exclusivo.

3. Realizar depósitos
Após selecionar um cliente, é possível fazer depósitos na conta desse cliente.

4. Realizar saques
Da mesma forma, é possível realizar saques, desde que o cliente tenha saldo disponível e não tenha excedido o limite de saques.

5. Exibir extrato
O sistema gera um extrato com todas as transações realizadas por um cliente específico.

Fluxo do Sistema
O sistema segue um fluxo em contínuo um menu interativo, onde o usuário pode escolher depósitos, saques, criar clientes, criar contas, listar contas e exibir extratos.

Requisitos
Python 3.6 ou superior.
