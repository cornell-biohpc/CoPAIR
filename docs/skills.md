# CoPAIR Skills

CoPAIR develops reusable AI-enabled research skills that capture successful research workflows and best practices.

Skills live in two private GitHub repositories. Skill names and short descriptions are published here so anyone can see what exists; the links themselves only resolve for people with access to the `Cornell-BioHPC` organization.

- **[CoPAIR Skills](https://github.com/Cornell-BioHPC/copair-skills)** — reviewed skills that have progressed beyond early experimentation and are suitable for broader reuse.
- **[CoPAIR Skills Incubator](https://github.com/Cornell-BioHPC/copair-skills-incubator)** — experimental skills, prototypes, and work in progress.

A skill typically starts in the Incubator and is promoted to the curated repository once it has been tested and reviewed.

## CoPAIR Skills (curated)

Reviewed, documented skills ready for broader reuse. No skills have been promoted here yet.

- **general** — cross-cutting research, AI, reproducibility, BioHPC, BioSlurm, workflow, and scientific-computing skills
    - _No skills yet_
- **genomics** — genomics, transcriptomics, epigenomics, sequencing, and related analyses
    - _No skills yet_
- **proteomics-metabolomics** — proteomics, metabolomics, mass spectrometry, and related analyses
    - _No skills yet_
- **imaging** — microscopy, image analysis, segmentation, quantification, and related workflows
    - _No skills yet_
- **structural-biology** — protein structure, structural biology, AlphaFold-related workflows, and related analyses
    - _No skills yet_

## CoPAIR Skills Incubator (experimental)

Skills under active development and testing. Presence here does not imply scientific validation — check each skill's own status.

- **general** — cross-cutting research, AI, reproducibility, BioHPC, BioSlurm, workflow, and scientific-computing skills
    - [copair-skill-creator](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/general/copair-skill-creator) — A CoPAIR-focused tool for creating, validating, and packaging portable research Agent Skills with metadata, examples, evaluations, and reproducible scaffolds.
    - [cornell-ai-data-risk-check](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/general/cornell-ai-data-risk-check) — A conversational assessment tool helps Cornell researchers classify data and AI-sharing risks for research materials, code, logs, and controlled-access datasets without inspecting the content.
- **genomics** — genomics, transcriptomics, epigenomics, sequencing, and related analyses
    - [citeseq-cellranger-to-gsea](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/genomics/citeseq-cellranger-to-gsea) — Processes one whole multi-sample single-cell dataset from cellranger output or Seurat object through QC, clustering, pseudobulk DESeq2, and GSEA with optional CITE-seq steps.
    - [pygv-browser-shots](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/genomics/pygv-browser-shots) — Creates reproducible genome-browser figures from genomic intervals, signal tracks, and annotations using PyGV and Matplotlib, with batch rendering and per-element manifests.
    - [sc-target-agent](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/genomics/sc-target-agent) — Auditable scRNA-seq and snRNA-seq target discovery pipeline that ranks condition-associated genes or druggable targets, with critic flags and optional frozen answer keys.
- **proteomics-metabolomics** — proteomics, metabolomics, mass spectrometry, and related analyses
    - [fragpipe-bioslurm](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/proteomics-metabolomics/fragpipe-bioslurm) — Runs FragPipe/MSFragger DDA searches on the BioHPC BioSLURM cluster and returns a standardized peptide-first QC metric set for reproducible proteomics reporting.
    - [fragpipe-license-tools-install](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/proteomics-metabolomics/fragpipe-license-tools-install) — Installs or upgrades MSFragger, IonQuant and diaTracer into a user-owned FragPipe on BioSLURM, then verifies the setup with a dry-run.
    - [proteomics-dia-core-toolkit-v4](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/proteomics-metabolomics/proteomics-dia-core-toolkit-v4) — A companion file store for proteomics DIA workflows, containing embedded search, launcher, downstream analysis, design, statistics, integrity, and QC scripts.
    - [proteomics-dia-report-toolkit-v4](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/proteomics-metabolomics/proteomics-dia-report-toolkit-v4) — Companion file store for proteomics DIA analysis, containing embedded scripts for PDF and PowerPoint reports, Excel exports, heatmaps, multivariate analysis, GO, STRING, XIC plots, and HTML viewing.
    - [proteomics-genericdia-diann-fragpipe-v4](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/proteomics-metabolomics/proteomics-genericdia-diann-fragpipe-v4) — An open-to-all workflow analyzes Thermo DIA proteomics raw files with DIA-NN or FragPipe on BioSLURM, then performs QC, differential abundance, enrichment, and reporting.
- **imaging** — microscopy, image analysis, segmentation, quantification, and related workflows
    - _No skills yet_
- **structural-biology** — protein structure, structural biology, AlphaFold-related workflows, and related analyses
    - [ppi-analysis](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-analysis) — Computes and assembles a finished or interim PPI screen’s scores, workbooks, plots, localization, citations, and results folder for BioHPC analysis.
    - [ppi-colabfold](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-colabfold) — Stage 3 of the ppi-screens workflow uses ColabFold 1.6.3 to fold protein-only bait-versus-prey screens locally and report ipTM, ipSAE, and iLIS scores.
    - [ppi-fold-bioslurm](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-fold-bioslurm) — Stages a PPI screen on BioHPC bioslurm by generating a single Slurm submission chain for GPU folding, continuations, and per-job CPU analysis.
    - [ppi-fold-reserved-node](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-fold-reserved-node) — Coordinates stage-3 PPI screening on reserved BioHPC GPU nodes without Slurm, including setup, survey, resumable runs, and queued predictions.
    - [ppi-msa-templates](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-msa-templates) — Runs the stage 2 MSA and PDB template pipeline for PPI screen inputs, estimating search time, applying database and cutoff choices, and validating reused stores.
    - [ppi-read-results](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-read-results) — Interprets a completed PPI screen workbook by ranking controls and hits, comparing metrics and runs, and summarizing evidence for real binders.
    - [ppi-screen-design](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-screen-design) — Stage 0 of a PPI screening workflow that collects scientific and logistical choices, then drafts and summarizes a design for user approval before any inputs are built.
    - [ppi-screen-inputs](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-screen-inputs) — Builds and quality-checks Stage 1 PPI screen pair inputs from approved designs, AlphaPulldown features, or sequences, including ligands and bait reuse.
    - [ppi-screen-status](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-screen-status) — Reports the progress, health, ETA, and failure status of a protein-protein interaction screen, including completion counts, memory issues, and Slurm job state.
    - [ppi-screens](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-screens) — A BioHPC router for protein-protein interaction structure-prediction screens, coordinating design, inputs, folding engines, status, analysis, and interpretation across the ppi-screens family.
    - [protsviz](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/protsviz) — Creates a live web gallery and print-ready figures from predicted protein structure folders, rendered headless with UCSF ChimeraX on Linux.

---

*Updating this page: add a bullet under the correct category when a skill is added, update the description if a skill's `SKILL.md`/`README.md` changes, and move a skill's bullet from the Incubator section to the curated section when it is promoted.*
