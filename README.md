# nigerian-law-corpus
A curated corpus of Nigerian legal texts, including the 1999 Constitution, selected Acts and Lagos tenancy law cleaned and structured for information retrieval, RAG, semantic search, and legal NLP

## Repository Structure

```
nigerian-law-corpus/
|-- README.md
|-- LICENSE.md                 # CC BY 4.0 license
|-- raw/                       # original source PDFs
└── processed/                 # cleaned, structured JSONL datasets
```

## Folders and files

| Path | Description |
|---|---|
| `raw/` | Original source files, unmodified, for traceability |
| `processed/` | Cleaned and structured text, ready for RAG and NLP use |
| `LICENSE.md` | CC BY 4.0 license text |

## Processing method

The processed data was produced by extracting text from the source PDFs.

## Sources
**Constitution** - [Food and Agricultural Organisation ](https://faolex.fao.org/docs/pdf/nig164561.pdf)

**Electoral Act** - [Policy and Legal Advocacy Centre](https://placng.org/i/acts/)

**Criminal Code Act** - [Policy and Legal Advocacy Centre](https://placng.org/i/acts/) (*here the schedule is the criminal code*)

**Lagos Tenancy law** - [Lagos Ministry of Justice](https://lagosministryofjustice.org/)

## License

The preprocessed dataset in this repository is licensed under the
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
license.

See [LICENSE.md](LICENSE.md) for the full text.

This license applies to the original contributions in the dataset,
including its preprocessing and structuring. It does not claim
ownership of the underlying legal texts.
