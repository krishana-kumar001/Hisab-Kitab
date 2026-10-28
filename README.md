# Hisab Kitab

Personal money and editing-business ledger.

**Live app:** https://claude.ai/artifact/JUmMFNP9sXXTzkaEswQ6E6 (private, opens only when you are signed in to your own Claude account)

- `index.html`: the web app (personal + editing books, budgets, pending client payments, CSV/JSON backup, Excel import and export).
- `Hisab-Kitab.xlsx`: Excel version with three sheets: Personal, Editing, Overview. Type entries from row 6 in Personal and Editing (row 6 is an example, delete it). Overview calculates month-wise totals for the financial year (April to March) by formula. Set the financial year and tax % in the two yellow cells at the top of Overview.

## Moving data between the Excel file and the app

In the app, open Settings and use **Import from Excel** to read the Personal and Editing sheets (columns are found by their headings). Importing the same file twice does not create duplicates. **Download as Excel** writes the app's entries in the same column layout.
