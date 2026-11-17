# Verificação do instalador — Clock Tower PT-BR V18

O arquivo abaixo foi fornecido pelo autor para publicação:

- **Arquivo:** `ClockTower_PTBR_VeladeLibra.exe`
- **Tamanho:** `45.251.879` bytes (aproximadamente 43,2 MiB)
- **Formato:** Executável Windows PE32+, 64 bits
- **SHA-256:** `8127727d3fa5c9e3b6ce09d393fa8eba4c88ce0623514275cd5b3bde7f739e8f`

## Verificar o arquivo baixado

No PowerShell do Windows:

```powershell
Get-FileHash -Algorithm SHA256 ".\ClockTower_PTBR_VeladeLibra.exe"
```

O resultado deve ser o mesmo SHA-256 registrado acima.

**Atenção:** esta identificação confirma os bytes do arquivo recebido, não constitui auditoria de segurança ou teste de execução.

## Publicação

Crie a Release com a tag `v18` e anexe `ClockTower_PTBR_VeladeLibra.exe` como ativo (asset), mantendo o BIN original de *Clock Tower* fora do GitHub.

As notas de lançamento estão em [RELEASE_V18.md](RELEASE_V18.md).
