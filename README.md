# Sistema de Cadastro de Alunos com HashTable (Java)

**R.A.: 007194 - Adryan Santos**  
**R.A.: 007217 - Julia Sudario**

Este projeto é um sistema simples de cadastro e consulta de alunos utilizando a estrutura de dados `Hashtable` em Java. Ele foi desenvolvido para fins educacionais, demonstrando os conceitos de orientação a objetos, encapsulamento e uso de coleções da linguagem.

## 🗂 Estrutura do Projeto

- **`Aluno.java`**  
  Classe que representa um aluno, com atributos encapsulados como matrícula, nome, curso e e-mail.

- **`AppHashTable.java`**  
  Versão simples da aplicação utilizando um `Hashtable<String, String>` apenas com matrícula e nome do aluno.

- **`AppHashTableClass.java`**  
  Versão completa, utilizando `Hashtable<String, Aluno>` com todos os dados do aluno encapsulados em um objeto da classe `Aluno`.

## 🚀 Funcionalidades

Ambas as versões do sistema oferecem as seguintes funcionalidades via menu no terminal:

1. **Cadastrar aluno**  
   - Verifica se a matrícula já foi cadastrada.
   - Na versão completa (`AppHashTableClass.java`), armazena nome, matrícula, curso e e-mail.

2. **Listar todos os alunos**
   - Exibe o conteúdo completo do `Hashtable`.

3. **Buscar aluno por matrícula**
   - Localiza o aluno e exibe seus dados, caso exista.

4. **Sair**
   - Encerra o programa.

## 🧠 Conceitos Utilizados

- **Programação Orientada a Objetos (POO)**
  - Encapsulamento de atributos na classe `Aluno`.
  - Métodos `get` e `set`.
  - Método `toString()` para facilitar a exibição.

- **Estrutura de Dados**
  - Uso de `Hashtable` para armazenamento e busca eficiente por matrícula.

- **Entrada e Saída**
  - Entrada de dados pelo terminal usando `Scanner`.

## ✅ Como Executar

1. Compile todos os arquivos:
   ```bash
   javac Hash/*.java
   ```

2. Execute a aplicação desejada:

   - Versão simples:
     ```bash
     java Hash.AppHashTable
     ```

   - Versão completa:
     ```bash
     java Hash.AppHashTableClass
     ```

## 📌 Observações

- O projeto está estruturado no pacote `Hash`.
- A versão completa é recomendada por seguir boas práticas de encapsulamento e oferecer um modelo mais realista de cadastro de alunos.busca eficiente por matrícula.

- **Entrada e Saída**
  - Entrada de dados pelo terminal usando `Scanner`.

## ✅ Como Executar

1. Compile todos os arquivos:
   ```bash
   javac Hash/*.java
   ```

2. Execute a aplicação desejada:

   - Versão simples:
     ```bash
     java Hash.AppHashTable
     ```

   - Versão completa:
     ```bash
     java Hash.AppHashTableClass
     ```

## 📌 Observações

- O projeto está estruturado no pacote `Hash`.
- A versão completa é recomendada por seguir boas práticas de encapsulamento e oferecer um modelo mais realista de cadastro de alunos.
