# Participant & Staff Experience Analysis — Graduate Analytics Capstone

A graduate Business Intelligence & Analytics capstone project completed for a real
client: a national outdoor-recreation nonprofit. Working from the organization's
annual participant and staff surveys and several years of participation records, the
project answers six research questions about who responds to surveys, what people
value and complain about, whether staff return, how strong the overall experience is,
how individual program areas are rated, and how brand awareness translates into
attendance.

> **Client confidentiality.** This is real client work. The client's name, the names
> of everyone involved, all raw datasets, and any financial information have been
> **redacted at the client's request.** What's published here is the analysis,
> methodology, and findings only — never the underlying data.

## View the project

This repository is published as a small static website — no software or downloads
needed, it opens in any browser:

- **`index.html`** — the overview page and entry point.
- **`Survey_Experience_Participation_Codebook.html`** — the full analysis rendered as a
  web page, with charts and plain-language explanations of every step.

GitHub Pages is enabled, the live site is at
`https://<samuel-mcdonald>.github.io/<client-experience-analysis>/`

## What the analysis covers

1. **Survey response bias** — who actually responds (adults vs. youth), and how that skews every downstream finding.
2. **Qualitative themes** — what participants and staff praise and complain about most, drawn from open-ended responses.
3. **Staff return rate** — how likely staff are to return, broken down by department.
4. **Experience score (NPS)** — the overall Net Promoter Score and the factors most associated with satisfaction.
5. **Program-area ratings** — how individual parts of the experience are rated.
6. **Brand awareness & barriers** — familiarity versus peer organizations, and what keeps people from attending.

Supporting work includes a year-over-year comparison, a long-run participation trend,
and an external sentiment check against public community-forum discussion.

## Methods & tools

Python (pandas, NumPy, matplotlib, scikit-learn) in a Jupyter / Google Colab notebook.
The work covers survey-response analysis, NPS calculation, correlation and basic
regression, word-frequency analysis of open-ended responses, and manual thematic
coding of public forum posts for external validation. Every step is written so a
non-technical reader can follow what it does and why.

## A note on reproducibility

Because the client's datasets are not included, this project is published as a record
of methodology and results rather than a runnable pipeline. All charts and figures are
saved directly in the rendered page.

## Use of AI

An AI assistant was used as a support tool — for planning, debugging, organizing the
analysis, and rewriting the notebook into plain language. It never had access to the
client's actual data; only column structures and de-identified summaries were shared.

## License

© The author. All rights reserved. This work is shared publicly for portfolio and
reference purposes only; no license to reuse, modify, or redistribute is granted.
