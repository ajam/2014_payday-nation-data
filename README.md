Payday Nation
===

### About

Data from the [Payday Nation](http://projects.aljazeera.com/2014/payday-nation/index.html) project, published June 17, 2014. The data was, in part, obtained via a Freedom of Information request to the Federal Trade Commission by Julia Harte, Joanna Zuckerman Bernstein & Nick Nehamas and was combined with subsequent reporting to link payday lending companies to their associated tribe. Geocoding was performed using [Texas A&M GeoServices](http://geoservices.tamu.edu/). OCR was performed by [ABBYY FineReader Express](http://abbyy.com).

The stories and graphics for [Payday Nation](http://projects.aljazeera.com/2014/payday-nation/index.html) were reported and produced in collaboration with the Stabile Center for Investigative Journalism at Columbia University in New York.

__All files in this folder can be found in `2014_payday-nation.zip`__.

### Contact

If you have questions about this data email us at [ajammultimedia@gmail.com](mailto:ajammultimedia@gmail.com?subject=Payday%20Nation%20data).

### Caveats

These complaints have not been investigated by the FTC nor have they been independently verified.

# What's here? 

This data powers the interactive [on this page](http://projects.aljazeera.com/2014/payday-nation/complaints.html). This repo contains two groups of data: 

1. Detailed complaints against ten payday lending companies including the text of the consumer's complaint: `detailed-complaint-texts.csv` and associated PDF and RTF files.
2. Less detailed but more comprehensive data showing the city and state of complaints against a much larger group of payday lenders: `pdl-complaints.csv`.
3. Topojson files of US states. `us-states.json` has land and state areas. `us.json` has counties as well.

Both datasets cover complaints issued between February 2013 and February 2014.

## Detailed complaint text data

The detailed data includes full text complaints from the following companies, which are associated with Native American tribes:

Tribe: __Wakpamni Lake Community of the Oglala Sioux Tribe__

* Fast Money Store
* Boulevard Cash
* Cash Cloud

Tribe: __Habematolel Pomo of Upper Lake__

* Golden Valley Lending
* Mountain Summit Financial
* Silver Cloud Financial

Tribe: __La Posta Band of Mission Indians__

* Harvest Moon Loans
* Gentle Breeze Loans

Tribe: __Guidiville Indian Rancheria__

* National Payday Loans
* Gallery Cash Now

File descriptions:

* `Complaints FOIA.pdf` - Complaints filed with the FTC against the companies affiliated with the Wakpamni Lake Community of the Oglala Sioux Tribe.
* `Complaints FOIA.rtf` - An OCRd version of `Complaints FOIA.pdf`
* `Full Complaints.pdf` - Complaints filed with the FTC against the other companies listed above.
* `Full Complaints.rtf` - An OCRd version of `Full Complaints.pdf`
* `detailed-complaint-texts.csv` - Data extracted from the above PDFs that had complaint text. Also includes complaint metadata including reference number, consumer age range, consumer city and consumer state (with lat/lngs), affiliated tribe, tribe city and state, loan amount requested, and loan amount paid.

## Less detailed geographic data

File description: 

* `pdl-complaints.csv` - A list of all complaints against the 23 tribes, listed below, between February 2013 and February 2014. This data is not as detailed as the PDF complaints but it contains information on more companies. Obtaining full complaint data for every complaint would have significantly delayed the project.

Tribes in `pdl-complaints.csv`:

* Miami Tribe of Oklahoma
* Otoe-Missouria Tribe
* Tunica-Biloxi Tribe of Louisiana
* Chippewa-Cree Tribe of Rocky Boy Montana
* Santee Sioux Tribe of Nebraska
* Modoc Tribe of Oklahoma
* Cheyenne River Sioux Tribe
* Fort Belknap Indian Community
* Guidiville Indian Rancheria
* Lac Vieux Desert Band of Lake Superior Chippewa Indians
* Habematolel Pomo of Upper Lake
* Wakpamni Lake Community of the Oglala Sioux Tribe
* United Keetoowah Band of Cherokee Indians
* Turtle Mountain Band of Chippewa Indians
* Mandan, Hidatsa, and Arikara Nation
* La Posta Band of Mission Indians
* Picayune Rancheria of the Chukchansi Indians
* Big Lagoon Rancheria
* Iipay Nation of Santa Ysabel
* Lac du Flambeau Band of Lake Superior Chippewa Indians
* Big Valley Rancheria
* Resighini Rancheria
* Sokaogon Chippewa Community

Companies in `pdl-complaints.csv`: 

* 500FastCash
* American Loans
* American Web Loan
* Ameriloan
* AMG Services
* Arrow One
* Bayside Cash
* Big Eye Lending
* Black Bear Advance
* BLR Tribal Services
* Blue King
* Bluechip Financial
* Boulevard Cash
* Bright Day Loans
* Cash Cloud
* Castle Payday
* Clear Loan Solutions
* Clearwater Lending
* Cover Me Cash
* Fast Money Store
* Fireside Cash
* First American Capital Resources
* Gallery Cash Now
* Golden Valley
* Great Plains Lending
* Green Corp Cash
* Green Trust
* Greenline Loans
* Harvest Moon Loans
* Island Finance
* La Posta
* Lakota Cash
* Miami Nation Enterprises
* Minute Funds
* Mobiloans
* Money Loans Quick
* Mountain Summit
* MTE Financial
* National Payday Loan
* Niizh
* Northern Plains Funding
* OneClickCash
* Pacific Cash
* Payday Financial
* Plain Green
* Red Cedar Services
* Red Rock Tribal Lending
* Riverbend Finance
* Seaside Dollar
* Seaside Payday
* SFS
* Silver Cloud
* Sky Lending
* Sovereign Advance
* Splash Cash Advance
* Spotloan
* Target Finance
* Tremont Lending
* Tribal Financial Services
* Tribal Lending Enterprise
* United Cash Loans
* US Fast Cash
* West River
* Western Sky Financial
