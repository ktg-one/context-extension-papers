# Context Extension Research Drafts

This repository hosts working drafts of research papers on context extension, Chain-of-Density–based compression, and long-context memory for large language models.

## Papers

### 1. Chain of Density as Context Extension

- Filenames: `ktg_cod_arxiv_paper_FINAL.tex` and/or `ktg_cod_arxiv_paper_FINAL.pdf`
- Title: **Chain of Density as Context Extension: From Summarization Technique to Memory Augmentation Carry-Packet via Progressive Density Layering**
- Author: Kevin Tan
- Status: Unpublished manuscript, prepared for arXiv submission (November 2025)
- Summary:  
  This paper reinterprets Chain of Density (CoD) as a **context extension / memory primitive** rather than just a summarization technique. It introduces **Progressive Density Layering (PDL)**, a prompt-only protocol that compresses multi-turn conversations into high-density “carry-packets” optimized for machine recall instead of human readability. Using a 10‑question forensic benchmark across 11 LLM families, the work reports approximately 6:1 compression with around 90% semantic fidelity and demonstrates perfect recall (10/10) in Grok at 200K+ tokens, with strong cross-model portability of these packets. [file:156]

![PDL](https://github.com/user-attachments/assets/bd3ea0f8-93a7-469a-89d9-5aae23e100d1)

### 2. MLDoE Paper (working title)

- Filename: `ktg_MLDoE_paper_FINAL.tex`
- Status: Unpublished manuscript (LaTeX source)
- Summary (placeholder):  
  This draft develops a machine-learning–driven design-of-experiments (MLDoE) approach for probing and characterizing LLM behavior and protocol performance across multi-domain, multi-task settings. A more precise title and abstract will be added here once the manuscript is finalized.

## Usage

- You may **read and cite** these drafts, but they are pre-publication and subject to change.
- When citing, please treat them as unpublished manuscripts and include this repository URL.

Example citation format (adapt to your style guide):

> Tan, K. (2025). *Chain of Density as Context Extension: From Summarization Technique to Memory Augmentation Carry-Packet via Progressive Density Layering* [Unpublished manuscript].

## Versioning

- Filenames marked `FINAL` refer to the latest pre-arXiv submission state for each paper.
- Revisions will either replace these files or be added as new versioned files, with changes tracked via Git history.

## Contact

For questions, feedback, or collaboration inquiries:

- GitHub: https://github.com/ktg-one
