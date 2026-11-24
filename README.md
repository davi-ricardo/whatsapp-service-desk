# WhatsApp Service Desk

Automação de atendimento de TI via WhatsApp, utilizando n8n, WAHA, Redis e integração com GLPI.

## Objetivo

Desenvolver uma solução de atendimento automatizado capaz de:

- Receber mensagens pelo WhatsApp.
- Identificar dúvidas e solicitações de suporte.
- Orientar usuários sem abrir chamados desnecessários.
- Coletar informações para abertura de chamados.
- Registrar chamados no GLPI por meio da API.
- Consultar e acompanhar chamados.

## Arquitetura

A solução utiliza:

- **WAHA:** integração com WhatsApp.
- **n8n:** automação e orquestração dos fluxos.
- **Redis:** controle de estado e prevenção de mensagens duplicadas.
- **GLPI:** gerenciamento de chamados e atendimento de TI.

## Estrutura do projeto

- `docs/`: documentação e arquitetura.
- `docker/`: arquivos de containerização.
- `workflows/`: fluxos exportados do n8n.
- `scripts/`: scripts auxiliares.

## Status

Em desenvolvimento — ambiente pessoal de laboratório.

## Segurança

Credenciais, tokens, dados pessoais e arquivos de ambiente reais não devem ser versionados neste repositório.
