# **Trabalho Final \- Programação Orientada a Objetos**

## **Identificação**

* **Instituição:** Universidade Federal de Goiás (UFG) \- Instituto de Informática (INF)
* **Aluno:** José Eduardo Gontijo de Carvalho \- Matrícula: 202300419
* **Data:** 22 de maio de 2026
* **Tema:** Sistema de Acompanhamento Nutricional

## **1\. Definição do Problema**

A prática dietética exige o gerenciamento preciso de dados antropométricos, cálculos metabólicos e a formulação de planos alimentares detalhados. Atualmente, muitos profissionais e estudantes dependem de planilhas genéricas ou anotações manuais, o que fragmenta as informações e aumenta a suscetibilidade a erros nos cálculos de Valor Energético Total (VET) e Necessidade Energética Total (NET). A ausência de um sistema local, unificado e de fácil operação dificulta o acompanhamento contínuo da evolução do paciente e a organização do catálogo de alimentos e substituições.

## **2\. Escopo do Trabalho**

O presente projeto visa desenvolver um sistema de software em Java com interface gráfica, focado na gestão da prática dietética e prescrição nutricional. O escopo abrange o gerenciamento (Inclusão, Exclusão, Alteração, Consulta e Lista) do cadastro de pacientes, o controle de um banco de alimentos (com detalhamento de macronutrientes) e a elaboração de planos alimentares. O sistema realizará de forma automatizada o cálculo de necessidades metabólicas. Estão fora do escopo a integração com aplicativos móveis para o paciente final, processamento de pagamentos ou agendamento de consultas. O foco principal é a aplicação estruturada da Programação Orientada a Objetos, garantindo a persistência dos dados localmente através da leitura e gravação de objetos em arquivos.

## **3\. Lista de Requisitos**

### **Requisitos Funcionais**

* **RF01 \- Gestão de Pacientes:** O sistema deve permitir operações completas de manutenção (Inclusão, Exclusão, Alteração, Consulta e Listagem) de dados e avaliações dos pacientes.
* **RF02 \- Cálculos Metabólicos:** O sistema deve calcular automaticamente as necessidades calóricas (VET e NET) do paciente a partir de seus dados biométricos.
* **RF03 \- Banco de Alimentos:** O sistema deve manter um catálogo de alimentos, permitindo registrar calorias, carboidratos, proteínas e gorduras por porção.
* **RF04 \- Gestão de Planos Alimentares:** O sistema deve permitir a montagem de dietas, associando alimentos a refeições específicas e vinculando o plano a um paciente.
* **RF05 \- Validação Nutricional:** O sistema deve totalizar as calorias e macronutrientes do plano alimentar elaborado, permitindo a comparação direta com os valores metabólicos calculados.

### **Requisitos Não Funcionais**

* **RNF01 \- Linguagem e Arquitetura:** O sistema deverá ser desenvolvido em linguagem Java, aplicando conceitos de herança, classes abstratas e/ou interfaces.
* **RNF02 \- Persistência:** O meio de armazenamento dos dados será através da leitura e gravação de objetos em arquivos locais.
* **RNF03 \- Interface:** A interação com o usuário deverá ocorrer por meio de interface gráfica.
* **RNF04 \- Tratamento de Exceções:** O sistema deve possuir uma classe de exceção própria voltada a uma restrição do problema (exemplo: restrição de limite calórico excedido).

### **Files**
![Use Cases](https://github.com/joseduardogon/sistema_acompanhamento_nutricional/blob/main/documents/Sistema%20de%20Acompanhamento%20Nutricional%20-%20Use%20Cases.png)

![Class Diagram](https://github.com/joseduardogon/sistema_acompanhamento_nutricional/blob/main/documents/Sistema%20de%20Acompanhamento%20Nutricional%20-%20UML%20Diagram.png)