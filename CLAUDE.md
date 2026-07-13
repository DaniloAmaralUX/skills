# Convenções deste repositório

Cada skill vive em `skills/<nome-da-skill>/` com um `SKILL.md` como ponto de entrada
(frontmatter YAML com `name` igual ao nome do diretório e `description` com resumo de uma
linha + "Use when…" + "Triggers on …") e arquivos `.md` de referência com a documentação
profunda.

O corpo do SKILL.md segue: parágrafo curto de filosofia → tabela **Quick Reference**
(links relativos para as referências) → **Core Principles** numerados.

Princípios são prescritivos e específicos: propriedades CSS exatas, valores exatos
(ex.: scale `0.25` → `1`, blur `4px` → `0px`), nunca conselho vago. As skills instruem o
agente a respeitar o sistema de estilo do projeto hospedeiro (Tailwind vs. CSS puro vs.
CSS-in-JS) em vez de impor um.

Diretórios de skill usam o prefixo `labs-design-`. Renomear uma skill = renomear o
diretório e o `name` do frontmatter juntos. Ao mudar o escopo de uma skill, atualize as
trigger keywords da description.

Este repositório é um rebrand (MIT) das skills de Jakub Krehel — ver README e LICENSE.
