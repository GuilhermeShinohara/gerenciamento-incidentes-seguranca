# 🛡️ Sistema de Gerenciamento de Incidentes de Segurança

> Projeto de Engenharia de Software focado na análise, modelagem, planejamento e especificação de uma solução para gerenciamento de incidentes de segurança da informação.

<p align="center">

![Status](https://img.shields.io/badge/Status-Concluído-success)
![Área](https://img.shields.io/badge/Área-Segurança%20da%20Informação-blue)
![Disciplina](https://img.shields.io/badge/Foco-Engenharia%20de%20Software-orange)
![Documentação](https://img.shields.io/badge/Documentação-Completa-brightgreen)

</p>

---

# 📖 Sobre o Projeto

O Sistema de Gerenciamento de Incidentes de Segurança foi concebido para apoiar organizações no registro, acompanhamento, investigação e resolução de incidentes de segurança da informação.

O projeto foi desenvolvido utilizando práticas de Engenharia de Software, Segurança da Informação e Gestão de Projetos, contemplando desde a definição do problema até a modelagem da solução, análise de riscos, planejamento da infraestrutura e definição do ciclo de vida do sistema.

A proposta busca garantir rastreabilidade, integridade das informações, preservação de evidências digitais e suporte à tomada de decisão durante o tratamento de incidentes.

---

# 🎯 Objetivos

* Registrar incidentes de segurança da informação.
* Garantir rastreabilidade das ações executadas.
* Preservar evidências digitais.
* Apoiar processos de investigação.
* Controlar o fluxo de aprovação dos incidentes.
* Facilitar auditorias e processos de conformidade.
* Apoiar o Comitê de Segurança na tomada de decisão.
* Fornecer histórico completo de ocorrências.

---

# 🚨 Problema de Negócio

Incidentes de segurança precisam ser registrados, investigados e resolvidos de forma estruturada.

Sem um sistema adequado, organizações podem enfrentar problemas como:

* Perda de evidências;
* Falta de rastreabilidade;
* Erros de comunicação;
* Dificuldade de auditoria;
* Falhas de conformidade;
* Atraso na resposta aos incidentes.

Este projeto propõe uma solução capaz de centralizar e padronizar todo o processo de tratamento de incidentes.

---

# 🔄 Fluxo de Tratamento de Incidentes

```text
Usuário
    ↓
Reportar Incidente
    ↓
Registro da Ocorrência
    ↓
Classificação e Priorização
    ↓
Investigação
    ↓
Registro de Evidências
    ↓
Análise do Comitê de Segurança
    ↓
Resolução
    ↓
Relatório Final
    ↓
Encerramento
```

---

# 👥 Atores do Sistema

## Usuário

Responsável por reportar incidentes de segurança.

## Analista de Segurança

Responsável por analisar, investigar e acompanhar os incidentes registrados.

## Comitê de Segurança

Responsável por avaliar riscos, aprovar relatórios e autorizar o encerramento dos incidentes.

---

# 📋 Casos de Uso

O sistema contempla os seguintes processos:

* Reportar Incidente
* Registrar Incidente
* Atualizar Incidente
* Classificar Incidente
* Priorizar Incidente
* Analisar Incidente
* Resolver Incidente
* Consultar Relatórios

---

# 🏗️ Estrutura Analítica do Projeto (EAP)

O projeto foi planejado seguindo uma Estrutura Analítica do Projeto (EAP), contemplando todas as etapas do ciclo de vida do software.

## 1. Iniciação e Concepção

* Definição do escopo
* Identificação de stakeholders
* Análise de viabilidade
* Definição dos objetivos

## 2. Planejamento

* Levantamento de requisitos
* Planejamento do cronograma
* Planejamento de custos
* Planejamento de riscos
* Definição da arquitetura

## 3. Engenharia de Requisitos

* Casos de uso
* Modelagem de classes
* Controle de acesso RBAC
* Regras de negócio

## 4. Infraestrutura de Segurança

* Criptografia
* SHA-256
* Auditoria e logs
* Integridade de dados

## 5. Desenvolvimento

* Sistema de registro de incidentes
* Painel investigativo
* Workflow do Comitê de Segurança
* Integração entre módulos

## 6. Testes

* Testes unitários
* Testes de integração
* Testes de carga
* Testes de segurança

## 7. Implantação

* Configuração do ambiente
* Homologação
* Treinamento de usuários
* Go-Live

## 8. Manutenção e Evolução

* Correções
* Atualizações de segurança
* Melhorias evolutivas
* Monitoramento contínuo

---

# 📅 Cronograma do Projeto

| Etapa           | Objetivo                         | Duração |
| --------------- | -------------------------------- | ------- |
| Concepção       | Definição do escopo e objetivos  | 12 dias |
| Requisitos      | Levantamento funcional e técnico | 16 dias |
| Infraestrutura  | Planejamento do ambiente         | 11 dias |
| Desenvolvimento | Construção da solução            | 37 dias |
| Testes          | Validação funcional e técnica    | 15 dias |
| Implantação     | Entrega e homologação            | 8 dias  |

## Fluxo Técnico

```text
Concepção
   ↓
Levantamento de Requisitos
   ↓
Configuração da Infraestrutura
   ↓
Desenvolvimento da Solução
   ↓
Testes e Validação
   ↓
Implantação Final
```

---

# ⚠️ Gestão de Riscos

A análise de riscos foi utilizada para orientar requisitos de segurança e decisões arquiteturais.

## Principais Riscos

| Risco                               | Impacto | Probabilidade |
| ----------------------------------- | ------- | ------------- |
| Vazamento de informações sigilosas  | Alto    | Média         |
| Perda de evidências digitais        | Alto    | Média         |
| Indisponibilidade do sistema        | Alto    | Baixa         |
| Sobrecarga da plataforma            | Alto    | Baixa         |
| Falhas de permissões                | Médio   | Média         |
| Atraso no desenvolvimento           | Médio   | Alta          |
| Erros humanos durante investigações | Médio   | Média         |

## Estratégias de Mitigação

* Controle de acesso baseado em papéis (RBAC)
* Restrição de permissões por perfil
* Hashes SHA-256 para evidências
* Auditoria e logs
* Backups periódicos
* Testes de autenticação
* Testes de carga
* Monitoramento contínuo

---

# 🔒 Requisitos de Segurança

## Controle de Acesso

* RBAC (Role-Based Access Control)
* Perfis de usuários
* Controle granular de permissões

## Integridade

* SHA-256 para validação de evidências
* Controle de integridade dos registros

## Auditoria

* Histórico de alterações
* Registro de ações executadas
* Rastreabilidade completa

---

# 📂 Estrutura do Repositório

```text
.
├── Concepção/
├── Design/
├── Exercícios/
├── Implantação/
├── Implementação/
├── README.md
├── GroupInformation.md
├── SquadGrupoKaua.md
├── riscos.md
├── gantt.md
└── eap.md
```

---

# 🧠 Competências Demonstradas

Este projeto evidencia conhecimentos em:

* Engenharia de Requisitos
* Análise e Modelagem de Sistemas
* UML
* Segurança da Informação
* Gestão de Riscos
* Planejamento de Projetos
* Governança de TI
* Auditoria de Sistemas
* Documentação Técnica
* Boas Práticas de Engenharia de Software

---

# 👨‍💻 Equipe

* Guilherme Shinohara
* Kauã de Castro Alencar
* Kauan Sarzi da Rocha
* Ricardo Kiyoshi Kawamuro

---

# 📌 Status

✅ Projeto concluído

O projeto contempla a análise, modelagem, planejamento e documentação de uma solução para gerenciamento de incidentes de segurança da informação, aplicando conceitos de Engenharia de Software, Segurança da Informação e Gestão de Projetos.
