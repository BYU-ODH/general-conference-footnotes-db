# general-conference-footnotes-db
This repo contains the data used for a research project that analyzes the footnotes of LDS General Conference addresses.
(A link to the published journal article will be here when it's published.)

"Conference Footnotes (April 2022).tsv" is a tab-delimited file which can be downloaded and opened in Google Sheets, Excel, or another spreadsheet app. Each row contains a record for one footnote. The description of the columns are as follows:

*id*: A unique number starting at 1 so that the chronological order of the footnotes can be easily maintained.
*decade*: The decade in which the general conference talk was given. Decades start at the 0th year rather than the 1st year, because we are academic heretics.
*year*: The year in which the general conference talk was given.
*title*: The title of the general conference talk given.
*is_apostle*: A boolean (true or false) for whether the speaker was an apostle at the time giving the talk. For example, Elder Gong's talks before April 2018 are FALSE.
*context*: The text that directly proceeds the footnote number within the text of the address. This is either until the beginning of the paragraph or until the previous footnote number, whichever comes first.
*footnote_text*: This is the text of the actual footnote.
*is_scripture*: A boolean (true or false) for whether the footnote text directly refers to a scripture reference or not.
*length*: The character length of the footnote text.
