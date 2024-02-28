# gncsv is a fork of Go's `encoding/csv` package.

The purpose of this package is to add ability to set a character for field
boundaries. It is a common practice "in the wild" to set field boundary
character to something different from `"`. Sometimes it is setup
to empty string. Here we try to add such option. 
