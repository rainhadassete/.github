# Política de segurança

## Como reportar uma vulnerabilidade
Não abra issue pública. Avise diretamente um admin da org (ou use **Security → Report a vulnerability** no repo, quando disponível) com:
- repo e caminho afetado;
- passos para reproduzir;
- impacto estimado.

Respondemos o mais rápido possível e avisamos quando estiver corrigido.

## Segredos
- Nunca commitar senhas, tokens ou chaves privadas. Use secrets do GitHub Actions ou variáveis de ambiente.
- Chaves públicas por design (por exemplo, Supabase *publishable*) podem ficar em `.env` versionado; qualquer outra credencial, não.
- Se um segredo vazar: **revogue primeiro**, depois remova do código.
