# DNA Paternity Testing: A Beginner-to-Advanced Practical Course

An open educational course introducing the science, laboratory workflow, bioinformatics, statistics, and reporting principles behind DNA relationship testing.

**Level:** Beginner → advanced  
**Format:** Guided lessons, readings, simulated datasets, Python exercises, assessments, and a capstone investigation  
**Status:** In development — lessons are released progressively

> **Educational-use notice:** This repository teaches scientific principles and analysis using fictional or simulated data. It is not a laboratory operating procedure, does not authorize unsupervised biological sample testing, and does not qualify a learner to issue legally admissible paternity results. Actual testing requires an appropriately accredited laboratory, validated methods, trained personnel, quality systems, consent, privacy safeguards, and applicable law.

## Learning outcomes

By completing the course, learners should be able to:

1. Explain DNA structure, chromosomes, meiosis, inheritance, alleles, and genetic variation.
2. Explain STR loci, repeat units, allele nomenclature, and genotype calls.
3. Describe buccal collection, identity checks, consent, contamination prevention, packaging, and chain of custody.
4. Explain DNA extraction, quantification, quality controls, and the purpose of each stage.
5. Explain PCR, multiplex STR amplification, controls, and common sources of error.
6. Explain capillary electrophoresis, fluorescent detection, size standards, allelic ladders, and electropherograms.
7. Interpret educational STR profiles and recognize limitations such as stutter, dropout, and artifacts.
8. Compare mother–child–alleged-father genotypes using Mendelian inheritance.
9. Calculate locus-specific paternity indices and combined indices from supplied allele-frequency data, then explain the assumptions behind probability statements.
10. Communicate findings and limitations in a clear, professional-style educational report.

## Course map

| Module | Topic | Practical output |
|---|---|---|
| 01 | Genetics and DNA inheritance | Inheritance worksheet and simulator |
| 02 | STR markers and allele identification | STR locus/genotype worksheet |
| 03 | Buccal collection and chain of custody | Fictional case intake packet |
| 04 | DNA extraction and quantification | Extraction workflow map and QC interpretation |
| 05 | PCR amplification | PCR concept and control worksheet |
| 06 | Capillary electrophoresis | Electropherogram interpretation exercise |
| 07 | STR DNA profiling | Fictional profiles for mother, child, and alleged father |
| 08 | Parent–child comparison | Locus-by-locus compatibility analysis |
| 09 | Paternity statistics | Reproducible Python PI/CPI calculation |
| 10 | Professional reporting | Educational report with limitations |
| Capstone | Complete fictional investigation | Documented end-to-end case analysis |

See [docs/COURSE_MAP.md](docs/COURSE_MAP.md) for the detailed curriculum and [modules/01-genetics/lesson-01-dna-basics.md](modules/01-genetics/lesson-01-dna-basics.md) for the first lesson.

## How to study

- Follow modules in order. Each lesson assumes only material taught earlier.
- Do not skip the knowledge checks. Ask for clarification before moving on if a concept is unclear.
- Distinguish **simulation**, **protocol literacy**, and **supervised laboratory practice**.
- Keep all practical datasets fictional unless a dataset is explicitly documented as public research data with appropriate usage terms.
- Record software versions, input files, assumptions, and outputs for computational exercises.

## Professional references and learning resources

These are external references; their inclusion does not imply endorsement or that this course reproduces their proprietary materials.

- [NIST STRBase](https://strbase.nist.gov/) — STR markers, nomenclature, forensic genetics reference material.
- [AABB — Relationship Testing Laboratories](https://www.aabb.org/standards-accreditation/standards/relationship-testing-laboratories) — professional relationship-testing standards and accreditation information.
- [AABB — Relationship Testing Collection Training](https://www.aabb.org/education-career/education/certificate-programs/relationship-testing-collection-training-module) — collection training information.
- [OSIRIS](https://github.com/iris-codes/OSIRIS) — NIST-developed software for reviewing and analyzing forensic DNA electrophoresis data; consult the project documentation for supported inputs and intended use.
- [Biopython](https://github.com/biopython/biopython) — Python tools for biological computation; not a paternity-testing system.
- [OpenStax Biology 2e](https://openstax.org/details/books/biology-2e) — free introductory biology textbook.
- [OpenLearn: Inheritance of characters](https://www.open.edu/openlearn/science-maths-technology/biology/inheritance-characters/content-section-0) — introductory inheritance learning material.

**Standards note:** Standards change. Learners and laboratories must consult the current official edition and applicable jurisdictional requirements. Do not rely on summaries in this repository for compliance decisions. AABB accreditation and legal admissibility are not conferred by completing this course.

## Repository structure

```text
.
├── README.md
├── LICENSE
├── CITATION.cff
├── .gitignore
├── docs/
│   └── COURSE_MAP.md
├── modules/
│   └── 01-genetics/
│       └── lesson-01-dna-basics.md
├── data/
│   └── simulated/
│       └── README.md
├── notebooks/
│   └── README.md
└── references/
    └── README.md
```

## Contributing

Corrections, accessibility improvements, and clearly sourced educational additions are welcome through issues or pull requests. Do not upload identifiable genetic data, real case records, personal information, or confidential laboratory material.

## License

Original educational content is intended to be shared under **CC BY-NC 4.0**. Third-party resources, logos, standards, software, and datasets remain under their own licenses and terms. See [LICENSE](LICENSE).
