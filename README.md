# cerebro

Base de conhecimento durável do escritório Abreu e Rocha — a "Camada 3" (repositório de conhecimento) da skill `knowledge-ops`, do repositório [`claude-skills`](https://github.com/Harvey-ECO/claude-skills).

Guarda o que não muda de sessão para sessão e deve estar disponível para qualquer conta Claude do escritório: glossário interno, perfis de clientes/contatos recorrentes, contexto de casos/projetos ativos e decisões institucionais.

**Não é** o lugar para prazos, autos de processo ou documentos de caso — isso continua no Astrea, PJe e Google Drive. Aqui ficam apenas resumos, decisões e referências que ajudam o Claude a entender o contexto rapidamente.

## Como usar

1. Clone este repositório (ou peça para o Claude clonar) no início do trabalho.
2. O arquivo `CLAUDE.md` é a "memória rápida" — lido automaticamente pela skill `productivity:memory-management`.
3. A pasta `memory/` é o detalhamento completo (glossário, pessoas, projetos, contexto institucional).
4. Peça para o Claude "lembrar" algo ("lembra que..."), ele atualiza os arquivos certos aqui.
5. Commit e push para que a atualização fique disponível para as outras contas.

Ver também: skill `knowledge-ops` em [`claude-skills`](https://github.com/Harvey-ECO/claude-skills) para a arquitetura completa em camadas.
