# OpenSourceBookData_Analysis

Open Library is an initiative of the Internet Archive, a 501(c)(3) non-profit, building a digital library of
Internet sites and other cultural artifacts in digital form. In the section Bulk Data Dumps, they provide public
feeds with the library data.

🡪 https://openlibrary.org/developers/dumps

They also provide a shorter versions of the file for developing or exploratory purposes, where the size is
around 140MB of data instead of ~20GB of the original/full file (referring to the “complete dump”).

https://s3-eu-west-1.amazonaws.com/csparkdata/ol_cdump.json

Starting with the short version of this file, pls. download it to your local laptop:

wget --continue https://s3-eu-west-1.amazonaws.com/csparkdata/ol_cdump.json -O
/tmp/ol_cdump.json