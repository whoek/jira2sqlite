# scrumdog

scrumdog is a free utility to export Jira Issues to a local SQLite database

For Windows, Linux and Mac binaries -- see <https://github.com/whoek/scrumdog-binaries>    
For notes on how to use -- see <https://scrumdog.app/>   
For background on the project -- see <https://whoek.com/b/jira-to-sqlite-with-scrumdog>

## Pre-requisites to compile the program

Install OCaml -- see <https://ocaml.org/>

Libraries used:
- `curly` - wrapper around the curl command line utility
- `yojson` - parsing library for the JSON format 
- `sqlite3` - SQLite3 bindings for OCaml 

To install the libraries run `opam install curly yojson sqlite3`

## To compile

`opam build`

