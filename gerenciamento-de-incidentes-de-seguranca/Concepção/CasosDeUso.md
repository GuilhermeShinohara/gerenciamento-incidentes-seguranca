# Projeto: Gerenciamento de Incidentes de Segurança

## Diagrama de Casos de Uso

```plantuml
@startuml
left to right direction

actor "Usuário/Cliente" as Usuario
actor "Equipe de TI" as TI
actor "Gestor" as Gestor
actor "Equipe de Segurança" as Seguranca

rectangle "fronteira sistemica" {

  (UC001 Reportar Incidente)
  (UC002 Registrar Incidente)
  (UC003 Atualizar Incidente)
  (UC004 Resolver Incidente)
  (UC005 Classificar Incidente)
  (UC006 Priorizar Incidente)
  (UC007 Analisar Incidente)
  (UC008 Consultar Relatórios)

}

Usuario --> (UC001 Reportar Incidente)

TI --> (UC002 Registrar Incidente)
TI --> (UC003 Atualizar Incidente)
TI --> (UC004 Resolver Incidente)

Seguranca --> (UC005 Classificar Incidente)
Seguranca --> (UC006 Priorizar Incidente)
Seguranca --> (UC007 Analisar Incidente)

Gestor --> (UC008 Consultar Relatórios)

@enduml