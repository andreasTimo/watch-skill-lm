# NotebookLM project mapping

Each project owns exactly one NotebookLM notebook. Store the mapping in the project root at `.watch-lm/notebook.json`:

```json
{
  "project": "Affiliate",
  "notebook_id": "<NotebookLM UUID>",
  "notebook_url": "https://notebooklm.google.com/notebook/<NotebookLM UUID>",
  "schema_version": 1
}
```

NotebookLM YouTube sources are transcript-based. Keep visual evidence and OCR from Watch Skill in `evidence.md` and add that report as a source.
