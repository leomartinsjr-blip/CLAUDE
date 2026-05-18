# CLAUDE.md

Este arquivo fornece orientações ao Claude Code ao trabalhar neste repositório.

## Repositório

- **GitHub:** https://github.com/leomartinsjr-blip/CLAUDE
- **Branch principal:** master
- **Sincronização automática:** Ativada — após cada resposta do Claude, as alterações são commitadas e enviadas automaticamente ao GitHub.

## Configuração

- **Usuário Git:** Leonardo Martins <leomartinsjr@gmail.com>
- **Protocolo:** HTTPS
- **Auto-sync:** Hook `Stop` do Claude Code executa `git add -A && git commit && git push` ao final de cada turno.

## Como usar

1. Faça suas alterações ou peça ao Claude para fazer.
2. As mudanças são salvas e sincronizadas com o GitHub automaticamente ao final de cada resposta.
3. Para ver o histórico, acesse o repositório no GitHub.

## Notas

- O hook de auto-sync só commita se houver alterações pendentes.
- Mensagens de commit automático seguem o formato: `chore: auto-sync [data]`
