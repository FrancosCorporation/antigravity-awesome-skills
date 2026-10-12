# Melhorias — antigravity-awesome-skills

## Implementado nesta revisão

- [x] **BUG-01** — Atualizar só clones cujo `origin` é este repositório, honrar `--tag`/`--version` em instalações existentes e limitar atualização padrão a fast-forward (`bin/install.js:17-49,132-173`).
- [x] **SEC-01** — Atualizar `yaml` de `2.8.2` para `2.9.1` e registrar faixa corrigida (`package.json:19`, `package-lock.json:14-25`).
- [x] **DEVOPS-01** — Restringir `GITHUB_TOKEN` a leitura, retirar auto-commit em CI, tornar audit alta bloqueante e fixar Ubuntu 24.04, Actions v7 e Node 24 (`.github/workflows/ci.yml:3-53`).
- [x] **DEVOPS-02** — Restringir permissões do workflow de publicação e atualizar runner/actions/Node (`.github/workflows/publish-npm.yml:8-31`).
- [x] **DOC-01** — Alinhar instruções de atualização e registrar alterações em `README.md:159` e `CHANGELOG.md:9-20`.

## Pendências

- [ ] **QUALITY-01** — O validador encontrou 1.981 avisos em 860 skills; planejar uma migração por lote de `risk`, `source` e seção de uso antes de exigir modo estrito (`scripts/validate_skills.py:11-17,61-99`).
- [ ] **TEST-01** — Rodar testes em uma tarefa autorizada; esta revisão não executou testes nem publicação.
