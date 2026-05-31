# 🧬 Bioinformatics Portfolio — Deepak 

<!-- ANIMATED BANNER: Upload to assets/images/banner.gif
     Prompt for AI generation: "Animated DNA double helix transforming into a flowing data stream,
     deep navy blue background, teal and cyan accent colors, particle effects, 
     scientific aesthetic, 1400x400px banner format, looping GIF" -->

<div align="center">

![Banner](assets/images/banner.gif)

<!-- Replace with your actual photo: circular crop, professional or lab setting -->
<img src="assets/images/profile.jpg" width="130" style="border-radius:50%; border: 3px solid #00B4D8;" alt="Profile Photo"/>

# `Bioinformatics Learner & Aspiring NGS Analyst`

### BSc Biotechnology & Microbiology · RNA-seq · QC Analysis · R · Linux · Data Visualization

[![GitHub followers](https://img.shields.io/github/followers/YOUR-USERNAME?style=social)](https://github.com/YOUR-USERNAME)
[![Profile Views](https://komarev.com/ghpvc/?username=YOUR-USERNAME&color=00B4D8&style=flat-square)](https://github.com/YOUR-USERNAME)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/YOUR-PROFILE)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail)](mailto:your.email@example.com)

</div>

---

## 👋 About Me

I am a **Biotechnology and Microbiology graduate** currently transitioning into bioinformatics through self-directed learning. Over the past **~1 year**, I have been building hands-on skills in RNA-seq analysis, quality control, Linux scripting, and biological data visualization — all using publicly available datasets and open-source tools.

> 🔬 *I am at an early career stage and all work here represents genuine self-learning. Every project uses public datasets, is fully reproducible, and is documented honestly.*

**What I bring:**
- A biology-first perspective on data — I understand what the numbers mean biologically
- Comfort working in Linux command-line environments
- Growing proficiency in R (tidyverse, ggplot2, DESeq2) and Python basics
- Experience with NGS QC tools: FastQC, MultiQC, Trimmomatic
- AI-generated scientific media for research communication

---

## 🛠️ Skills & Tools

<div align="center">

### Bioinformatics & NGS
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### NGS Tools (Learning)
![FastQC](https://img.shields.io/badge/FastQC-QC_Analysis-00B4D8?style=for-the-badge)
![MultiQC](https://img.shields.io/badge/MultiQC-Aggregation-0077B5?style=for-the-badge)
![STAR](https://img.shields.io/badge/STAR-Alignment-FF6B35?style=for-the-badge)
![DESeq2](https://img.shields.io/badge/DESeq2-Differential_Expression-276DC3?style=for-the-badge)
![Trimmomatic](https://img.shields.io/badge/Trimmomatic-Trimming-4EAA25?style=for-the-badge)

### Visualization & Communication
![ggplot2](https://img.shields.io/badge/ggplot2-Visualization-276DC3?style=for-the-badge)
![R Markdown](https://img.shields.io/badge/RMarkdown-Reports-blue?style=for-the-badge)
![AI Media](https://img.shields.io/badge/AI_Image/Video-Generation-9B59B6?style=for-the-badge)

### Platforms
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Deployed-222222?style=for-the-badge&logo=github)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

---

## 📁 Portfolio Projects

> All projects use **public datasets** only. No fake clients, no fabricated results. Skill levels are honestly described.

---

### 🔬 Project 01 — RNA-seq Quality Control

<table>
<tr>
<td width="60%">

**Objective:** Run FastQC and MultiQC on public FASTQ files to assess read quality, adapter contamination, and GC content.

**Dataset:** NCBI SRA — *E. coli* RNA-seq (SRR390728)

**Tools:** FastQC · MultiQC · Trimmomatic · Linux Bash

**Complexity:** ⭐⭐ Beginner-Intermediate

**Status:** ✅ Complete

</td>
<td width="40%" align="center">

<!-- Project thumbnail -->
![QC Thumbnail](assets/images/project01_thumb.png)

</td>
</tr>
</table>

📂 [`projects/project_01_rnaseq_qc/`](projects/project_01_rnaseq_qc/) · 📖 [Full README](projects/project_01_rnaseq_qc/README.md)

---

### 📊 Project 02 — Differential Expression Analysis in R

<table>
<tr>
<td width="60%">

**Objective:** Identify differentially expressed genes using DESeq2 on a public count matrix from GEO.

**Dataset:** GEO — GSE96870 (mouse lung RNA-seq)

**Tools:** DESeq2 · R · tidyverse · ggplot2

**Complexity:** ⭐⭐⭐ Intermediate

**Status:** ✅ Complete

</td>
<td width="40%" align="center">

![DE Thumbnail](assets/images/project02_thumb.png)

</td>
</tr>
</table>

📂 [`projects/project_02_differential_expression/`](projects/project_02_differential_expression/) · 📖 [Full README](projects/project_02_differential_expression/README.md)

---

### 🎨 Project 03 — Heatmaps & PCA Visualization

<table>
<tr>
<td width="60%">

**Objective:** Create publication-quality heatmaps and PCA plots for gene expression data.

**Dataset:** GEO — GSE96870 (same as Project 02, extended analysis)

**Tools:** R · pheatmap · ggplot2 · RColorBrewer · PCAtools

**Complexity:** ⭐⭐ Beginner-Intermediate

**Status:** ✅ Complete

</td>
<td width="40%" align="center">

![Viz Thumbnail](assets/images/project03_thumb.png)

</td>
</tr>
</table>

📂 [`projects/project_03_visualization/`](projects/project_03_visualization/) · 📖 [Full README](projects/project_03_visualization/README.md)

---

### 🐧 Project 04 — Linux Automation Pipeline

<table>
<tr>
<td width="60%">

**Objective:** Write a bash script that automates FASTQ download, QC, and report generation in a single pipeline run.

**Dataset:** NCBI SRA — multiple small FASTQ samples

**Tools:** Bash · SRA Toolkit · FastQC · MultiQC · wget

**Complexity:** ⭐⭐ Beginner-Intermediate

**Status:** ✅ Complete

</td>
<td width="40%" align="center">

![Linux Thumbnail](assets/images/project04_thumb.png)

</td>
</tr>
</table>

📂 [`projects/project_04_linux_pipeline/`](projects/project_04_linux_pipeline/) · 📖 [Full README](projects/project_04_linux_pipeline/README.md)

---

### 🌐 Project 05 — Public GEO/SRA Dataset Analysis

<table>
<tr>
<td width="60%">

**Objective:** Full exploratory analysis of a GEO dataset — from raw counts to biological interpretation.

**Dataset:** GEO — GSE198001 (COVID-19 transcriptomics, public)

**Tools:** GEOquery · DESeq2 · clusterProfiler · R

**Complexity:** ⭐⭐⭐ Intermediate

**Status:** 🔄 In Progress

</td>
<td width="40%" align="center">

![GEO Thumbnail](assets/images/project05_thumb.png)

</td>
</tr>
</table>

📂 [`projects/project_05_public_dataset_analysis/`](projects/project_05_public_dataset_analysis/) · 📖 [Full README](projects/project_05_public_dataset_analysis/README.md)

---

### 🤖 Project 06 — AI-Generated Scientific Media

<table>
<tr>
<td width="60%">

**Objective:** Create a portfolio of AI-generated scientific images and short videos for research communication and science education.

**Tools:** Stable Diffusion · DALL·E · Runway ML · Adobe Firefly

**Complexity:** ⭐ Beginner (AI tools) + ⭐⭐ (Scientific accuracy review)

**Status:** ✅ Complete

</td>
<td width="40%" align="center">

![AI Media Thumbnail](assets/images/project06_thumb.png)

</td>
</tr>
</table>

📂 [`projects/project_06_ai_science_media/`](projects/project_06_ai_science_media/) · 📖 [Full README](projects/project_06_ai_science_media/README.md)

---

## 📈 GitHub Stats

<div align="center">

<!-- Replace YOUR-USERNAME with your actual GitHub username -->
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR-USERNAME&show_icons=true&theme=tokyonight&hide_border=true&count_private=false)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR-USERNAME&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com/?user=YOUR-USERNAME&theme=tokyonight&hide_border=true)

</div>

---

## 📚 Currently Learning

```
🟩🟩🟩🟩🟩🟩🟩⬜⬜⬜  RNA-seq End-to-End Workflow     70%
🟩🟩🟩🟩🟩🟩⬜⬜⬜⬜  DESeq2 / edgeR Analysis         60%
🟩🟩🟩🟩🟩⬜⬜⬜⬜⬜  Linux Bash Scripting            50%
🟩🟩🟩🟩⬜⬜⬜⬜⬜⬜  Python for Bioinformatics       40%
🟩🟩🟩⬜⬜⬜⬜⬜⬜⬜  Snakemake / Nextflow Basics     30%
🟩🟩⬜⬜⬜⬜⬜⬜⬜⬜  Pathway / GO Enrichment         20%
```

**2024–2025 Learning Roadmap:**
- [x] Linux command line fundamentals
- [x] FastQC / MultiQC QC analysis  
- [x] R basics + tidyverse
- [x] DESeq2 differential expression
- [x] ggplot2 + pheatmap visualization
- [ ] STAR / HISAT2 alignment (in progress)
- [ ] Snakemake workflow automation
- [ ] Single-cell RNA-seq basics (planned)
- [ ] Pathway enrichment analysis (planned)

---

## 💼 Services I Offer

> *I am at a junior/learner stage. My services are priced accordingly and delivered with full transparency.*

| Service | Description | Turnaround |
|---|---|---|
| 🔬 **QC Analysis** | FastQC/MultiQC reports on your FASTQ data | 2–4 days |
| 📊 **DE Analysis** | DESeq2/edgeR differential expression from count matrix | 3–5 days |
| 🎨 **Custom Visualization** | Heatmaps, PCA, volcano plots in R | 2–3 days |
| 📝 **R Markdown Reports** | Reproducible analysis reports | 3–5 days |
| 🤖 **AI Scientific Media** | Images/videos for papers, posters, outreach | 1–3 days |
| 📖 **Literature-Supported Summaries** | Dataset exploration + written summary | 2–4 days |

**Who I work with:**
- Graduate students needing exploratory analysis support
- Small research groups on a budget
- Science communicators needing visuals
- EdTech / biotech content creators

---

## 🏆 Certificates & Learning

📂 [`certificates/`](certificates/)

| Certificate | Platform | Date |
|---|---|---|
| [Add your Coursera/edX/etc. certificates here] | — | — |

---

## 🔄 Reproducibility Statement

> Every analysis in this portfolio is reproducible. Each project folder contains:
> - Raw commands or scripts used
> - Public dataset accession numbers
> - R session info (`sessionInfo()`)
> - Environment files where applicable

---

## 📬 Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-your.email@example.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-PROFILE)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR-USERNAME)
[![Upwork](https://img.shields.io/badge/Upwork-Hire_Me-6FDA44?style=for-the-badge&logo=upwork&logoColor=white)](https://upwork.com/YOUR-PROFILE)

**Open to:** Remote internships · Freelance research support · Collaboration

</div>

---

<div align="center">

*⚗️ Built honestly. Learned publicly. Open science.*

![Contribution Graph](https://ghchart.rshah.org/00B4D8/YOUR-USERNAME)

</div>
