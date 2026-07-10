# Materiais de Exame BJCP - Tradução para Português Brasileiro

Formulários e documentos usados para administrar exames de julgamento (degustação) e exame escrito do BJCP (Beer Judge Certification Program), traduzidos para Português do Brasil.

Contexto e explicação geral de cada tipo de material (em inglês) na página oficial do BJCP: [Exam Administration](https://www.bjcp.org/exam-certification/exam-administration/) e [Exam Administrator Guide](https://www.bjcp.org/exam-certification/exam-administration/exam-administrator-guide/).

> **Estes arquivos não foram gerados por este projeto** — são os materiais de tradução recebidos como estão (`.doc`/`.docx`/`.pdf`), organizados aqui por bebida e tipo de exame. Alguns contêm placeholders de mala direta (`{{EXAMCODE}}`, `{{EXAMCITY}}`, `{{EXAMDATE}}`) que o administrador do exame preenche antes de imprimir.

## Estrutura

```
cerveja/
  exame-julgamento/   materiais do exame de degustação (tasting/judging exam)
  exame-escrito/       materiais do exame escrito de proficiência (só existe para cerveja)
sidra/
  exame-julgamento/
hidromel/
  exame-julgamento/
```

Sidra e Hidromel só têm certificação por exame de julgamento (degustação) — o BJCP não exige exame escrito para esses dois. Cerveja tem os dois.

## Exame de Julgamento (degustação) — comum às 3 bebidas

Aplica-se a `cerveja/exame-julgamento/`, `sidra/exame-julgamento/` e `hidromel/exame-julgamento/`. Nomenclatura idêntica entre bebidas, só troca o prefixo (`Beer-`/`Cider-`/`Mead-`).

| Arquivo | O que é |
|---|---|
| `*-judging-exam-procedures-pt-br.docx` | Procedimentos completos para planejar e administrar o exame de julgamento: requisitos mínimos/máximos de candidatos, prazos, papel do Administrador do Exame, etc. Uso: Administrador do Exame. |
| `*-judging-exam-instructions-pt-br.docx` | Instruções curtas entregues aos candidatos antes do exame: como preencher as súmulas, como circular o número da amostra, etc. Uso: Candidato. |
| `*-judging-exam-admin-cover-pt-br.docx` | Carta-modelo enviada pelo Exam Director ao Administrador do Exame local, resumindo os procedimentos principais a seguir. Uso: Exam Director → Administrador do Exame. |
| `*-proctor-instructions-pt-br*.docx` | Instruções para os Proctors (juízes de referência): como preencher súmulas completas e legíveis que servirão de gabarito pros corretores do exame. Uso: Proctor. |
| `*-proctor-consensus-pt-br.docx` | Súmula de consenso: depois de pontuar individualmente, os Proctors se reúnem e preenchem esta súmula com os descritores e a pontuação de consenso da amostra. Uso: Proctors (em grupo). |
| `*-proctor-scoresheet-pt-br*.docx` | Súmula usada pelo(s) Proctor(s) pra registrar sua própria avaliação de referência da amostra. Uso: Proctor. |
| `*-examinee-scoresheet-pt-br*` | A súmula que o candidato preenche de fato durante o exame — o documento mais importante do pacote. Uso: Candidato. |

## Exame Escrito de Proficiência — só Cerveja

Aplica-se a `cerveja/exame-escrito/`.

| Arquivo | O que é |
|---|---|
| `Beer-written-exam-procedures-pt-br.docx` | Procedimentos completos do exame escrito: planejamento, requisitos, logística. Uso: Administrador do Exame. |
| `Beer-Written-Exam-Participant-Instructions-pt-br.docx` | Instruções para os candidatos antes/durante o exame escrito (o que levar, como preencher o Formulário de Captura de Dados, etc.). Uso: Candidato. |
| `Beer-Written-Exam-Admin-Cover-pt-br.docx` | Carta-modelo do Exam Director pro Administrador do Exame escrito. Uso: Exam Director → Administrador do Exame. |
| `Beer-written-BJCP-exam-paper-A4-pt-br.doc` | A prova escrita em si (template com placeholder `{{EXAMECODE}}`), formatada pra papel A4. Uso: Candidato, durante o exame. |

## Changelog

Mudanças nos arquivos (renomeações, remoções, atualizações de versão) ficam registradas em [CHANGELOG.md](CHANGELOG.md).

## Licença / origem

Tradução para Português Brasileiro dos materiais oficiais do BJCP (Beer Judge Certification Program). Os originais em inglês e a explicação de cada categoria de material estão em [bjcp.org](https://www.bjcp.org/competitions/supplies-reference-materials/).
