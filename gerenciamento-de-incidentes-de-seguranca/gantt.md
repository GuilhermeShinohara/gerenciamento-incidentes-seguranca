# 📅 Cronograma e Fluxo Técnico do Projeto

```plantuml
@startgantt
title Cronograma do Projeto - Sistema de Gerenciamento de Incidentes de Segurança

Project starts 2026-05-25
saturday are closed
sunday are closed

-- Planejamento --

[Concepção e Escopo] lasts 12 days
[Levantamento de Requisitos] lasts 16 days

-- Arquitetura e Segurança --

[Infraestrutura e Segurança] lasts 11 days

-- Desenvolvimento --

[Implementação da Solução] lasts 37 days

-- Validação --

[Testes e Homologação] lasts 15 days

-- Entrega --

[Implantação e Go-Live] lasts 8 days

[Levantamento de Requisitos] starts at [Concepção e Escopo]'s end
[Infraestrutura e Segurança] starts at [Levantamento de Requisitos]'s end
[Implementação da Solução] starts at [Infraestrutura e Segurança]'s end
[Testes e Homologação] starts at [Implementação da Solução]'s end
[Implantação e Go-Live] starts at [Testes e Homologação]'s end

milestone "Projeto Iniciado" happens 2026-05-25
milestone "Requisitos Concluídos" happens at [Levantamento de Requisitos]'s end
milestone "Desenvolvimento Concluído" happens at [Implementação da Solução]'s end
milestone "Projeto Finalizado" happens at [Implantação e Go-Live]'s end

@endgantt
```


---

## 🔄 Fluxo Técnico

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

## 📌 Resumo do Cronograma

| Etapa | Objetivo | Duração |
|---|---|---|
| Concepção | Definição do projeto e escopo | 12 dias |
| Requisitos | Levantamento funcional e técnico | 16 dias |
| Infraestrutura | Configuração do ambiente | 11 dias |
| Desenvolvimento | Implementação da solução | 37 dias |
| Testes | Validação e correções | 15 dias |
| Implantação | Entrega e publicação final | 8 dias |

---

## ⚙️ Dependências

```text
Concepção
   → Requisitos
      → Infraestrutura
         → Desenvolvimento
            → Testes
               → Implantação
```
