# TMS to XLSX converters
Two fast no-frills scripts to convert tmx translation memories into Excel spreadsheets.
- tmx_to_excel_2langs.ipynb: simple dual-language version to be used when we know for sure that the there are only two languages in the TM and we know which languages are there. If there are more than two languages in a segment, the scrip will give warning but will save the first two only. 
Output: an xlsx file with two columns: source и target.
- tmx_to_excel_multiple_langs.ipynb: converts a ТМ with several languages into an xlsx spreadsheet with columns names same as language names in the TM.