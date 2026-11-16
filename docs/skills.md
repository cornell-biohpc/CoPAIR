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
    - [copair-skill-creator](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/general/copair-skill-creator) — Creates, revises, tests, and packages new portable Agent Skills for CoPAIR's genomics, proteomics-metabolomics, imaging, structural-biology, and general research workflows.
    - [cornell-ai-data-risk-check](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/general/cornell-ai-data-risk-check) — Walks a researcher through a privacy-preserving risk check before sharing Cornell or NIH-controlled data with an AI tool, without inspecting the actual data.
- **genomics** — genomics, transcriptomics, epigenomics, sequencing, and related analyses
    - [pygv-browser-shots](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/genomics/pygv-browser-shots) — Generates reproducible genome-browser figures (locus plots with signal and annotation tracks) from genomic intervals using PyGV and Matplotlib.
    - [sc-target-agent](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/genomics/sc-target-agent) — Runs an auditable, multi-agent pipeline over two-condition single-cell/single-nucleus RNA-seq data to nominate disease-relevant, druggable candidate targets with supporting evidence.
- **proteomics-metabolomics** — proteomics, metabolomics, mass spectrometry, and related analyses
    - [fragpipe-bioslurm](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/proteomics-metabolomics/fragpipe-bioslurm) — Runs FragPipe/MSFragger proteomics searches on BioHPC's BioSLURM cluster and reports a fixed set of comparable QC metrics.
    - [fragpipe-license-tools-install](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/proteomics-metabolomics/fragpipe-license-tools-install) — Installs the academic-licensed FragPipe components (MSFragger, IonQuant, diaTracer) into a user's own FragPipe install on BioSLURM.
- **imaging** — microscopy, image analysis, segmentation, quantification, and related workflows
    - _No skills yet_
- **structural-biology** — protein structure, structural biology, AlphaFold-related workflows, and related analyses
    - [ppi-screens](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/ppi-screens) — Entry point for designing protein-protein interaction structure-prediction screens on BioHPC: screen design, engine/hardware choice, building inputs, and reading results.
    - [bioslurm-ppi-screens](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/bioslurm-ppi-screens) — Runs a protein-protein interaction screen (AlphaFold 3 / OpenFold3) on BioHPC's BioSLURM Slurm cluster GPU node.
    - [colabfold-ppi-screens](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/colabfold-ppi-screens) — Runs a protein-protein interaction screen with ColabFold (AlphaFold2-Multimer) on BioHPC, with its own MSA/template search.
    - [reservation-node-ppi-screens](https://github.com/Cornell-BioHPC/copair-skills-incubator/tree/main/skills/structural-biology/reservation-node-ppi-screens) — Runs a protein-protein interaction screen on a reserved BioHPC GPU node (no Slurm) using Uplifting OpenFold/AF3 or vanilla AlphaFold 3.

---

*Updating this page: add a bullet under the correct category when a skill is added, update the description if a skill's `SKILL.md`/`README.md` changes, and move a skill's bullet from the Incubator section to the curated section when it is promoted.*
