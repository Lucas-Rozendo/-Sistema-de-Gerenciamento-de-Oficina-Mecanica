# Sistema de Gerenciamento para Oficina Mecânica

## Desenvolvido por

* Lucas Gabriel Rozendo da Silva
* Ricardo Francisco Real de Castro Junior

Acadêmicos de Engenharia de Software – ULBRA

---

## Sobre o Projeto

O Sistema de Gerenciamento para Oficina Mecânica é uma aplicação desktop desenvolvida em Java utilizando Programação Orientada a Objetos (POO) e interface gráfica Swing no Apache NetBeans.

O sistema foi criado para simular o gerenciamento de uma oficina mecânica, permitindo o controle de profissionais, proprietários, veículos, agendamentos e fichas de manutenção, aplicando conceitos fundamentais de desenvolvimento de software.

---

## Funcionalidades

### Gerenciamento de Profissionais

Cadastro e gerenciamento de profissionais da oficina.

#### Mecânicos

* Código
* Nome completo
* Lista de telefones
* Número de certificação
* Área de especialização

#### Atendentes

* Código
* Nome completo
* Lista de telefones
* Senha de acesso

#### Operações disponíveis

* Inserir
* Editar
* Excluir
* Listar
* Cadastro automático de dados de teste

---

### Gerenciamento de Proprietários

Cadastro de clientes da oficina contendo:

* Nome
* CPF
* Telefone

Cada proprietário pode possuir vários veículos cadastrados.

---

### Gerenciamento de Veículos

Cadastro e gerenciamento de veículos vinculados aos seus proprietários.

#### Informações cadastradas

* Placa
* Marca
* Modelo
* Ano de fabricação
* Cor
* Proprietário

#### Operações disponíveis

* Inserir
* Editar
* Excluir
* Listar
* Cadastro automático de dados de teste

---

### Gerenciamento de Categorias

As categorias são utilizadas para classificar os reparos realizados nos veículos.

#### Categorias de exemplo

* Motor
* Freios
* Suspensão
* Sistema Elétrico
* Estética Automotiva

#### Operações disponíveis

* Inserir
* Editar
* Excluir
* Listar
* Cadastro automático de categorias

---

### Gerenciamento de Agendamentos

Permite controlar os serviços programados para os veículos.

#### Informações do agendamento

* Código
* Data
* Hora
* Tipo de serviço
* Valor orçado
* Veículo associado
* Mecânico responsável

#### Validações implementadas

* Não permite veículos inexistentes.
* Não permite mecânicos inexistentes.
* Não permite profissionais que não sejam mecânicos.
* Não permite códigos duplicados.
* Não permite conflito de horário para o mesmo veículo.
* Não permite conflito de horário para o mesmo mecânico.
* Validação de data e horário.

#### Relatórios disponíveis

* Relatório por veículo.
* Relatório por mecânico.
* Relatório por data.
* Exibição geral dos cadastros.

#### Funcionalidades extras

* Cadastro automático de agendamentos de teste.
* Consulta rápida dos registros cadastrados.

---

### Gerenciamento de Fichas de Manutenção

Cada veículo pode possuir uma ficha de manutenção contendo diversos reparos realizados ao longo do tempo.

#### Informações da ficha

* Código da ficha
* Veículo associado
* Lista de reparos

#### Funcionalidades disponíveis

* Inserção de reparos
* Edição de reparos
* Exclusão de reparos
* Relatório completo da ficha
* Cálculo automático do custo total
* Contagem automática da quantidade de reparos
* Cadastro automático de fichas de teste

---

### Gerenciamento de Reparos

Cada reparo registrado possui:

* Código
* Nome do serviço
* Data de realização
* Custo
* Relato do problema
* Categoria
* Profissional responsável

---

## Tecnologias Utilizadas

* Java
* Apache NetBeans
* Java Swing
* Collections Framework (ArrayList)
* Programação Orientada a Objetos

---

## Conceitos Aplicados

* Encapsulamento
* Herança
* Polimorfismo
* Classes Abstratas
* Interfaces
* Agregação
* Relacionamento entre classes
* CRUD (Create, Read, Update e Delete)
* Tratamento de Exceções
* Interface Gráfica com Swing

---

## Estrutura do Projeto

```text
classes/
├── Profissional
├── Mecanico
├── Atendente
├── Proprietario
├── Veiculo
├── Categoria
├── Agendamento
├── Reparo
├── FichaManutencao
└── Interfaces

telas/
├── FormPrincipal
├── CadastroMecanicos
├── CadastroVeiculos
├── CadastroCategorias
├── CadastroFichasManutencao
└── GerenciarAgendamento
```

---

## Destaques do Projeto

* Interface gráfica desenvolvida com Java Swing.
* Utilização de classes abstratas para modelagem dos profissionais.
* Associação entre veículos e proprietários.
* Associação entre agendamentos, veículos e mecânicos.
* Controle de histórico de manutenção através das fichas.
* Relatórios para consulta dos dados cadastrados.
* Dados de teste para facilitar demonstrações e avaliações.

---

## Objetivo Acadêmico

Projeto desenvolvido para aplicação prática dos conceitos de Programação Orientada a Objetos, modelagem de classes, relacionamentos entre objetos, interfaces gráficas e manipulação de coleções em Java.

---

## Licença

Projeto desenvolvido exclusivamente para fins educacionais e acadêmicos.
