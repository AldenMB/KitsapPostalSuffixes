Kitsap county data was acquired from https://www.kitsap.gov/assessor/Pages/DataDownload.aspx, including specific files:
https://www.kitsap.gov/assessor/Documents/Property_addresses.txt
https://www.kitsap.gov/assessor/Documents/property_addresses.pdf
note that the property addresses are tab-separated

USPS data downloaded from https://pe.usps.com/text/pub28/28apc_002.htm, "Publication 28 - Postal Addressing Standards > Appendix C > C1 Street Suffix Abbreviations"

All data processing is done kitsap_streets.ipynb. Data is output to kitsap_suffixes.tsv, and then copied to kitsap_suffixes.xlsx using Libreoffice.