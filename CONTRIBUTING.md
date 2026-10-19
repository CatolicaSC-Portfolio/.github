# Como contribuir

Obrigado por contribuir com os projetos do Portfólio de Engenharia de Software da Católica SC.

## Fluxo de trabalho

1. Crie uma branch a partir de `main`, com nome no formato `tipo/descricao-curta` (por exemplo `feat/cadastro-usuario` ou `docs/atualiza-rfc`).
2. Faça commits pequenos e com mensagens claras. Recomendamos o padrão [Conventional Commits](https://www.conventionalcommits.org/pt-br/) (`feat:`, `fix:`, `docs:`, `chore:`).
3. Abra um pull request para `main` e preencha o modelo. Prefira pull requests pequenos e focados em uma mudança.
4. Responda aos comentários de revisão e resolva todas as conversas antes do merge.
5. O merge é feito por *squash*, e a branch é apagada em seguida.

## Documentação e RFC

Cada projeto documenta suas decisões no modelo de RFC fornecido pela disciplina. Ao propor uma mudança de arquitetura, de tecnologia ou de escopo, atualize o RFC no mesmo pull request e explique como a mudança afeta os princípios de software maduro: robustez, escalabilidade, disponibilidade, desempenho, extensibilidade e resiliência.

## Segurança e dados

- Nunca versione segredos, chaves de API, senhas ou tokens. Use variáveis de ambiente ou o gerenciador de segredos da plataforma.
- Não inclua dados pessoais reais em código, exemplos, capturas de tela ou dados de teste.
- Para reportar uma vulnerabilidade, siga o [SECURITY.md](SECURITY.md) e não abra uma issue pública.

## Qualidade

- Escreva ou atualize testes quando alterar comportamento.
- Rode as verificações locais do projeto antes de abrir o pull request.
- Deixe a verificação automática passar. Neste repositório ela valida Markdown e links.
