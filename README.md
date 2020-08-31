# Web-scrapper-olx-gumtree-otodom
This project is about a creating web scraper for sites olx, gumtree, otodom.

## Project assumptions:

  - Scraper of real estates on site:
    - https://www.olx.pl/,
    - https://www.gumtree.pl/
    - https://www.otodom.pl/
  - Linking to PostgreSQL
  - All data are normalized
 
## Project description:
 
This application is directly commissioned by my client and it's protected by copyright. Thats why I can't post here the code. The whole script is written in python language. Applited external libraries: 
  - requests 
  - bs4 
  - psycopg2
  
This application at beginning jumping from  location to another location and scrape links to direct offer. After collected all unseen offers, program starts visiting downloaded links and collecting data from there. Location used for this purpose are collected directly from working site, this allows us to be sure that we are using the right locations.
 ## Schematic photos
 
 PostgreSQL scheme
 
 ![alt text](https://github.com/wiktorowski-dev/Web-scrapper-gratka-sprzedajemy-licytacje-komornik-WS1/blob/master/file/psotgresql3.png?raw=true)
 
 ---
 
 Classes UML diagram
 
![alt text](https://github.com/wiktorowski-dev/Web-scrapper-olx-gumtree-otodom-WS1/blob/master/files/scrapper%20gumtree%20olx%20otodom2.png?raw=true)
