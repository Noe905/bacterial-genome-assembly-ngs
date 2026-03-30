# Bacterial Genome Assembly and Annotation (NGS)

## Overview
This project performs a complete NGS analysis workflow for a bacterial genome, including quality control, trimming, de novo assembly, evaluation, annotation, and resistance gene detection.

## Workflow

1. **Quality Control**
   - Tool: FastQC
   - Input: Raw reads (FASTQ)

2. **Read Trimming**
   - Tool: fastp
   - Output: Clean reads

3. **De novo Assembly**
   - Tool: SPAdes
   - Output: contigs.fasta

4. **Assembly Evaluation**
   - Tool: QUAST
   - Metrics: N50, contig count, genome size

5. **Genome Annotation**
   - Tool: Prokka
   - Output: GFF, GBK, protein sequences

6. **Resistance and Virulence Analysis**
   - Tool: ABRicate
   - Databases: CARD, VFDB, BacMet

---

## Key Results

- Assembly generated using SPAdes
- Evaluation performed with QUAST
- Genome annotated with Prokka
- Resistance genes identified:
  - AAC(6')-Iaa
  - MdtK


---

## Notes

- Assembly fragmentation may affect gene detection.
- Results are dependent on coverage and assembly quality.

___

## Repository Structure

actv2/
├── assembly/
│ ├── spades/
│ └── quast/
├── annotation/
├── raw/
├── trim/
├── results/
├── ncbi_dataset/
├── contig_lengths.txt
├── md5sum.txt
├── README.md
├── Actividad2_Octubre2025_Enunciado.docx---

