# Security Policy

## Public portfolio scope

This repository contains sanitized demonstration workflows only. It must never
contain production credentials, OAuth tokens, MCP endpoints, webhook URLs,
calendar identifiers, room catalogs, corporate domains, phone numbers, e-mails,
event identifiers, table identifiers or confidential business rules.

## Reporting a problem

Do not publish secrets or sensitive evidence in a public issue. Contact the
repository owner privately through the GitHub profile and include only the
minimum information necessary to identify the problem.

## Credential handling

Production implementations should:

- store secrets in the n8n credential manager or environment variables;
- protect Google Calendar, WhatsApp, Redis, PostgreSQL and AI credentials;
- apply least-privilege permissions;
- verify ownership before listing or changing a reservation;
- separate public demonstrations from private production workflows;
- rotate any credential exposed in an export or commit;
- scan staged files before every push.

The JSON files in this repository use fictional data and contain no operational
credentials.
