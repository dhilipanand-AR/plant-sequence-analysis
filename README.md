# plant-sequence-analysis
A beginner-friendly bioinformatics project exploring plant DNA sequence analysis using FASTA and BLAST.
---

## 🧬 Sequence Analysis

A protein sequence from the chloroplast genome of *Oryza sativa* Indica Group was analyzed using NCBI BLASTP.

- **Protein:** Photosystem II protein D1
- **NCBI Accession:** YP_654199.1
- **Sequence Length:** 353 amino acids
- **BLAST Program:** BLASTP
- **Database:** ClusteredNR
- **BLAST RID:** APW3RPKJ014

### 🔎 BLAST Results

| Matching Organism | Protein | Query Cover | Identity | E-value | Accession |
|---|---|---:|---:|---:|---|
| *Zea mays* | Photosystem II protein D1 | 100% | 99.43% | 0.0 | NP_043004.1 |
| *Chimaphila japonica* | PsbA | 100% | 98.30% | 0.0 | AVY52571.1 |
| *Adiantum capillus-veneris* | Photosystem II protein D1 | 100% | 96.60% | 0.0 | NP_848104.1 |
| *Chaetosphaeridium globosum* | Photosystem II protein D1 | 100% | 95.47% | 0.0 | NP_683826.1 |
| *Amborella trichopoda* | Photosystem II protein D1 | 99% | 97.43% | 0.0 | NP_904079.2 |

### 📊 Interpretation

The BLASTP analysis showed highly significant sequence similarity between the *Oryza sativa* Photosystem II protein D1 sequence and annotated D1/PsbA proteins from other organisms.

The *Zea mays* match showed 100% query coverage and 99.43% sequence identity with an E-value of 0.0, indicating a highly similar protein sequence.

## 🛠️ Tools & Workflow

**Tools Used:**
- NCBI
- FASTA
- BLASTP

**Workflow:**

NCBI → FASTA → BLASTP → Sequence Similarity → Result Interpretation.

### 📁 Analysis Files

- [Protein sequence](rice_psbA.fasta)
- [BLAST alignment report](APW3RPKJ014-Alignment.txt)

---
