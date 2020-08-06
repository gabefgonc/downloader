# Downloader

A simple python script that uses flask to expose files to download

## Installation

There are two ways to use this. Installing it (moving to PATH) or simply running the script on any directory.

* Method 1: Installing
  
    1. Clone this repo and CD into it:
        > git clone https://github.com/gabefgonc/downloader; cd downloader

    2. Install (replace /usr/bin with any other path in your $PATH)

        > sudo cp downloader /usr/bin/

    3. Run (see USAGE for more info):
        > downloader
   
* Method 2: Just running the script
    
    1. Clone this repo and CD into it:
        > git clone https://github.com/gabefgonc/downloader; cd downloader
    2. Just run (see USAGE for more info):
        > ./downloader

## Usage
 > downloader dir [--exclude "file1,file2"] [--title "title"]

Options:
    
--exclude

Specify files that are not going to be served

The files must be separated by commas

--title

Specify a title to the page header.

> if the title contains spaces, wrap it with quotation marks


## That's it! Thanks for reading!

