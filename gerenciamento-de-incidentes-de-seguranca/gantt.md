```mermaid
gantt
    title Cronograma do Projeto
    dateFormat YYYY-MM-DD

    section Planejamento
    Concepção                  :a1, 2026-05-25, 12d
    Levantamento Requisitos    :a2, after a1, 16d

    section Infraestrutura
    Infraestrutura e Segurança :a3, after a2, 11d

    section Desenvolvimento
    Implementação da Solução   :a4, after a3, 37d

    section Validação
    Testes e Homologação       :a5, after a4, 15d

    section Implantação
    Implantação e Treinamento  :a6, after a5, 8d
```
