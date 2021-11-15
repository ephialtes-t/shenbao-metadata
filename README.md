# Shenbao Metadata

Internet archive has a collection of over 26,900 issues of the Chinese newspaper Shenbao (申報). This can be found here:

[Shenbao on Internet Archive](https://archive.org/search.php?query=title%3A(%E7%94%B3%E5%A0%B1)+AND+description%3A(Shun+Pao)&sort=-date)

However, the vast majority of these issues contain only the year and the month, usually accompanied by some kind of an incrementing number (that is not always consistent).

The metadata for these internet archive entries can be fixed, but the task of adding the full date to over 23,000 issues is a tedious one and lends itself to a collaborative effort. 

This repository hosts a CSV file which lists all the issues that need the day added to the date file. Hopefully we can complete the dates on all issues and I will upload the metadata correction to the dates and also update the title of each entry.

## How to signal contribution

In order to avoid people duplicating their efforts, signal your desire to contribute dates from some of the months or years here:

**[Signal Your Contribution](https://github.com/ephialtes-t/shenbao-metadata/discussions/1)**

More details there on how to contribute.

## Link to the raw CSV file:

Here is a link to the raw CSV (Comma separated values) metadata file:

**[Raw CSV File](https://raw.githubusercontent.com/ephialtes-t/shenbao-metadata/main/metadata.csv)**

Save this from your browser and you can open this in a spreadsheet viewer such as Microsoft Excel, Open Office, or Apple Numbers but please save again as a CSV file when you share it back to us. The first column includes a link to the item on Internet Archive; the second column for your reference includes the title displayed in internet archive, and the final column contains the (usually incomplete) date with year and month.

To help out, volunteers would need to check the pdf of the issue on Internet Archive and add the day to the date column. For example, if the issue checked is January 12, 1880, then 

1880-01

should be changed to:

1880-01-12

and so on...

Please make sure you check the issue itself and confirm that you have the correct Gregorian calendar date (西曆) from the issue. Please do not depend on the incrementing number as this will often lead to errors given the inconsistent nature of this number and the fact that there are often missing issues and other irregularities in the dating.
