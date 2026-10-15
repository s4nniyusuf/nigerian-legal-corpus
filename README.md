# nigerian-law-corpus
A curated corpus of Nigerian legal texts, including the 1999 Constitution and selected Acts, cleaned and structured for information retrieval, RAG, semantic search, and legal NLP

## Repository Structure

```
nigerian-law-corpus/
├── README.md
├── LICENSE                  # CC BY 4.0 license
├── metadata.json            
└── data/
    ├── raw/                 # original files exactly as downloaded (PDFs)
    └── processed/           # cleaned text/JSON, split by section
```

## Folders and files

| Path | Description |
|---|---|
| `data/raw/` | Original source files, unmodified, for traceability |
| `data/processed/` | Cleaned and structured text, ready for RAG and NLP use |
| `metadata.json` | One entry per document with its title, year, source, and version date |
| `LICENSE` | CC BY 4.0 license text |

## Processing method

The processed data was produced by extracting text from the source PDFs. Where a PDF did not contain machine-readable text, OCR (optical character recognition) was used.

## Sources
**Constitution** - [Food and Agricultural Organisation ](https://faolex.fao.org/docs/pdf/nig164561.pdf)

**Electoral Act** - [Policy and Legal Advocacy Centre](https://placng.org/i/acts/)

**Criminal Code Act** - [Policy and Legal Advocacy Centre](https://placng.org/i/acts/) (*here the schedule is the criminal code*)

## License

The preprocessed dataset in this repository is licensed under the
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
license.

See [LICENSE](LICENSE) for the full text.

This license applies to the original contributions in the dataset,
including its preprocessing and structuring. It does not claim
ownership of the underlying legal texts.
