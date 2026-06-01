# 🚗 Sistema de Gerenciamento de Oficina Mecânica

Projeto desenvolvido para a disciplina de Programação Orientada a Objetos utilizando Java e Swing.

## 📋 Descrição

O sistema simula o gerenciamento de uma oficina mecânica, permitindo o cadastro e controle de:

- Mecânicos
- Proprietários
- Veículos
- Categorias de reparo
- Fichas de manutenção
- Reparos realizados

O projeto foi desenvolvido com foco na aplicação de conceitos de Programação Orientada a Objetos, como:

- Encapsulamento
- Herança
- Polimorfismo
- Classes Abstratas
- Interfaces
- Composição
- Relacionamentos entre objetos
- Coleções (ArrayList)

---

## 🛠 Funcionalidades

### Mecânicos
- Cadastro de mecânicos
- Edição de informações
- Exclusão
- Listagem

### Veículos
- Cadastro de veículos
- Associação com proprietários
- Edição
- Exclusão
- Listagem

### Categorias
- Cadastro de categorias de reparo
- Edição
- Exclusão
- Listagem

### Fichas de Manutenção
- Cadastro de ficha para veículo
- Controle de reparos realizados
- Cálculo automático do custo total
- Relatório completo da manutenção
- Controle para impedir múltiplas fichas para o mesmo veículo

### Reparos
- Registro de serviços realizados
- Associação com categoria
- Associação com profissional responsável
- Registro de custo e relato técnico

---

## 🧩 Conceitos de POO Aplicados

### Herança

```java
Profissional
    └── Mecanico
```

### Interface

```java
GerenciarFichaManutencao
```

Implementada pela classe:

```java
FichaManutencao
```

### Composição

```java
FichaManutencao
    └── Reparo
```

Os reparos são criados e gerenciados dentro da ficha de manutenção.

---

## 💻 Tecnologias Utilizadas

- Java
- Swing (JFrame e JDialog)
- NetBeans IDE
- Programação Orientada a Objetos

---

## 📷 Telas do Sistema

### Tela Principal

- Cadastro de Mecânicos
- Cadastro de Veículos
- Cadastro de Categorias
- Cadastro de Fichas de Manutenção

### CRUD Completo

- Inserir
- Editar
- Excluir
- Listar

---

## 🚀 Como Executar

1. Clone o repositório

```bash
git clone https://github.com/seuusuario/nome-do-repositorio.git
```

2. Abra o projeto no NetBeans

3. Execute a classe:

```java
FormPrincipal.java
```

---

## 👨‍💻 Autor

Lucas Gabriel Rozendo da Silva

Estudante de Engenharia de Software – ULBRA

Projeto desenvolvido para fins acadêmicos.
