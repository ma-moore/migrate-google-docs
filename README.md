# migrate-google-docs
Bash script for moving google docs while mantaining file structure

## Overview


## Usage

To search for and move all the google docs within a folder, run the following:

        find  . \( -name "*.gsheet" -or -name "*.gdoc" -or -name "*.gslides" -or -name "*.gdraw" -or -name "*.gmap" \)  -exec ../move-docs {}  \;