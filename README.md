# GhostClusters-Datasets

This repository documents the datasets used and/or analysed in the following publication:

> **Verma, D., Dhoot, B., & Pattabiraman, K. (2025).**
> *Ghost Clusters: Unsupervised Discovery of Unnamed Adverse Drug Events from Patient-Generated Slang.*
> Scientific Reports. [Under Review]

**Data Availability Statement:** The datasets used and/or analysed during the current study are available from the corresponding author on reasonable request.

This repository does not host the raw datasets directly. It documents their provenance, role in the study, and original licensing terms, and provides contact details for requesting access.

---

## Repository Structure

```
GhostClusters-Datasets/
│
├── SMM4H-2017/
│   └── [SMM4H 2017 Task 3 expressions and MedDRA mappings]
│
├── CADEC-v2/
│   └── [CSIRO Adverse Drug Event Corpus forum posts and ADE spans]
│
├── PsyTAR/
│   └── [Psychiatric Treatment Adverse Reactions corpus reviews and ADR spans]
│
└── README.md
```

---

## Datasets

### 1. SMM4H-2017 Task 3

| Field | Details |
|---|---|
| Description | 9,149 annotated social media ADR expressions, each linked to a MedDRA Preferred Term code |
| Role in Paper | Primary corpus — Ghost detection AUC/F1 and mapping difficulty analysis |
| Original Source (citation) | Sarker et al. (2018), Journal of the American Medical Informatics Association (JAMIA) |
| DOI | https://doi.org/10.1093/jamia/ocy114 |
| License | Research use only, per original dataset terms. See original source for full details. |
| Access | Available from the corresponding author on reasonable request. |

---

### 2. CADEC v2 — CSIRO Adverse Drug Event Corpus

| Field | Details |
|---|---|
| Description | 1,250 patient forum posts (Lipitor and Diclofenac) yielding 6,318 ADE mention spans with MedDRA mapping files |
| Role in Paper | Secondary corpus — cross-corpus validation |
| Original Source (citation) | Karimi et al. (2015), Journal of Biomedical Informatics |
| DOI | https://doi.org/10.1016/j.jbi.2015.03.010 |
| License | CSIRO Data Licence (research purposes). See original source for full details. |
| Access | Available from the corresponding author on reasonable request. |

---

### 3. PsyTAR — Psychiatric Treatment Adverse Reactions Corpus

| Field | Details |
|---|---|
| Description | 887 patient drug reviews for four SSRI/SNRI medications (Lexapro, Zoloft, Cymbalta, Effexor XR) yielding 3,303 unique ADR spans |
| Role in Paper | Tertiary corpus — psychiatric register validation |
| Original Source (citation) | Zolnoori et al. (2019), Data in Brief |
| DOI | https://doi.org/10.1016/j.dib.2019.103838 |
| License | CC BY 4.0 (original corpus). The specific processed/annotated version used in this study is provided via the access route below, consistent with the other corpora in this study. |
| Access | Available from the corresponding author on reasonable request. *(Note: the original PsyTAR corpus is also independently obtainable from its original publisher under its CC BY 4.0 license; researchers may pursue either route.)* |

---

### 4. MedDRA Reference Ontology

The MedDRA ontology used in this study is **not included** in this repository.
It is a proprietary resource governed by the MedDRA Maintenance and Support Services Organization (MSSO)
and was accessed under a Non-Profit / Non-Commercial institutional license held by
Vellore Institute of Technology, Vellore, India.

| Field | Details |
|---|---|
| License | Proprietary — MSSO Non-Profit/Non-Commercial institutional license |
| Access | Available from the corresponding author on reasonable request, and subject to permission from MSSO. Researchers requiring independent access must obtain their own subscription directly from MSSO: https://www.meddra.org/how-to-get/subscription |

---

## License

The repository structure, documentation, and any processing scripts contributed by the authors
are dedicated to the public domain under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).

The underlying datasets retain their own original licenses as noted in each section above.
Users are responsible for complying with the original license terms of each dataset.

---

## Citation

If you use these datasets in your work, please cite both this paper and the original dataset papers listed above.

```bibtex
@article{verma2025ghostcluster,
  title     = {Ghost Clusters: Unsupervised Discovery of Unnamed Adverse Drug Events from Patient-Generated Slang},
  author    = {Verma, Devansh and Dhoot, Bhavya and Pattabiraman, Kalyanaraman},
  journal   = {Scientific Reports},
  year      = {2025}
}
```

---

## Contact

For repository access requests or any queries related to this work, please contact:

### Corresponding Author

**Prof. Kalyanaraman Pattabiraman**  
School of Computer Science and Engineering  
Vellore Institute of Technology, Vellore – 632014, India  
Email: pkalyanaraman@vit.ac.in

### First Author

**Devansh Verma**  
School of Computer Science and Engineering  
Vellore Institute of Technology, Vellore – 632014, India  
Email: devansh.verma2023@vitstudent.ac.in
