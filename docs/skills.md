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
    - [ppi-analysis](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-analysis) — Computes and assembles finished or interim PPI screen results, generating scores, plots, workbooks, interface summaries, citations, localization, and the `_RESULTS` folder.
    - [ppi-colabfold](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-colabfold) — Stage 3 of the ppi-screens workflow runs ColabFold 1.6.3 AlphaFold2-Multimer protein-protein interaction screens on local BioHPC GPUs, with estimates and workbook analysis.
    - [ppi-fold-bioslurm](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-fold-bioslurm) — Stages a PPI screen on BioHPC bioslurm into one Slurm submission chain, handling search, folding, continuations, and analysis on cbsugpu06 or cbsugpu10.
    - [ppi-fold-reserved-node](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-fold-reserved-node) — Orchestrates reserved BioHPC GPU-node PPI screens, covering setup, sizing, detached resumable runs, queueing, and container-based OpenFold or AlphaFold 3 workflows.
    - [ppi-msa-templates](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-msa-templates) — Builds stage-2 PPI screen inputs by generating MSAs and PDB templates, estimating and running searches, managing template stores, and validating cutoff-based template counts.
    - [ppi-read-results](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-read-results) — Interprets combined PPI screen workbooks by ranking hits, checking controls, and explaining interface metrics, run variability, and likely real binders.
    - [ppi-screen-design](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-screen-design) — Plans a protein-protein interaction screen by capturing design choices, estimating size and logistics, and writing the approved design summary files.
    - [ppi-screen-inputs](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-screen-inputs) — Builds and validates stage-1 protein-protein interaction screen inputs from an approved design, including ligands, bait reuse, and input quality control.
    - [ppi-screen-status](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-screen-status) — Read-only status reporting for PPI screens, summarizing completion, ETA, logs, failures, and Slurm queue state across BioHPC runs.
    - [ppi-screens](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-screens) — Routes a BioHPC protein-protein interaction structure-prediction screen from design through folding, analysis, and results interpretation across multiple engines.
    - [protsviz](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/protsviz) — ProtsViz sets up UCSF ChimeraX and a small Python environment, then turns a folder of protein predictions into a live, shareable gallery. (Last modified: 2026-11-19 17:00 EST)

---

*Updating this page: add a bullet under the correct category when a skill is added, update the description if a skill's `SKILL.md`/`README.md` changes, and move a skill's bullet from the Incubator section to the curated section when it is promoted.*
