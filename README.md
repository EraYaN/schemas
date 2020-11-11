# Schema example

So this would be for the main data exchange format.

Say you make an export every 2 weeks for people to download.
You make large JSON files for each kind of metadata (TV show, Movies etc) based on the JSON schema's included.

This proposal would be mostly focussed on reducing the number of API calls and output as much info in one call as possible, greatly simplifying usage.

For updates I'd propose a long array of JSON Patches, maybe in chunks of 1 hour for downstream server instances to grab once an hour.