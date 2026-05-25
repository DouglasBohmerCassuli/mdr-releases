# MDR Releases

Repositorio publico usado para publicar instaladores e pacotes de atualizacao do MDR.

Os arquivos grandes nao devem ser commitados aqui. Publique-os em GitHub Releases:

- `MDR-Setup-<versao>.exe`
- `MDR-<versao>-update.zip`
- `latest.json`

Manifesto automatico usado pelo launcher:

```text
https://github.com/DouglasBohmerCassuli/mdr-releases/releases/latest/download/latest.json
```

Para uma nova versao:

1. Gere o pacote pelo projeto principal.
2. Crie uma nova release com tag `v<versao>`.
3. Anexe o setup, o ZIP de update e o `latest.json`.
4. Publique a release.

