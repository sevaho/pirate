# Pirate

```
  Usage: /home/sevaho/scripts/pirate [OPTIONS]... [ARGS]...

    Very simple bash script to download any magnet link from the TPB and load them up in rtorrent.

  OPTIONS: 
  
    -m                  Top movies
    -s                  Top series
    -h                  Usage
    -l <limit>          Size of the output list
    -o <order>          Order of your search query

                        1 - name ascending; 
                        2 - name descending;
                        3 - recent first; 
                        4 - oldest first;
                        5 - size descending; 
                        6 - size ascending;
                        7 - seeds descending; 
                        8 - seeds ascending;
                        9 - leechers descending; 
                        10 - leechers ascending;

    -?                  Usage

  EXAMPLES:
    
    pirate -l 60 -m
    pirate -l 10 -o 99 "legal movies"
```
