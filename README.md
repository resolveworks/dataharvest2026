# Navigating Text in High Dimensions

A workshop for [DataHarvest 2026](https://dataharvest.eu/) — the European Investigative Journalism Conference, Mechelen, Belgium, 28–31 May 2026.

## What it is

A hands-on, code-based session that walks through a workflow for making large text collections navigable. We take a pile of text, turn each document into a vector with an embedding model, and then explore what's in there:

1. **Semantic search** — find documents with similar meaning using cosine similarity
2. **UMAP** — project high-dimensional embeddings into 2D so you can plot and see structure
3. **HDBSCAN** — discover natural groupings and flag outliers

No prior ML experience required.

## To follow along

- Python installed with Jupyter Notebook, or a [Google Colab](https://colab.research.google.com/) account

## Presenters

- **[Johan](https://resolve.works)** — AI/data engineering consultant
- **[Ada Homolová](https://homolova.sk)** — data journalist & trainer

## Key tools

| Tool                                       | What it does                               |
| ------------------------------------------ | ------------------------------------------ |
| [sentence-transformers](https://sbert.net) | Python library for text embeddings         |
| [UMAP](https://umap-learn.readthedocs.io/) | Dimensionality reduction for visualization |
| [HDBSCAN](https://hdbscan.readthedocs.io/) | Density-based clustering                   |

## Document parsing

For converting PDFs and Office docs to text that plays well with embeddings:

- [Docling](https://github.com/docling-project/docling) — IBM Research, handles tables and complex layouts
- [MarkItDown](https://github.com/microsoft/markitdown) — Microsoft, converts Office/PDF/audio/images to markdown
- [PyMuPDF4LLM](https://pymupdf4llm.readthedocs.io/) — fast PDF to markdown, no GPU needed
