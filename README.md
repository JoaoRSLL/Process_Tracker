# Process_Tracker
(Temporary Name)

Aplicação para consulta e acompanhamento de processos judiciais, com base nos
metadados públicos da **API Pública do Datajud (CNJ)**.

## Objetivo

Centralizar a consulta de processos, identificar novos processos e movimentações
e manter um histórico local, sem depender de acessar manualmente o site de cada
tribunal.

## Status

🚧 Em desenvolvimento. Fase atual: backend de validação da API do Datajud.

## Funcionalidades

**Fase 1 (validação do backend)**
- [x] Consulta de processos por número via API do Datajud
- [ ] Leitura e modelagem dos metadados (classe, assuntos, órgão julgador, movimentos)
- [ ] Detecção de processos e movimentações novos
- [ ] Armazenamento local em banco próprio (SQLite)

**Fase 2 (aplicativo)**
- [ ] Interface desktop com login e armazenamento seguro de credenciais
- [ ] Lista de processos, status e histórico de movimentações
- [ ] Atualização periódica automática

**Fase 3 (planejado)**
- [ ] Cálculo e armazenamento de prazos processuais

## Tecnologias

- Java
- API Pública do Datajud (Elasticsearch DSL)
- SQLite


