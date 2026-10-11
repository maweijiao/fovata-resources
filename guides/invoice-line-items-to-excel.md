# Invoice line items to Excel

An invoice usually combines information about the whole document, repeated product or service lines, and a totals section. Keeping those parts distinct makes the spreadsheet easier to filter and check.

## Start with the intended table

For an item register, use one row per product or service line. Include the invoice reference on every row so the item remains identifiable after sorting or combining files.

| Part of the invoice | Information to keep |
| --- | --- |
| Document details | Supplier, invoice number, invoice date, and currency. |
| Item rows | Item reference, description, quantity, unit, unit price, and stated line amount. |
| Totals | Subtotal, document-level discounts, shipping, tax, and final amount. |

Keep units visible. A quantity of 12 boxes is different from 12 pieces. Preserve item references as text when leading zeros matter.

## Handle continuation pages

Check that the complete description stays with its item when it wraps onto another line. On later pages, remove repeated headings from the item table and confirm that no item was skipped or copied twice.

A subtotal or a carried-forward amount belongs in the reconciliation work, rather than becoming another purchased item. Keep separately stated charges distinct from product quantities.

## Reconcile without changing the source

First compare each captured line amount with the printed amount. Quantity multiplied by unit price is a useful check, but discounts and rounding can explain a difference. Keep the stated value and flag discrepancies for review.

Next reconcile the item subtotal with the invoice total using the charges and deductions actually shown. Keep different currencies separate. Do not invent a missing tax amount or exchange rate to make the figures match.

For combined files, keep the source filename and page reference in the working table. They help you locate an item when two suppliers use the same invoice number.

## Continue on the website

Use the [FOVATA commercial invoice workflow](https://fovata.com/solutions/commercial-invoice-pdf-to-excel) for the document task, then check the workbook against the original invoice.

See the [PDF to Excel checklist](pdf-to-excel-checklist.md) for general workbook checks.

[Back to FOVATA Resources](../README.md)

