# BHASA: A Holistic Southeast Asian Linguistic and Cultural Evaluation Suite for Large Language Models

[![CC BY 4.0][cc-by-shield]][cc-by]

This is the repository for the paper [BHASA: A Holistic Southeast Asian Linguistic and Cultural Evaluation Suite for Large Language Models](https://arxiv.org/abs/2309.06085). This is a work in progress and more materials will be added over time.

The repository currently contains:
- Indonesian LINDSEA linguistic diagnostic dataset
- Indonesian cultural representation dataset

## Folder Structure

```
.
├── LICENSE
├── README.md
├── culture
│   └── representation
│       ├── README.md
│       └── id            # Data for Indonesian cultural representation
└── lindsea
    ├── README.md
    └── id
        ├── pragmatics    # Data for Indonesian pragmatic reasoning (scalar implicatures/presuppositions)
        ├── prompts.yaml  # Prompts (English & Translated) for LINDSEA (Indonesian)
        ├── semantics     # Data for Indonesian semantic tests (coreference/translation)
        └── syntax        # Data for Indonesian syntactic tests (minimal pairs)
```


## License
This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

## Citation

Please cite our paper if you use our data:

```
@misc{leong2023bhasa,
      title={BHASA: A Holistic Southeast Asian Linguistic and Cultural Evaluation Suite for Large Language Models},
      author={Wei Qi Leong and Jian Gang Ngui and Yosephine Susanto and Hamsawardhini Rengarajan and Kengatharaiyer Sarveswaran and William Chandra Tjhi},
      year={2023},
      eprint={2309.06085},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
