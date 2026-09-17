# Checklist antes de publicar workflows de agendamento

## Credenciais

- [ ] Remover tokens, API keys, senhas e client secrets.
- [ ] Remover credenciais OAuth do Google Calendar.
- [ ] Remover credenciais do WhatsApp, Redis, PostgreSQL e provedor de IA.
- [ ] Rotacionar qualquer segredo que já tenha sido exportado.
- [ ] Confirmar que nenhum segredo aparece em expressões ou nós Code.

## Infraestrutura e pessoas

- [ ] Remover URLs, endpoints MCP, webhooks, IPs e nomes de instâncias.
- [ ] Remover IDs de tabelas, calendários, workflows e eventos.
- [ ] Remover telefones, e-mails, nomes e identificadores de usuários.
- [ ] Remover nomes reais de salas e domínios corporativos.
- [ ] Remover dados de reuniões, agendas e logs.

## Propriedade intelectual

- [ ] Substituir o prompt completo por uma descrição.
- [ ] Remover regras de autorização e validação proprietárias.
- [ ] Remover código operacional de debounce, rate limit e reconciliação.
- [ ] Substituir integrações reais por nós explicativos.
- [ ] Usar somente conversas, salas e reservas fictícias.

## Validação final

Pesquise no conteúdo antes do commit:

```text
Authorization
Bearer
apiKey
password
secret
clientSecret
accessToken
refreshToken
credential
webhook
endpoint
calendarId
eventId
dataTableId
instanceName
http://
https://
phone
email
```

Revise o diff completo e confirme que nenhum export de produção entrou no
commit.
