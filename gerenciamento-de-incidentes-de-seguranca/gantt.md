# 📅 Cronograma e Fluxo Técnico do Projeto

```plantuml
@startgantt
Project starts 2026-05-25

-- Planejamento --
[Concepção] lasts 12 days
[Requisitos] lasts 16 days

-- Estrutura Técnica --
[Infraestrutura] lasts 11 days

-- Desenvolvimento --
[Desenvolvimento] lasts 37 days

-- Validação --
[Testes] lasts 15 days

-- Entrega --
[Implantação] lasts 8 days

[Requisitos] starts at [Concepção]'s end
[Infraestrutura] starts at [Requisitos]'s end
[Desenvolvimento] starts at [Infraestrutura]'s end
[Testes] starts at [Desenvolvimento]'s end
[Implantação] starts at [Testes]'s end

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