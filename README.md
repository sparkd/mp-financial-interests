# MP Financial Interests
## 2010 - 2018.

CSV dataset extracted from the UK House of Commons Register of Members' Financial Interests http://www.publications.parliament.uk/pa/cm/cmregmem/contents1415.htm

The data is available as CSV file: https://github.com/sparkd/mp-financial-interests/tree/master/data/financial-interests.csv, parsed on 7th April 2018.

Data extracted:

| Field        | Description | 
| ------------ |-------------| 
| Member name  | The name of the Member of Parliament (honorifics removed) | 
| Title        | Interest type title e.g Employment and earnings |
| Type code    | Numeric type code 1-10, denoting interest type.  Important note: the codes changed in 2015.  So Employment and earnings has code 2 in sessions before 2015; code 1 in post-2015 sessions.) |
| Amount       | The registered amount of the interest, in pounds.  |
| Date         | The registered date of the interest (not necessarily the actual date of the interest) |
| Description  | Full description of the interest, extracted directly from register. |
| Session      | The parliamentary session the interest is included in - e.g. 2010-12; 2015-16 |


The script used to create this dataset is available at: [https://github.com/benscott/mp-financial-interests](https://github.com/benscott/mp-financial-interests)
