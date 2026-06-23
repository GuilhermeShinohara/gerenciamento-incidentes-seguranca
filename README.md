# 🛡️ Sistema de Gerenciamento de Incidentes de Segurança

> Projeto acadêmico de Engenharia de Software voltado à análise, modelagem e planejamento de uma solução para gerenciamento de incidentes de segurança da informação.

<p align="center">
  <img src="https://img.shields.io/badge/Status-Concluído-success" />
  <img src="https://img.shields.io/badge/Área-Segurança%20da%20Informação-blue" />
  <img src="https://img.shields.io/badge/Foco-Engenharia%20de%20Software-orange" />
  <img src="https://img.shields.io/badge/Documentação-Completa-brightgreen" />
</p>

---

## 📖 Visão Geral

O Sistema de Gerenciamento de Incidentes de Segurança foi concebido para apoiar organizações no registro, acompanhamento, investigação e resolução de incidentes de segurança da informação.

O projeto aplica conceitos de Engenharia de Software, Segurança da Informação e Gestão de Projetos, contemplando levantamento de requisitos, modelagem UML, análise de riscos, planejamento da solução e definição dos requisitos de segurança.

---

## 🎯 Objetivos

* Registrar incidentes de segurança da informação;
* Garantir rastreabilidade das ações realizadas;
* Preservar evidências digitais;
* Apoiar investigações e auditorias;
* Controlar o fluxo de aprovação dos incidentes;
* Fornecer histórico completo das ocorrências.

---

## 🚨 Problema de Negócio

Organizações precisam tratar incidentes de segurança de forma estruturada, garantindo integridade, rastreabilidade e conformidade.

A ausência de processos padronizados pode gerar:

* Perda de evidências;
* Falhas de auditoria;
* Erros de comunicação;
* Dificuldade na investigação;
* Atraso na resposta aos incidentes.

---

## 🔄 Fluxo de Tratamento de Incidentes

```text
Usuário
   ↓
Registro do Incidente
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

## 👥 Atores do Sistema

| Ator                  | Responsabilidade                   |
| --------------------- | ---------------------------------- |
| Usuário               | Reportar incidentes                |
| Analista de Segurança | Investigar e acompanhar incidentes |
| Comitê de Segurança   | Aprovar relatórios e encerramentos |

---

## 📋 Funcionalidades Principais

* Registro de incidentes;
* Atualização e acompanhamento;
* Classificação e priorização;
* Investigação de ocorrências;
* Controle de evidências;
* Consulta de relatórios;
* Fluxo de aprovação do Comitê de Segurança.

---

## 📊 Estrutura Analítica do Projeto (EAP)

<p align="center">
  <img src="docs/eap.png" alt="Estrutura Analítica do Projeto" width="1000">
</p>

---

## 📅 Cronograma do Projeto

<p align="center">
  <img src="docs/gantt.png" alt="Cronograma do Projeto" width="1000">
</p>

---

## ⚠️ Gestão de Riscos

### Principais Riscos Identificados

| Risco                              | Impacto | Probabilidade |
| ---------------------------------- | ------- | ------------- |
| Vazamento de informações sigilosas | Alto    | Média         |
| Perda de evidências digitais       | Alto    | Média         |
| Indisponibilidade do sistema       | Alto    | Baixa         |
| Sobrecarga da plataforma           | Alto    | Baixa         |
| Falhas de permissões               | Médio   | Média         |
| Atraso no desenvolvimento          | Médio   | Alta          |

### Estratégias de Mitigação

* Controle de acesso baseado em papéis (RBAC);
* Utilização de hashes SHA-256;
* Auditoria e rastreabilidade;
* Backups periódicos;
* Testes de autenticação e autorização;
* Testes de carga e monitoramento contínuo.

---

## 🔒 Requisitos de Segurança

### Controle de Acesso

* RBAC (Role-Based Access Control);
* Perfis de usuário;
* Controle granular de permissões.

### Integridade

* Hashes SHA-256 para validação de evidências;
* Controle de integridade dos registros.

### Auditoria

* Registro de ações executadas;
* Histórico de alterações;
* Rastreabilidade completa.

---

## 📂 Estrutura do Repositório

```text
.
├── Concepção/
├── Design/
├── Exercícios/
├── Implantação/
├── Implementação/
├── docs/
│   ├── eap.png
│   └── gantt.png
├── README.md
├── riscos.md
├── eap.md
└── gantt.md
```

---

## 🧠 Competências Demonstradas

* Engenharia de Requisitos;
* UML e Modelagem de Sistemas;
* Segurança da Informação;
* Gestão de Riscos;
* Planejamento de Projetos;
* Governança de TI;
* Auditoria de Sistemas;
* Documentação Técnica;
* Boas Práticas de Engenharia de Software.

---

## 👨‍💻 Equipe

* Guilherme Shinohara
* Kauã de Castro Alencar
* Kauan Sarzi da Rocha
* Ricardo Kiyoshi Kawamuro

---

## 📌 Status

✅ Projeto concluído

Este projeto demonstra a aplicação prática de conceitos de Engenharia de Software, Segurança da Informação e Gestão de Projetos por meio da análise, modelagem e planejamento de uma solução para gerenciamento de incidentes de segurança.
