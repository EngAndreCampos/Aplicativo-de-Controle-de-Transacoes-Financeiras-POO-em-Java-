# 💰 Aplicativo de Controle de Transações Financeiras (POO em Java)

Este projeto implementa um **sistema de controle financeiro pessoal**, desenvolvido com **Programação Orientada a Objetos (POO)** em Java.  
O aplicativo permite registrar **receitas**, **despesas**, listar transações e calcular o **saldo total**.

---

## 🧭 Objetivo

O objetivo é praticar os princípios fundamentais de **POO**, como:
- **Abstração**
- **Encapsulamento**
- **Herança**
- **Polimorfismo**

ao mesmo tempo em que se cria uma aplicação funcional e útil para o controle financeiro do usuário.

---

🧠 Conceitos POO Aplicados
- Conceito	Descrição
- Abstração	A classe Transacao define o modelo genérico de uma transação.
- Encapsulamento	Os atributos são privados e acessados por getters.
- Herança	Receita e Despesa herdam de Transacao.
- Polimorfismo	O GerenciadorFinanceiro manipula objetos Transacao de tipos diferentes (receitas e despesas).

## 🏗️ Estrutura do Projeto

src/
├── Main.java
├── model/
│ ├── Transacao.java
│ ├── Receita.java
│ └── Despesa.java
└── service/
└── GerenciadorFinanceiro.java

---

## 🧩 Descrição das Classes

| Classe | Função |
|--------|--------|
| **Transacao (abstrata)** | Define os atributos e comportamentos comuns de uma transação (descrição, valor, data). |
| **Receita** | Representa uma entrada de dinheiro (herda de `Transacao`). |
| **Despesa** | Representa uma saída de dinheiro (herda de `Transacao`). |
| **GerenciadorFinanceiro** | Responsável por armazenar, listar e calcular o saldo das transações. |
| **Main** | Contém o menu principal e a interação com o usuário. |

---

## 🧠 Funcionalidades

✅ Adicionar **Receitas**  
✅ Adicionar **Despesas**  
✅ Listar **todas as transações**  
✅ Calcular **saldo atual**  
✅ Utilizar **POO** com boas práticas de encapsulamento e herança  

---

## 💻 Tecnologias Utilizadas

- **Linguagem:** Java (JDK 8 ou superior)  
- **Paradigma:** Programação Orientada a Objetos (POO)  
- **Bibliotecas padrão:** `java.util`, `java.time`  

---

## ⚙️ Como Executar o Projeto

### Pré-requisitos:
- Java instalado e configurado no PATH
- Um terminal ou IDE (IntelliJ, Eclipse ou VS Code com extensão Java)

### Passos:
1. Clone ou baixe o projeto.
2. No terminal, vá até a pasta `src/`.
3. Compile o código:
   ```bash
   javac Main.java model/*.java service/*.java
4. Execute o programa:
   java Main

---

Exemplo de Execução
=== 💰 Aplicativo de Controle Financeiro ===
1. Adicionar Receita
2. Adicionar Despesa
3. Listar Transações
4. Ver Saldo Atual
0. Sair
Escolha uma opção: 1
Descrição: Salário
Valor: 5000
✅ Receita adicionada com sucesso!

Escolha uma opção: 2
Descrição: Aluguel
Valor: 1800
✅ Despesa adicionada com sucesso!

Escolha uma opção: 4
💵 Saldo Atual: R$ 3200.00

Escolha uma opção: 3
📋 Lista de Transações:
[Receita] Salário - R$ 5000.00 (22/10/2025)
[Despesa] Aluguel - R$ 1800.00 (22/10/2025)

---

👨‍💻 Autor
Desenvolvido por [André Campos] 💻
📅 Data: Outubro de 2025
🎓 Projeto educacional para prática de Programação Orientada a Objetos em Java.

📝 Licença
Este projeto é de uso educacional e pode ser livremente modificado ou distribuído.

