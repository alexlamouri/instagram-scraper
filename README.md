# instagram-scraper

## Description

InstagramScraper uses the Requests external library to perform an HTTP request on a given URL and the BeautifulSoup library to extract the HTML code from the given website.

InstagramScraper performs analytics on multiple Instagram accounts and outputs the account name, account handle, account bio, account type, account website, number of followers, number of following and number of posts.

InstagramScraper is capable of outputting data directly to the console or exporting it to a CSV file.

## Usage

InstagramScraper prompts the user for the URL to an Instagram account. The user inputs the URL to the Instagram account and the program then performs analytics on the Instagram account.

The user is prompted for the method of output. If the user chooses the console as the method of output, the output of the programs will be displayed on the user’s console. If the user chooses a CSV file as the method of output, the user will be prompted for the name of a CSV file. A CSV file will then be created with the CSV module, timestamped using the datetime module and the output will then be written to it. 

## Setup

InstagramScraper relies on two external libraries that require installation.

Requests can be installed through here:
http://docs.python-requests.org/en/master/user/install/

BeautifulSoup can be installed through here: 
https://www.crummy.com/software/BeautifulSoup/#Download
