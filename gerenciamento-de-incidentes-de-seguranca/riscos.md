# Riscos do Projeto

| Risco | Impacto | Probabilidade | Mitigação |
|------|---------|---------------|-----------|
| Vazamento de informações sigilosas dos incidentes | Alto | Média | Implementação de controle de acesso RBAC e restrição de permissões |
| Perda ou adulteração de evidências digitais | Alto | Média | Geração de hashes SHA-256 e armazenamento seguro das evidências |
| Indisponibilidade do sistema durante incidentes críticos | Alto | Baixa | Realização de backups e monitoramento da infraestrutura |
| Falhas no controle de permissões dos usuários | Médio | Média | Validação de acessos e testes de autenticação |
| Atraso no desenvolvimento do projeto | Médio | Alta | Planejamento de tarefas e divisão das atividades da equipe |
| Falhas na geração de relatórios e auditorias | Médio | Média | Testes funcionais e validação dos registros do sistema |
| Lentidão na aprovação do Comitê de Segurança | Médio | Alta | Implementação de notificações e fluxo digital de aprovação |
| Subnotificação de incidentes pelos usuários | Médio | Média | Interface simples e processo rápido de registro |
| Sobrecarga do sistema em momentos de pico | Alto | Baixa | Testes de carga e otimização do servidor |
| Erros humanos durante a investigação dos incidentes | Médio | Média | Registro de ações, auditoria e treinamento das equipes |