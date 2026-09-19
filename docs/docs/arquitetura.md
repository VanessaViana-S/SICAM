# Arquitetura conceitual

A arquitetura atual do projeto utiliza o Microsoft Lists como estrutura de armazenamento e gerenciamento dos dados.

A evolução planejada considera a utilização de ferramentas do ecossistema Microsoft 365.

```text
                 SICAM
                   │
                   ▼
          ┌─────────────────┐
          │ Microsoft Lists │
          │ Base de dados   │
          └────────┬────────┘
                   │
          ┌────────┼────────┐
          │        │        │
          ▼        ▼        ▼
     Power Apps  Power    Power BI
                Automate
