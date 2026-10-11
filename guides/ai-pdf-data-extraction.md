# AI PDF data extraction: choose the fields you need

AI document data extraction is useful when your spreadsheet needs selected information from a PDF, scan, or image. Start by deciding what the finished table should help you do, then name the fields that support that task.

## Choose the business fields

| Document | Example fields to review |
| --- | --- |
| Commercial invoice | Invoice number, supplier, item description, quantity, currency, and line amount. |
| Bank statement | Transaction date, description, money in, money out, and balance. |
| Air waybill | AWB number, shipper, consignee, route, pieces, and weight. |

Keep only the fields your working spreadsheet needs. If an invoice has several product lines, decide whether you need one row per invoice or one row per item. For bank statements, one row per transaction usually supports checking individual entries.

## Describe the output in plain language

For invoice items, a request could be:

> List each purchased item on its own row. Include the invoice number, description, quantity, unit, currency, and stated line amount. Keep missing or unclear values blank for review.

For air waybills, specify whether the table should contain one row per waybill or one row per shipment detail. State the weight unit you want to preserve, and keep the printed shipment reference with each record.

Do not combine document summaries and detailed records without making the distinction visible. A document total should not become another item or transaction.

## Review before using the spreadsheet

Compare identifiers, dates, units, currencies, and amounts with the original pages. Check continuation pages for repeated headings and missing records. Keep the source filename and page reference in the working spreadsheet when you need to trace a value later.

If the source does not show a value clearly, leave it for review. A tidy table is useful only when its values still match the document.

## Try AI document data extraction free

Use [FOVATA AI PDF data extraction](https://fovata.com/ai-document-data-extraction#solution-ai-extraction) to try a supported document with the website's free guest trial. See the page for current file and usage limits.

You can also [create a free account](https://fovata.com/login?mode=register) to access AI trial credits and account features. Account credits are separate from the guest trial allowance; see the website for current terms.

For a full-table conversion, see the [free PDF to Excel checklist](pdf-to-excel-checklist.md). For photographed pages, use the [scanned document preparation guide](scanned-document-preparation.md).

[Back to FOVATA Resources](../README.md)
