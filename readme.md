# Elgg Dash Docset
This is a crude attempt to get the [Elgg](http://elgg.org) documentation into the wonderful tool [Dash](http://kapeli.com/).

This was created from the source in :octocat:[Elgg/Elgg](https://github.com/elgg/elgg) using Doxygen and the instructions inside Dash.

## Prerequisites

`brew install doxygen`

## Instructions

Update the submodule.

`
doxygen Doxyfile
cd output/html
make
cp -r org.elgg.docst <wherever it should go>
`
