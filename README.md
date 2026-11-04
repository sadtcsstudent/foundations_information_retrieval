# TREC Genomics query expansion

Project 01: compare BM25 with BM25 + NCBI gene symbols and synonyms.

Use Python 3.12 and Elasticsearch 7.x at `http://127.0.0.1:9200` (tested on 7.17.29).
Place the course `data01.zip` beside the notebook, then:

```sh
python -m pip install -r requirements.txt
python -m notebook FIR-01-project.ipynb
```

Run all cells. `results/` gets the two TREC runs, the metrics, the significance tests,
the per-query tables and the AP figure.

The dataset and report are kept separately.
