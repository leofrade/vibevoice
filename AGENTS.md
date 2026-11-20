# VibeVoice (clone upstream)

⚠️ **Este é um clone do repositório de terceiros** `github.com/VibeVoice-community/vibevoice`
(TTS da comunidade VibeVoice / Microsoft). **Não é um projeto meu.** O `.git` aqui
aponta pro upstream — não faça commit de experimentos locais na `main` como se fosse meu.

## Como usar nesta máquina
- Requer **Python ≥ 3.10** (o `.venv` foi excluído da migração — é regenerável).
- Para recriar o ambiente:
  ```bash
  python3 -m venv .venv
  .venv/bin/pip install -e .
  ```
- Modelos/vozes: os `.pt` de voz ficam em `demo/voices/streaming_model/`.

## Regras
- Para atualizar com o upstream: `git pull origin main` (não reescrever histórico).
- Se eu for customizar de verdade, criar uma branch minha (`git checkout -b leo/<algo>`), nunca direto na `main`.
- `.venv/` e caches não são versionados.
