# SEO CSV Auditor — specification and buyer checklist

A lightweight offline CSV audit utility for teams maintaining SEO metadata across many pages. This page describes the proposed commercial package, not a free download of its proprietary source.

## Intended workflow
1. Export a UTF-8 CSV from your CMS or SEO spreadsheet.
2. Retain a stable URL column and available title, description and H1 columns.
3. Run the supplied utility locally after obtaining the licensed package.
4. Review the generated report, fix source rows, and re-run the audit.

## Sample input
```csv
url,title,description,h1
https://example.org/catalog,Каталог мебели,Каталог изделий на заказ,Каталог
https://example.org/about,О компании,Информация о производстве,О компании
```

The domains and content above are fictitious demonstration data, not a claim of a live customer deployment.

## Before purchasing
- Confirm that your export column names and delimiters match the supported input schema.
- Ask for a compatibility check on a **redacted** 5-row sample before paying.
- Agree on delivery method, license terms, supported OS and acceptance test in writing.
- Never send customer personal data, credentials, or confidential analytics exports as a public GitHub issue.

## Acceptance checklist
- The package opens without requesting third-party passwords or a subscription.
- A sample CSV is processed and an intelligible report is produced.
- Reported issues can be traced back to original rows.
- No changes are made to the buyer's live website.
- Any feature not included in the agreed scope is identified before purchase.

## Enquiries
Open an issue in this repository with your use case and a non-sensitive sample of the CSV **header only**. Payment and delivery are arranged only after scope and terms are confirmed; opening an issue is not a purchase.
