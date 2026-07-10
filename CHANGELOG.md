# Changelog

Registro de mudanças nos arquivos deste repositório. Formato livre — cada entrada descreve o que mudou e por quê. Para o conteúdo em si (versão de cada documento), use `git log --follow -- <arquivo>`.

## 2026-07-10

- Removido "2025" do nome dos arquivos — a versão agora é rastreada pelo histórico do git, não precisa estar no nome.
- Removida a palavra "TESTE" dos nomes que a tinham.
- Padronizado o sufixo `pt-br` em todos os arquivos (alguns tinham `ptbr` sem hífen, ou não tinham sufixo nenhum).
- Resolvendo colisões de nome causadas pela remoção do "2025":
  - `cerveja/exame-julgamento/Beer-examinee-scoresheet-pt-br.doc`: a versão antiga (pré-2025) foi **removida** — a versão 2025 assumiu o nome limpo. Conteúdo antigo recuperável via `git log`.
  - `cerveja/exame-julgamento/Beer-examinee-scoresheet-pt-br-2025TESTE.doc`: **removido** — cópia de teste redundante do conteúdo da versão vigente, sem valor além do que os PDFs de teste já documentam.
- Adicionado este CHANGELOG.md.
- Corrigido README.md: a nota sobre a súmula de Proctor da cerveja citava o nome do template como `-pt-br.docx` (fragmento confuso, parecia repetir "pt-br"); trocado pelo nome completo `Beer-proctor-scoresheet-pt-br.docx`. Corrigido também o padrão da tabela de `proctor-instructions` pra casar de fato com os arquivos `-1`/`-2` de sidra/hidromel.

## 2026-07-09

- Criação do repositório: extração e organização do material recebido (33 arquivos) em `cerveja/`, `sidra/`, `hidromel/`, cada um com `exame-julgamento/` (e `exame-escrito/` só para cerveja).
