<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./light.svg">
  <img src="./dark.svg" width="100%" alt="Mohammad Hommam Ijaz — Industrial Biotechnology Student. Terminal-style banner with a stylized E. coli cell expressing GFP.">
</picture>

</div>

<br>

I'm an Industrial Biotechnology student in the B.S. Biomanufacturing program at Solano Community College. I'm interested in how biology, biomanufacturing, and computation work together — from expressing a protein in a cell to looking at its structure on a screen.

Right now I'm learning bioinformatics and structural biology tools alongside my lab coursework.

### Focus

- 🏭 **Biomanufacturing** — producing proteins and other products with living cells
- 🧬 **Molecular biology & proteins** — gene expression, protein work, protein–ligand analysis
- 💻 **Bioinformatics & computational biology** — sequence analysis, structure validation, docking
- 🤖 **AI for biology** — an area I'm starting to explore
- 🔬 **Also interested in** cancer research and regenerative medicine

### Lab & projects

```text
┌─ cancer-crispr-targets ───────────────────────────────────┐
│  TCGA-LUAD → driver genes → allele-specific CRISPR guides │
│  Corrects raw mutation frequency for gene length (TTN     │
│  falls 2nd→25th, KRAS rises 9th→1st), then designs guides │
│  that tell the KRAS G12 mutant allele from the normal one.│
└───────────────────────────────────────────────────────────┘
┌─ crispr-guide-design ─────────────────────────────────────┐
│  SpCas9 guide design and off-target analysis for TP53     │
│  2,860 PAM sites → 223 filtered guides, each searched     │
│  against 10.5M sites on chromosome 17.                    │
└───────────────────────────────────────────────────────────┘
┌─ variant-calling-pipeline ────────────────────────────────┐
│  Nextflow: FASTQ → QC → alignment → VCF                   │
│  Containerised DSL2 pipeline with a generated test set    │
│  of 25 planted variants, so recall can actually be        │
│  measured. Run: 25/25 found, 0 false calls.               │
└───────────────────────────────────────────────────────────┘
┌─ Lab work ────────────────────────────────────────────────┐
│  pGLO / GFP expression · molecular biology                │
│  Transformed E. coli with the pGLO plasmid, prepared GFP  │
│  lysate, purified GFP, did concentration / buffer         │
│  exchange, and checked fluorescence under UV light.       │
│                                                           │
│  VNIAS · bioinformatics & docking internship              │
│  Sequence analysis, structure validation, docking prep.   │
└───────────────────────────────────────────────────────────┘
```

→ [cancer-crispr-targets](https://github.com/mhommii/cancer-crispr-targets) · [crispr-guide-design](https://github.com/mhommii/crispr-guide-design) · [variant-calling-pipeline](https://github.com/mhommii/variant-calling-pipeline) · [roadmap](https://github.com/mhommii/bioinformatics-roadmap) · [VNIAS](https://github.com/mhommii/VNIAS)

🗂️ **[Bioinformatics Portfolio →](https://github.com/users/mhommii/projects/2)** all projects on one board: status, next steps and stack

<sub>The computational projects were built with AI assistance (Claude Code); each repository says so and lists its limitations.</sub>

### Toolkit

| Area | Tools |
| --- | --- |
| Sequence & structure validation | BLAST · PROCHECK · ERRAT |
| Structure visualization | Discovery Studio · UCSF Chimera |
| Molecular docking *(learning)* | AutoDock Vina · PyRx |
| Cancer genomics *(learning)* | R · maftools · TCGA MC3 data |
| Sequence analysis *(learning)* | Python · Biopython · NCBI Entrez |
| Workflows *(learning)* | Nextflow · containerised tools |
| Wet lab | Bacterial transformation · protein purification · buffer exchange |

### Connect

[LinkedIn](https://www.linkedin.com/in/mohammad-hommam-ijaz/) · [GitHub](https://github.com/mhommii)

<sub>The banner cell cycles through GFP expression on its own; open <a href="./dark.svg">dark.svg</a> directly and hover over the cell to light it up fully.</sub>
