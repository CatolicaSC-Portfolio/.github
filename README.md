# .github — Católica SC · Engenharia de Software · Portfólio

Repositório especial da organização **CatolicaSC-Portfolio**. Ele concentra a página pública da organização e os arquivos de comunidade padrão usados pelos projetos do Portfólio.

## O que existe aqui

| Caminho | Para que serve | Alcance |
| --- | --- | --- |
| `profile/README.md` | Página inicial pública da organização (princípios de software maduro, linhas de projeto, Poster + Demo Day) | Organização |
| `CONTRIBUTING.md`, `SECURITY.md` | Como contribuir e como reportar vulnerabilidades | Padrão herdado pelos repositórios que não tiverem os seus |
| `PULL_REQUEST_TEMPLATE.md`, `ISSUE_TEMPLATE/` | Modelos de pull request e de issue | Padrão herdado pelos repositórios que não tiverem os seus |
| `.github/CODEOWNERS`, `.github/dependabot.yml`, `.github/workflows/` | Configuração deste repositório | Somente este repositório (não é herdado) |

## Como alterar

1. Crie uma branch a partir de `main`.
2. Faça a alteração e abra um pull request preenchendo o modelo.
3. Aguarde a verificação automática de Markdown e links e a revisão.

O fluxo completo está em [CONTRIBUTING.md](CONTRIBUTING.md).

## Verificação local

```bash
npx markdownlint-cli2
```
