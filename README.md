# RemixFBQuotes

I created an interesting Python script which Web scrapes a random quote and it's author and post it as a facebook status  

# *If you want to integrate it in your project or do anything it with , be sure to check LICENSE first .*

## I used the BeautifulSoap python module to scrap quotes from <i>[this site](http://www.quotationspage.com/random.php3)</i>

### Then I used the GraphAPI of Facebook and using an ACCESS_TOKEN I connected to my account .

# How to use it : 
- You have to get an ACCESS TOKEN first from https://developers.facebook.com/tools/explorer
- Clone this project or download .
- Copy and Paste your ACCESS_TOKEN in the FacebookPost.py file through vim or any editor
- Then Simply use <i>$ python FacebookPost.py</i> and open facebook to see the magic :D

### you can use a bash shell script to run this file and sleep for 3600 in a infinite while loop , and it will post a random quote every 1 hour .You can easily do that , and you can make a pull request too if you have any ideas .
