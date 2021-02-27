# Torrent Hound
Search torrents from multiple websites via the CLI


### Requirements
- Python 3.9
- bs4
- clint
- pyperclip
- humanize
- VeryPrettyTable
- cfscrape


### Installation
Clone the repository and run torrent-hound.py


### Update existing Intallation
Run `git pull` in the shell after navigating to the `torrent-hound` directory


### Usage
Navigate to the repository root and execute below command
`./torrent-hound.py [search-query]` or simply `./torrent-hound.py`


### Menu
Available Commands :

  1. `m<result number>` - Print magnet link of selected torrent   
  2. `c<result number>` - Copy magnet link of selected torrent to clipboard
  3. `d<result number>` - Download torrent using default torrent client
  4. `o<result number>` - Open the torrent page of the selected torrent in the default browser
  5. `cs<result number>` - Copy magnet link and open Seedr.cc
  6. `p<optional choice>` - Print top 10 results from each website for the given query
     
     `<choice>` : [{default : 1}, {0 : Print formatted result}, {1 : Pretty print results}]        
  7. `s` - Enter a new query to search for over all avilable torrent websites
  8. `r` - Repeat last search (with same query)


### Help
In case of an `SSL Error`, consult [these answers on Stackoverflow](https://stackoverflow.com/questions/31649390/python-requests-ssl-handshake-failure) for potential fixes.
