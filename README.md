# xlsx-to-csv-

Excel can save a spreadsheet to a CSV file with a few mouse clicks, but if you had to convert hundreds of
Excel files to CSVs, it would take hours of clicking. write a program that reads all the Excel files in a working
directory and outputs them as CSV files.

A single Excel file might contain multiple sheets; you’ll have to create one CSV file per sheet. The filenames of
the CSV files should be &lt;excel filename&gt;_&lt;sheet title&gt;.csv, where &lt;excel filename&gt; is the filename of the
Excel file without the file extension (for example,&#39;spam_data&#39;, not &#39;spam_data.xlsx&#39;) and &lt;sheet
title&gt; is the string from the Worksheet object’s title variable.
