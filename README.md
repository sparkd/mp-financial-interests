# MP Financial Interests
## 2010 - 2015.

CSV dataset extracted from the UK House of Commons Register of Members' Financial Interests http://www.publications.parliament.uk/pa/cm/cmregmem/contents1415.htm

The data is available as:

CSV file: data/financial-interests.csv
Google doc: https://docs.google.com/spreadsheets/d/1j3IX-yGOZj1SUNMEs817v9egBPu5YJyVek26t3mGJqQ

The focus of the data extraction is to retrieve the *value* of each interest. As a result, some information for the interests have been discarded.

It also means some interest categories that do not provide a numeric valuation have been excluded.  These are:
* 8 - Land and property
* 9 - Registrable shareholdings
* 11 - Misc.

The date used in the dataset is the registered data, not the actual date of the interest.  The registered date was often better formed, so was used in preference.

The scripts used to create this dataset will be released soon.
