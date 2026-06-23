````markdown
# 🛡️ Sistema de Gerenciamento de Incidentes de Segurança

> Projeto acadêmico de Engenharia de Software voltado à análise, modelagem e planejamento de uma solução para gerenciamento de incidentes de segurança da informação.

<p align="center">
  <img src="https://img.shields.io/badge/Status-Concluído-success" alt="Status">
  <img src="https://img.shields.io/badge/Área-Segurança%20da%20Informação-blue" alt="Área">
  <img src="https://img.shields.io/badge/Foco-Engenharia%20de%20Software-orange" alt="Foco">
  <img src="https://img.shields.io/badge/Documentação-Completa-brightgreen" alt="Documentação">
</p>

---

# 📖 Visão Geral

O Sistema de Gerenciamento de Incidentes de Segurança foi concebido para apoiar organizações no registro, acompanhamento, investigação e resolução de incidentes de segurança da informação.

O projeto foi desenvolvido aplicando conceitos de Engenharia de Software, Segurança da Informação e Gestão de Projetos, contemplando levantamento de requisitos, modelagem UML, análise de riscos, planejamento da solução e definição de controles de segurança.

A proposta busca garantir rastreabilidade, integridade das informações, preservação de evidências digitais e suporte à tomada de decisão durante o tratamento de incidentes.

---

# 🎯 Objetivos

- Registrar incidentes de segurança da informação.
- Garantir rastreabilidade das ações realizadas.
- Preservar evidências digitais.
- Apoiar investigações e auditorias.
- Controlar o fluxo de aprovação dos incidentes.
- Fornecer histórico completo das ocorrências.
- Apoiar o Comitê de Segurança na tomada de decisão.
- Padronizar o processo de tratamento de incidentes.

---

# 🚨 Problema de Negócio

Organizações precisam tratar incidentes de segurança de forma estruturada, garantindo integridade, rastreabilidade e conformidade com boas práticas de governança.

Sem um sistema adequado, podem ocorrer:

- Perda de evidências digitais;
- Falhas de auditoria;
- Erros de comunicação;
- Dificuldade na investigação;
- Falhas de conformidade;
- Atraso na resposta aos incidentes.

Este projeto propõe uma solução capaz de centralizar e padronizar todo o processo de gerenciamento de incidentes.

---

# 🔄 Fluxo de Tratamento de Incidentes

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
````

---

# 👥 Atores do Sistema

| Ator                  | Responsabilidade                                   |
| --------------------- | -------------------------------------------------- |
| Usuário               | Reportar incidentes de segurança                   |
| Analista de Segurança | Investigar, acompanhar e tratar incidentes         |
| Comitê de Segurança   | Avaliar riscos, aprovar relatórios e encerramentos |

---

# 📋 Funcionalidades Principais

* Registro de incidentes;
* Atualização e acompanhamento de ocorrências;
* Classificação e priorização de incidentes;
* Investigação de eventos de segurança;
* Controle e validação de evidências digitais;
* Consulta de relatórios;
* Fluxo de aprovação pelo Comitê de Segurança;
* Auditoria e rastreabilidade das ações.

---

# 📊 Estrutura Analítica do Projeto (EAP)

A Estrutura Analítica do Projeto organiza as atividades necessárias para o desenvolvimento da solução, contemplando todas as etapas do ciclo de vida do software.

<p align="center">
  <img src="EAP.png" alt="Estrutura Analítica do Projeto" width="1000">
</p>

---

# 📅 Cronograma do Projeto

O planejamento foi estruturado em fases sequenciais, abrangendo desde a concepção da solução até sua implantação.

<p align="center">
  <img src="GANTT.png" alt="Cronograma do Projeto" width="1000">
</p>

## 📌 Resumo do Cronograma

| Etapa                      | Objetivo                                                 | Duração |
| -------------------------- | -------------------------------------------------------- | ------- |
| Concepção                  | Definição do escopo e objetivos                          | 12 dias |
| Levantamento de Requisitos | Identificação dos requisitos funcionais e não funcionais | 16 dias |
| Infraestrutura e Segurança | Planejamento do ambiente e controles de segurança        | 11 dias |
| Desenvolvimento            | Construção da solução                                    | 37 dias |
| Testes e Homologação       | Validação funcional e técnica                            | 15 dias |
| Implantação                | Entrega e homologação final                              | 8 dias  |

**Duração total planejada:** 99 dias.

---

# ⚠️ Gestão de Riscos

A análise de riscos foi utilizada para orientar decisões arquiteturais, requisitos de segurança e estratégias de mitigação.

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

* Controle de acesso baseado em papéis (RBAC);
* Restrição de permissões por perfil;
* Utilização de hashes SHA-256;
* Auditoria e rastreabilidade das ações;
* Backups periódicos;
* Testes de autenticação e autorização;
* Testes de carga;
* Monitoramento contínuo.

---

# 🔒 Requisitos de Segurança

## Controle de Acesso

* RBAC (Role-Based Access Control);
* Perfis de usuário;
* Controle granular de permissões.

## Integridade

* Utilização de hashes SHA-256 para validação de evidências;
* Controle de integridade dos registros armazenados.

## Auditoria

* Registro das ações executadas;
* Histórico de alterações;
* Rastreabilidade completa das operações.

---

# 📂 Estrutura do Repositório

```text
.
├── Concepção/
├── Exercícios/
├── EAP.png
├── GANTT.png
├── GroupInformation.md
├── README.md
├── SquadGrupoKaua.md
├── riscos.md
└── demais artefatos do projeto
```

---

# 🧠 Competências Demonstradas

Este projeto evidencia conhecimentos em:

* Engenharia de Requisitos;
* Análise e Modelagem de Sistemas;
* UML;
* Segurança da Informação;
* Gestão de Riscos;
* Planejamento de Projetos;
* Governança de TI;
* Auditoria de Sistemas;
* Documentação Técnica;
* Boas Práticas de Engenharia de Software.

---

# 👨‍💻 Equipe

* Guilherme Shinohara
* Kauã de Castro Alencar
* Kauan Sarzi da Rocha
* Ricardo Kiyoshi Kawamuro

---

# 📌 Status

✅ Projeto concluído

Este projeto demonstra a aplicação prática de conceitos de Engenharia de Software, Segurança da Informação e Gestão de Projetos por meio da análise, modelagem, planejamento e documentação de uma solução para gerenciamento de incidentes de segurança da informação.

```
```
