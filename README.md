# ☕ Disciplina Java 2 — Programação Avançada em Java

Este repositório reúne as atividades e conteúdos desenvolvidos ao longo da disciplina **Java 2**, parte do curso de **Pós-Graduação em Tecnologia Java**.  

A disciplina aprofunda os conhecimentos adquiridos em **Java 1**, explorando **Generics, Programação Funcional, Threads, Collections, API de Data e Hora, Manipulação de Arquivos** e os **Princípios SOLID**, por meio de atividades práticas e teóricas.

---

## 🧠 Conceitos-Chave

- **Programação Genérica:** uso de `Generics` para criar classes e métodos parametrizados.  
- **Programação Funcional:** expressões lambda, referências de método e Streams API.  
- **Manipulação de Arquivos:** leitura e escrita com `File`, `Files`, `BufferedReader`, `BufferedWriter`.  
- **Concorrência (Threads):** criação e controle de threads, sincronização e condições de corrida.  
- **Collections Framework:** listas, conjuntos, mapas e operações funcionais (`map`, `filter`, `reduce`).  
- **Date and Time API:** manipulação moderna de datas e horas com `LocalDate`, `LocalDateTime`, `Period`, `Duration`.  
- **Princípios SOLID:** boas práticas de design orientado a objetos (SRP, OCP, LSP, ISP, DIP).  
- **Boas práticas adicionais:** DRY, KISS, YAGNI — código limpo e de fácil manutenção.

---

## 🛠️ Tecnologias utilizadas

| Ferramenta | Descrição |
|-------------|------------|
| ☕ **Java SE 17** | Linguagem principal utilizada na disciplina |
| 🧰 **IDE** | NetBeans / IntelliJ IDEA / Eclipse |
| 📦 **APIs Java** | `java.util`, `java.io`, `java.time`, `java.util.concurrent`, `java.util.stream` |
| 🧪 **Execução** | Projetos executados via console (CLI) |
| 📚 **Referências** | *Java para Iniciantes – 6ª Edição* e documentação oficial da Oracle |

---

## 📚 Estrutura e Atividades da Disciplina

### 🧩 Bloco 1 — Programação Funcional e Generics
📅 *09/06/2025 – 22/06/2025*  

**Conteúdos abordados:**  
- Tipos Genéricos: classes e métodos parametrizados (`<T>`).  
- Expressões Lambda e Interfaces Funcionais (`Predicate`, `Function`, `Consumer`).  
- Streams API e operações funcionais (`filter`, `map`, `reduce`, `collect`).  

**Atividade:**  
📝 **B1A1 – Questionário sobre Generics**  
Fixação dos conceitos de tipagem genérica e lambdas.  

**Referências:**  
- *Java para Iniciantes – Cap. 13 e 14*  
- *Baeldung – Java 8 Streams & Lambdas*  
- *Java Magazine – Functional Programming in Java*

---

### 🗄️ Bloco 2 — Sistema de Arquivos (Java I/O)
📅 *23/06/2025 – 06/07/2025*  

**Conteúdos abordados:**  
- Entrada e saída de dados com `File`, `FileReader`, `FileWriter`, `BufferedReader`, `BufferedWriter`.  
- Criação, leitura, escrita e exclusão de arquivos.  
- Manipulação de diretórios e exceções de I/O.  

**Atividade prática:**  
💻 **B2A1 – Sistema de Arquivos**  
Implementação de um utilitário para:
- Listar arquivos de um diretório.  
- Ler e gravar conteúdo em arquivos `.txt`.  
- Criar e excluir diretórios.  
- Tratar exceções e exibir logs de operação.

**Referências:**  
- *Java Tutorial – Basic I/O*  
- *Coding with John – Java File I/O*  
- *Baeldung – Java IO API's*

---

### 🏎️ Bloco 3 — Threads e Concorrência
📅 *07/07/2025 – 20/07/2025*  

**Conteúdos abordados:**  
- Criação e execução de threads (`Thread`, `Runnable`).  
- Métodos de controle (`start`, `join`, `sleep`, `isAlive`).  
- Prioridades e sincronização (`synchronized`, `wait/notify`).  
- Condições de corrida e boas práticas de paralelismo.  

**Atividade prática:**  
💻 **B3A2 – Corrida de Motos**  
Simulação multithread de uma corrida com:
- Vários corredores (threads independentes).  
- Atualização paralela das posições.  
- Controle de tempo e identificação do vencedor.  
- Sincronização para evitar inconsistências.

**Referências:**  
- *Java para Iniciantes – Cap. 11*  
- *Baeldung – CountdownLatch vs Semaphore*  
- *JavaSpecialists – Synchronizing on value-based classes*

---

### 📊 Bloco 4 — Collections e Date Time API
📅 *21/07/2025 – 03/08/2025*  

**Conteúdos abordados:**  
- Uso de coleções (`List`, `Set`, `Map`) e operações funcionais.  
- Agrupamento, filtragem e ordenação de dados.  
- Manipulação de datas com `LocalDate`, `LocalDateTime`, `Period`, `Duration`.  

**Atividades práticas:**  
💻 **B4A1 – Contador de Vendas**  
Desenvolvimento de um sistema de contagem de vendas com:
- Uso de `Map` para agrupar produtos e quantidades.  
- Cálculo de totais, médias e estatísticas.  
- Aplicação de Streams e DateTime API.  

📝 **B4A2 – Questionário sobre Vendas**  
Fixação teórica sobre Collections e API de datas.  

**Referências:**  
- *Java Tutorial – Collections & Standard Calendar*  
- *Baeldung – Introduction to Java Date and Time API*  
- *Java2s – Collections and Date Time*

---

### 🧱 Bloco 5 — Princípios SOLID em Java
📅 *04/08/2025 – 17/08/2025*  

**Conteúdos abordados:**  
- Princípios de design de software:
  - **S** – Single Responsibility  
  - **O** – Open/Closed  
  - **L** – Liskov Substitution  
  - **I** – Interface Segregation  
  - **D** – Dependency Inversion  
- Acrônimos complementares: **DRY**, **KISS**, **YAGNI**.  
- Boas práticas de arquitetura orientada a objetos.  

**Atividade teórica:**  
🧩 **B5A1 – Praticando SOLID**  
Questionário para fixar os princípios e sua aplicação em código.

**Referências:**  
- *SOLID, KISS, YAGNI – DevMedia & DZone*  
- *Vídeoaula – Introdução ao SOLID e outros acrônimos*

---

## 🧾 Resumo Final

> A disciplina **Java 2** consolidou o domínio da linguagem com foco em **abstração, coleções, processamento funcional, manipulação de arquivos, concorrência e boas práticas de design orientado a objetos**.  
> As atividades práticas (**Sistema de Arquivos**, **Corrida de Motos**, **Contador de Vendas**) permitiram aplicar conceitos modernos do Java, explorando **Streams, Threads e Collections** em cenários reais, preparando o aluno para o desenvolvimento de aplicações robustas e escaláveis.

---
