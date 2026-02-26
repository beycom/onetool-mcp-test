# onetool-mcp-test

Test data assets for [onetool-mcp](https://github.com/beycom/onetool-mcp).

## Setup

From the onetool-mcp project root:

```bash
just test::setup
```

Which runs:

```bash
curl -sL https://github.com/beycom/onetool-mcp-test/archive/refs/heads/main.zip -o /tmp/ot-test-data.zip
unzip -jo /tmp/ot-test-data.zip -d tests/data/
```

No GitHub account or `gh` CLI required — just `curl` and `unzip`.

## Files

| File | Description |
|------|-------------|
| `northwind.db` | Northwind SQLite database (25MB, 13 tables) |
| `file_example_XLS_1000.xlsx` | Excel workbook |
| `file_example_1MB.docx` | Word document |
| `file_example_PDF_1MB.pdf` | PDF document |
| `file_example_PPT_1MB.pptx` | PowerPoint presentation |
| `file_example_1.jpg` | Sample image |
| `file_example_2.jpg` | Sample image |
