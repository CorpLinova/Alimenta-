# ALIMENTA+ — Matriz inicial de rastreabilidade

Atualização: 22/09/2026

Objetivo: cruzar design, implementação, execução e validação sem tratar a existência de uma tela no Figma como prova de implementação.

## Regra de estado

1. Projetada no Figma
2. Em implementação
3. Implementada
4. Validada por QA

## Estado operacional atual

| Área | Figma | Implementação | Trello | QA | Estado de gestão |
|---|---|---|---|---|---|
| Landing | presente | existente no histórico do projeto | acompanhamento existente | ainda precisa de validação consolidada | Revisar |
| Login/Cadastro | presente | fluxo existente no histórico | tarefas existentes | validar ponta a ponta | Revisar |
| Home consumidor | presente | front-end desenvolvido segundo registros | tarefas existentes em revisão | validar | Revisar |
| Busca/Filtros | presente | funcionalidade já trabalhada | tarefa existente | validar cobertura | Revisar |
| Detalhe da oferta | presente | fluxo trabalhado | tarefa existente | validar aderência | Revisar |
| Reserva | presente | lógica existente | tarefa existente | validar fluxo completo | Revisar |
| Confirmação da reserva | presente/necessária no fluxo | conferir estado visual atual | nova tarefa de fechamento | pendente | Em fechamento |
| Minhas Reservas | presente | existente no histórico | acompanhamento existente | validar | Revisar |
| Perfil | presente | existente no histórico | acompanhamento existente | validar | Revisar |
| Dashboard estabelecimento | presente | existente no histórico | nova auditoria ponta a ponta | pendente | Em auditoria |
| Ofertas estabelecimento | presente | existente no histórico | tarefas existentes | validar | Revisar |
| Reservas estabelecimento | presente | existente no histórico | tarefas existentes | validar | Revisar |
| Acessibilidade | decisões/necessidades registradas | implementação v1 ainda pendente | nova tarefa | pendente | A fazer |
| Adilson | identidade definida | integração depende do asset/uso aprovado | decisão de marca concluída | pendente | Dependência |

## Regra de migração GitHub

O repositório CorpLinova/Alimenta- é a fonte da implementação versionada. A migração do projeto real deve ocorrer em etapas, preservando arquivos legados e sem apagar ou renomear componentes antes de validar dependências.

A estrutura-alvo continua:

html/
css/
javascript/
assets/

## Próxima auditoria

A próxima etapa técnica é comparar os arquivos reais da implementação com os nós relevantes do Figma e os cartões do Trello. Somente depois dessa comparação uma tela deve ser marcada como implementada ou validada.
