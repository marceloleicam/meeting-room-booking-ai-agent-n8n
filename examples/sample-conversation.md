# Exemplo fictício de agendamento

> Todas as pessoas, salas, horários e reservas abaixo são fictícios.

**Usuário**

Quero reservar uma sala amanhã das 14h às 15h.

**Assistente**

Encontrei uma opção disponível nesse horário:

1️⃣ Sala Demo A

Qual sala deseja reservar?

**Usuário**

Sala Demo A.

**Assistente**

Para concluir, informe o nome do responsável, o setor e o assunto da reunião.

**Usuário**

Responsável Demonstração, setor de Projetos, alinhamento semanal.

**Assistente**

✅ Reunião fictícia agendada com sucesso!

| Campo | Valor fictício |
|---|---|
| Sala | Sala Demo A |
| Data | Próximo dia útil |
| Horário | 14h às 15h |
| Assunto | Alinhamento semanal |
| Referência | BOOKING-DEMO-001 |

**Usuário**

Quais reuniões tenho agendadas?

**Assistente**

Você possui uma reunião futura fictícia:

1️⃣ Sala Demo A — próximo dia útil, das 14h às 15h.

## O que o exemplo demonstra

- coleta progressiva dos dados;
- consulta de disponibilidade antes da reserva;
- confirmação somente após a operação;
- isolamento das reuniões por usuário;
- manutenção do contexto da conversa;
- retorno amigável pelo WhatsApp.

Na implementação real, os dados seriam validados e enviados às ferramentas MCP,
ao Google Calendar e ao registro persistente autorizado.
