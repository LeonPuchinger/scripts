# A collection of convenience scripts i use quite often

Add this to PATH (only works with GNU find):

export PATH="$PATH:$(find <path/to/repo> -type d -printf ":%p")"

Otherwise, just add the individual subdirectories of this repo to PATH by hand.
