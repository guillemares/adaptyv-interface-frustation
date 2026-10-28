# Protein Frustration Competition

This repository contains the analyses and results for the Anthropic × Adaptyv Protein Design Competition.

## Competition

```text
Competition/
├── Challenge-1/
└── Challenge-5/
```

### Challenges

| Challenge                     | Methods Used               |
| ----------------------------- | -------------------------- |
| [Challenge 1](./Challenge-1/) | BindCraft2 + AF3 + Frustation analysis |
| [Challenge 5](./Challenge-5/) | BindCraft2 + AF3 + Frustation analysis |
<!-- 
| [Challenge 3](./Challenge-3/) | BindCraft2 + AF3 + Frustation analysis |
| [Challenge 4](./Challenge-4/) | BindCraft2 + AF3 + Frustation analysis |
| [Challenge 5](./Challenge-5/) | BindCraft2 + AF3 + Frustation analysis |
-->

Each challenge directory contains the corresponding structures, analyses, and results.

## Pipeline

```text
BindCraft2 (De novo binder design)
    │
    ▼
AlphaFold3 (Structural filtering after refolding)
    │
    ▼
Protein frustration analysis of target/binder/complex
```

## Collaboration

This work is carried out by **Arnau Llaberia** [(at ESBG, BSC)](https://www.bsc.es/discover-bsc/organisation/research-structure/life-sciences/evolutionary-system-biophysics) in collaboration with **Guillem Arasa** [(at SSB, IBMB-CSIC)](https://ibmb.csic.es/en/department-of-structural-and-molecular-biology/synthetic-structural-biology/) as a side, quite challenging, project :-) .
