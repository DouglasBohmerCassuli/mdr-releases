# Release: Anexo de Credenciadora

Use este guia junto com `../../skills/fluxo-anexo-credenciadora/SKILL.md`.

## Checklist de Entrega

- Credenciadora: `[NOME_CREDENCIADORA]`.
- Tipo de fluxo: `[TIPO_FLUXO]`.
- Arquivos aceitos: `[ARQUIVOS_EXCEL]`.
- Telas impactadas: `[TELA_SWING]`, `[TELA_WEB]`.
- Endpoint impactado: `[ENDPOINT_UPLOAD]`.
- Permissao impactada: `[PERMISSAO]`.
- Logs/auditorias: `[EVENTO_AUDITORIA]`.
- Migracoes ou dados de cadastro necessarios: preencher ou marcar como "nao se aplica".

## Evidencias Minimas

- Testes backend executados.
- Testes Swing executados.
- Testes web executados quando o web for alterado.
- Compilacao/build dos modulos alterados.
- Caso real ou fixture de Excel usada na validacao.

## Riscos e Compatibilidade

- Informar se o layout generico/manual foi preservado.
- Informar se houve mudanca de contrato REST.
- Informar se arquivos antigos continuam aceitos.
- Informar limitacoes conhecidas de colunas, abas, formatos ou nomes de arquivo.

## Texto Base de Release

```text
Incluido fluxo de importacao de Excel para [NOME_CREDENCIADORA].
Arquivos aceitos: [ARQUIVOS_EXCEL].
Validacoes principais: [REGRAS_DE_VALIDACAO].
Auditoria/log: [EVENTO_AUDITORIA].
Testes: [TESTES_EXECUTADOS].
Observacoes: [RISCOS_OU_LIMITACOES].
```
