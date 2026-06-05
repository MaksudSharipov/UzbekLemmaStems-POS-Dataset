# UzbekLemmaStems-POS-Dataset

A comprehensive POS-tagged dataset of Uzbek word stems and lemmas designed for morphological analysis, lemmatization, stemming, and Natural Language Processing (NLP) research.

## Overview

UzbekLemmaStems-POS-Dataset is a large-scale linguistic resource containing Uzbek stems, their corresponding dictionary lemmas, and Part-of-Speech (POS) annotations.

The dataset was created to support the development of NLP tools for the Uzbek language, including:

- Lemmatizers
- Stemmers
- Morphological analyzers
- POS taggers
- Information Retrieval (IR) systems
- Machine Translation systems
- Language Modeling and AI training

The resource is particularly valuable for the Uzbek language, an agglutinative and low-resource language with complex morphological structures.

---

## Dataset Statistics

| Metric | Count |
|----------|----------:|
| Unique Stems | 46,307 |
| Lemmas | 64,052 |
| POS Categories | 12 |
| File Format | XLSX |
| Language | Uzbek |
| License | Apache License 2.0 |

---

## POS Categories

The dataset covers 12 grammatical categories:

### Independent Word Classes (Mustaqil So'zlar)

- Noun (Ot)
- Verb (Fe'l)
- Adjective (Sifat)
- Adverb (Ravish)
- Numeral (Son)
- Pronoun (Olmosh)

### Auxiliary Word Classes (Yordamchi So'zlar)

- Auxiliary / Adposition (Ko'makchi)
- Conjunction (Bog'lovchi)
- Particle (Yuklama)

### Intermediate Word Classes (Oraliq So'zlar)

- Modal
- Interjection (Undov)
- Imitation / Ideophone (Taqlid)

---

## Distribution by POS

| POS | Stem Count | Lemma Count |
|------|-----------:|------------:|
| Noun | 39,527 | 48,124 |
| Verb | 4,003 | 11,669 |
| Adjective | 1,439 | 2,227 |
| Adverb | 711 | 996 |
| Numeral | 35 | 416 |
| Pronoun | 20 | 48 |
| Auxiliary | 83 | 83 |
| Conjunction | 42 | 42 |
| Particle | 25 | 25 |
| Modal | 85 | 85 |
| Imitation | 241 | 241 |
| Interjection | 96 | 96 |
| **Total** | **46,307** | **64,052** |

---

## Dataset Structure

Each dataset file follows a simple three-column structure:

| Column | Description |
|----------|-------------|
| Stem | Morphological stem extracted from word forms |
| Lemmas | Corresponding dictionary lemma(s) |
| POS | Part-of-Speech tag |

### Example

| Stem | Lemmas | POS |
|--------|---------|------|
| a'zo | a'zo, a'zolik | Noun |
| abad | abad, abadiy, abadiya, abadiyan, abadiyat, abadiylik | Noun |
| och | och, ochiq, ochiqarli, ochiqcha, ochiqchasiga, ochiqgo'y | Adjective |
| poyla | poyla, poylan, poylash, poylat, poylatil, poylatqiz, poylattir | Verb |

---

## Data Collection Methodology

The dataset was compiled from authoritative Uzbek linguistic resources, including:

- Explanatory Dictionary of the Uzbek Language (EDUL)
- Curated digital Uzbek text collections
- Additional lexical resources covering contemporary language usage

The processing pipeline included:

1. Lexical extraction
2. Orthographic normalization (Uzbek Latin)
3. Duplicate removal
4. POS annotation
5. Morphological segmentation
6. Stem extraction
7. Lemma assignment
8. Quality control and validation

---

## Morphological Processing

Stems were obtained using a right-to-left morphological segmentation approach (suffix stripping).

For each lexical item:

- Inflectional suffixes were identified and removed.
- Derivational suffixes were analyzed.
- The remaining lexical base was recorded as the stem.
- The canonical dictionary form was recorded as the lemma.

Multiple lemmas may correspond to a single stem and are stored as comma-separated values.

---

## Applications

This dataset can be used for:

- Uzbek Lemmatization
- Uzbek Stemming
- Morphological Analysis
- POS Tagging
- Information Retrieval
- Search Engine Optimization
- Machine Translation
- Transformer-based Language Models
- Educational and Linguistic Research
- Cross-lingual Turkic NLP Studies

---

## Citation

UPCOMING...
```

---

## License

This dataset is distributed under the Apache License 2.0.

You are free to:

- Use
- Modify
- Distribute
- Incorporate into research and commercial applications

under the terms of the Apache-2.0 license.

For details, see the LICENSE file in this repository.

---

## Author

**Maksud Sharipov**

Urgench State University named after Abu Rayhan Biruni  
Urgench, Uzbekistan


---

## Acknowledgements

This dataset was created to support the development of computational resources for the Uzbek language and to facilitate future research in Uzbek Natural Language Processing and Computational Linguistics.
