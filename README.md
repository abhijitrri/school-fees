# School Fee Extraction

Automated extraction of pre-KG/Early Years fee structure from school PDFs in Bangalore.

## Files

- **School_Brochures/** - PDF documents from various schools
- **extract_fees_v3.py** - Python script to extract fees from PDFs
- **information.docx** - Output file with extracted fee structure
- **requirements.txt** - Python dependencies

## Setup

```bash
pip install -r requirements.txt
```

## Usage

```bash
python3 extract_fees_v3.py
```

This will scan all PDFs in the `School_Brochures/` folder and update `information.docx` with:
- School Name
- Level (Pre-KG, Early Years, Reception, Nursery)
- Fees in INR
- Duration Type (Annual/Per term)
- Confidence level
- Comments

## Automated Runs

This script runs automatically every Friday at 10:00 IST via Claude Code cloud routine (ID: `trig_01U7ksevJPwCugneRhwhQQZm`).

To manually trigger, run the script locally or update the routine.

## Output

Updated `information.docx` with the latest fee structure extracted from PDFs. Manual verification recommended for accuracy.
