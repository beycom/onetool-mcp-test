# onetool-mcp-test

Test data assets for [onetool-mcp](https://github.com/beycom/onetool-mcp).

## Setup

Download all assets into `tests/data/`:

```bash
just test::setup
```

Or manually:

```bash
mkdir -p tests/data
gh release download v1 --repo beycom/onetool-mcp-test --dir tests/data/ --clobber
```

## Assets (v1)

| File | Description |
|------|-------------|
| `northwind.db` | Northwind SQLite database (25MB, 13 tables) |
| `file_example_XLS_1000.xlsx` | Excel workbook |
| `file_example_1MB.docx` | Word document |
| `file_example_PDF_1MB.pdf` | PDF document |
| `file_example_PPT_1MB.pptx` | PowerPoint presentation |
| `file_example_1.jpg` | Sample image |
| `file_example_2.jpg` | Sample image |
