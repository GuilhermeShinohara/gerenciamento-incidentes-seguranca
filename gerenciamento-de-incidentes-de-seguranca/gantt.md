# 📅 Cronograma do Projeto

O planejamento do projeto foi estruturado em fases sequenciais que abrangem todo o ciclo de vida do desenvolvimento de software, desde a definição inicial do problema até a implantação da solução.

## Visão Geral

O cronograma contempla atividades de concepção, levantamento de requisitos, planejamento da infraestrutura, desenvolvimento, testes e implantação, garantindo uma abordagem organizada para execução do projeto.

### Diagrama de Gantt (PlantUML)

```plantuml
@startgantt
title Cronograma do Projeto - Sistema de Gerenciamento de Incidentes de Segurança

Project starts 2026-05-25

-- Planejamento --
[Concepção] lasts 12 days
[Levantamento de Requisitos] lasts 16 days

-- Arquitetura e Infraestrutura --
[Infraestrutura e Segurança] lasts 11 days

-- Desenvolvimento --
[Implementação da Solução] lasts 37 days

-- Validação --
[Testes e Homologação] lasts 15 days

-- Implantação --
[Implantação e Treinamento] lasts 8 days

[Levantamento de Requisitos] starts at [Concepção]'s end
[Infraestrutura e Segurança] starts at [Levantamento de Requisitos]'s end
[Implementação da Solução] starts at [Infraestrutura e Segurança]'s end
[Testes e Homologação] starts at [Implementação da Solução]'s end
[Implantação e Treinamento] starts at [Testes e Homologação]'s end

@endgantt
```

> Recomenda-se exportar este diagrama para PNG e disponibilizá-lo na pasta `docs/cronograma.png` para melhor visualização no GitHub.

---

## 🔄 Fluxo de Execução

O desenvolvimento segue uma sequência lógica de dependências entre as etapas do projeto.

```text
Concepção
    ↓
Levantamento de Requisitos
    ↓
Definição da Arquitetura
    ↓
Infraestrutura e Segurança
    ↓
Desenvolvimento da Solução
    ↓
Testes e Homologação
    ↓
Implantação e Treinamento
    ↓
Monitoramento Inicial
```

---

## 📊 Resumo do Planejamento

| Fase | Objetivo | Duração |
|--------|-----------|----------|
| Concepção | Definição do escopo, objetivos e viabilidade do projeto | 12 dias |
| Levantamento de Requisitos | Identificação dos requisitos funcionais e não funcionais | 16 dias |
| Infraestrutura e Segurança | Planejamento do ambiente e requisitos de segurança | 11 dias |
| Desenvolvimento | Construção dos módulos e funcionalidades da solução | 37 dias |
| Testes e Homologação | Validação funcional, integração e segurança | 15 dias |
| Implantação e Treinamento | Disponibilização da solução e capacitação dos usuários | 8 dias |

**Duração total planejada:** 99 dias.

---

## ⚙️ Dependências entre Atividades

```text
Concepção
   └──► Levantamento de Requisitos
            └──► Infraestrutura e Segurança
                     └──► Desenvolvimento
                              └──► Testes e Homologação
                                       └──► Implantação e Treinamento
```

---

## 🎯 Entregas por Fase

### Concepção
- Definição do problema
- Objetivos do projeto
- Escopo inicial
- Identificação dos stakeholders

### Levantamento de Requisitos
- Casos de uso
- Regras de negócio
- Requisitos funcionais
- Requisitos não funcionais

### Infraestrutura e Segurança
- Definição da arquitetura
- Estratégias de criptografia
- Controle de acesso RBAC
- Auditoria e integridade de dados

### Desenvolvimento
- Sistema de Registro de Incidentes
- Painel Investigativo
- Workflow do Comitê de Segurança
- Integração dos módulos

### Testes e Homologação
- Testes unitários
- Testes de integração
- Testes de carga
- Testes de segurança

### Implantação e Treinamento
- Configuração do ambiente
- Homologação final
- Treinamento dos usuários
- Entrada em produção
