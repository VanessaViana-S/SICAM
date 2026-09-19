# SICAM

## Sistema Integrado de Conflitos Agrários e Mediação

Projeto de reestruturação e organização de dados para registro e acompanhamento de conflitos agrários, utilizando o Microsoft Lists como estrutura atual da solução.

---

## Sobre o projeto

O SICAM — Sistema Integrado de Conflitos Agrários e Mediação — surgiu a partir da necessidade de melhorar a organização, o registro e o acompanhamento das informações relacionadas aos conflitos agrários.

O projeto propõe uma estrutura mais organizada e padronizada para os dados, permitindo facilitar o acompanhamento das informações e criar uma base para futuras evoluções tecnológicas.

---

## Objetivo

O projeto tem como objetivo estruturar e organizar as informações relacionadas aos conflitos agrários, buscando:

- padronizar o registro das informações;
- melhorar a organização dos dados;
- facilitar o acompanhamento dos conflitos;
- centralizar informações relevantes para o acompanhamento dos casos;
- reduzir dificuldades relacionadas à utilização da estrutura anterior;
- preparar a base para futuras automações e aplicações.

---

## Situação atual

Atualmente, o SICAM está implementado utilizando o **Microsoft Lists**, integrado ao ambiente Microsoft 365.

A estrutura foi reorganizada para permitir o registro padronizado das informações dos conflitos e seu acompanhamento pela equipe.

A utilização da nova estrutura teve início em setembro de 2026 e a migração dos dados existentes está ocorrendo de forma gradual.

---

## Estrutura atual

A estrutura do SICAM contempla diferentes grupos de informações, incluindo:

- Identificação do conflito;
- Localização;
- Caracterização;
- Atores envolvidos;
- Direitos e violência;
- Gestão e acompanhamento;
- Movimentações;
- Histórico das atualizações.

---

## Protótipos

Durante o desenvolvimento do projeto foram elaborados protótipos conceituais para representar a evolução futura da solução.

Entre as telas previstas estão:

- Tela inicial;
- Consulta de conflitos;
- Cadastro de novo conflito;
- Detalhes do conflito.

Os protótipos representam uma proposta de interface para uma futura aplicação e **não correspondem a uma aplicação Power Apps já implementada**.

---

## Evolução planejada

A estrutura atual em Microsoft Lists foi pensada como base para futuras evoluções do projeto.

### Power Apps

Está prevista a reconstrução do SICAM utilizando o **Microsoft Power Apps**, utilizando a estrutura criada no Microsoft Lists como fonte de dados.

A futura aplicação deverá permitir uma experiência de utilização mais estruturada para cadastro, consulta e acompanhamento dos conflitos.

### Power Automate

Também estão previstas futuras automações utilizando o **Power Automate**, possibilitando recursos como:

- notificações;
- acompanhamento de prazos;
- avisos de atualização;
- registro de movimentações;
- automatização de tarefas repetitivas.

### Power BI

O **Power BI** poderá ser utilizado futuramente para criação de indicadores e painéis de acompanhamento, utilizando os dados estruturados no Microsoft Lists.

Entre os possíveis indicadores estão:

- quantidade de conflitos;
- distribuição territorial;
- situação dos acompanhamentos;
- natureza dos conflitos;
- evolução dos registros;
- movimentações e providências.

> As integrações com Power Apps, Power Automate e Power BI ainda não estão implementadas neste projeto.

---

## Tecnologias

### Implementado

- Microsoft Lists
- Microsoft 365

### Planejado

- Microsoft Power Apps
- Microsoft Power Automate
- Microsoft Power BI

---

## Organização do repositório

```text
SICAM/
│
├── README.md
│
├── imagens/
│   ├── tela-inicial.png
│   ├── cadastro-conflito.png
│   ├── consulta-conflitos.png
│   └── detalhes-conflito.png
│
├── docs/
│   ├── projeto.md
│   └── arquitetura.md
│
├── modelos/
│   └── estrutura-listas.md
│
└── planejamento/
    ├── power-apps.md
    ├── power-automate.md
    └── power-bi.md
