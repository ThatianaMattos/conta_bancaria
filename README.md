# Projeto Conta Bancária – Módulo TypeScript (Generation)

Sistema bancário desenvolvido durante as aulas do módulo de TypeScript da Generation Brasil.  
O objetivo é praticar Programação Orientada a Objetos, Repository Pattern, Interfaces, abstração e operações bancárias via console.

## 📌 Funcionalidades Implementadas

### 💼 Operações bancárias

- Criar conta  
- Listar contas  
- Buscar por número  
- Atualizar dados  
- Apagar conta  
- Sacar  
- Depositar  
- Transferir valores  

## 🧱 Estrutura orientada a objetos

### 🏦 Classe Conta (abstrata)

- Número  
- Agência  
- Tipo  
- Titular  
- Saldo  
- Métodos sacar, depositar e visualizar  

### 💳 Conta Corrente

- Limite adicional  
- Saque com limite  

### 🏦 Conta Poupança

- Dia do aniversário  
- Depósito e saque comuns  

### 📂 Repository Pattern

- Armazena e manipula todas as contas do sistema  
- Busca, lista e controla operações  

### 🧮 Controller

- Regras de negócio  
- Manipula operações bancárias  
- Integra Menu com Repository  

### 🖥️ Menu (console)

- Interface de operação via console  
- Inputs, prints e fluxo da aplicação  

## ▶️ Como Executar

```bash
npm install
ts-node Menu.ts

📥 Como Clonar este Repositório
git clone https://github.com/ThatianaMattos/conta_bancaria.git
cd conta_bancaria
npm install
ts-node Menu.ts

📚 Sobre a Documentação do Projeto

A documentação utilizada para estudo foi fornecida internamente pela Generation Brasil.
Por política da instituição, ela não pode ser compartilhada publicamente.
