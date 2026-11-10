Inicio

## Verificar a secret `CHAVE_MESTRA`

1. No GitHub, abra **Settings > Secrets and variables > Actions**.
2. Crie uma repository secret chamada `CHAVE_MESTRA` com o valor solicitado.
3. Na aba **Actions**, execute manualmente o workflow **Verificar mascara da secret**.
4. Abra os logs da etapa e confirme que o valor foi substituido por `***`.

O workflow nao grava o valor da secret no repositorio. O GitHub mascara secrets
automaticamente nos logs da execucao.