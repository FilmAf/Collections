# Collections

As we do not have a live database and since there are 15 million collection
entries, we had to split the collections in two pieces.  The zipped files
contain who has what. The name of the file is the first collection in that
archive.

For example the first collection file is named "collections-0001-0-jd-0",
the second is "collections-0002-45degreeangel".  So if you are looking for
"44loveletter" that will be on the first file because the second begins
with "45degreeangel".

The all-titles.txt file contains the title information. You will need to
merge both files. The easiest way to do that is with excel and doing a
VLOOKUP formula.  We will do a video showing how.  Both files are sorted
by dvd_id to make it easier to merge them if you are doing it in some
other way.

It is possible that someone will step forward and get this data in a
easier for people to get at it.


Fields in all-titles.txt
========================
dvd_id: id used to link collections and titles

dvd_title: title/description of the dvd, blu-ray, hd-dvd or film

film_rel_year: release year for listings with a single feature

director: director of the features in the listing

publisher: studio/publisher of the dvd, blu-ray, hd-dvd or film

orig_language: original languages of the feature -- languages.txt

country: country for this dvd, blu-ray, hd-dvd edition -- see countries.txt

region: region coding for the dvd, blu-ray

genre: primary genre for the feature

media_type: type of media: dvd, blu-ray, etc.

num_titles: number of titles

num_disks: number of disks

rel_status: release status: out of print, current, etc.

film_rel_dd: release date for the original feature

dvd_rel_dd: release date for dvd, blu-ray, hd-dvd

dvd_oop_dd: date dvd, blu-ray, hd-dvd went out of print

imdb_id: imdb id for the features in the listing

list_price: list price as provided by the person that submitted the listing

sku: studio product code

upc: upc bar code

asin: amazon product identifier

amz_country: country/site where amazon lists this title (use with asin)


Fields in collection files
==========================
user_id: id used to access the collection in the sire as romeo.filmaf.com

dvd_id: id used to link collections and titles

folder: folder where the title was placed

sort_text: sort overwrite as specified by the collection owner

genre_overwrite: genre overwrite as specified by the collection owner

user_film_rating: feature rating as provided by the collection owner

user_dvd_rating: edition rating as provided by the collection owner

comments: comments by the collection owner

owned_dd: date the title was acquired as provided by the collection owner
