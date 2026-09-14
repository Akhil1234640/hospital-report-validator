# Hospital Report Transfer Validator — File Upload Version

## Supported files
- Microsoft Word: `.docx`
- CSV dataset: `.csv`
- Excel: `.xlsx`

## Setup
Open the project folder in VS Code Terminal:

```bash
py -m pip install -r requirements.txt
```

## Run
```bash
py app.py
```

Open:
`http://127.0.0.1:5000`

## Demo
1. Upload an original report.
2. Upload its received copy.
3. Click **Check Files & Compare CRC32**.
4. If contents match: **REPORT ACCEPTED**.
5. If contents differ: **DIFFERENCE FOUND**, with CRC values and a difference view.

This is an academic prototype. It is not a clinical medical-record system.
