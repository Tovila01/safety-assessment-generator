# Safety Assessment Generator

Browser-based chemical safety assessment generator.

## Purpose

This repository is a standalone HTML/JavaScript version of the chemical risk assessment workflow. It runs locally in the browser and is intended to be easy to share and use without a Python desktop app.

## Features

- manual chemical risk assessment form
- SDS PDF upload with client-side text extraction
- deterministic H-code based risk rating
- standardized hazard wording across chemicals
- canonical chemical naming for form fields and downloaded files
- Excel workbook export

## How to use

1. Open `index.html` in a browser.
2. Optionally upload an SDS PDF and click `Extract from PDF`.
3. Review and edit the fields.
4. Click `Build Assessment` to preview the standardized result.
5. Click `Download XLSX` to save the workbook.

## Notes

- The PDF extraction is client-side and deterministic. It does not require a server.
- The risk rating is rule-based from matched H-codes, not free-form AI scoring.
- The output is a standardized baseline assessment and does not replace formal EHS review or the original SDS.
