# URL-hashing
Purpose of project :- It can easily compress any long URL and can return the original URL from the compressed one also. It can be easily used while sharing long URLs in the teams.

# **Description**
Language used is Python
Bitly URL shortener API is used here along with Python Pyshortener Library.
pyshorteners is a Python lib to help you short and expand urls using the most famous URL Shorteners availables, here the shortener used is Bitly.

# Getting Started
To begin with, Bitly API should be dowloaded but in order to do that one must make a free account on Bitly and generate the acess code from there and copy it. Then we need to download
and install Bitly API in local machine and after extracting it, it has to be included in the current folder using the following commands in command prompt
cd downloads
cd bitly-api-python-master

Also pyshortener library is to be installed for which the command is: pip install pyshorteners 

# Modification before running
One can generate their own Access code from bitly before running the code

# Execution
After importing libraries, program asks the user for Long URL as input and returns a short url for it. If the user passes short url in place of long url, an error will come.

Also url expansion froms hort url is included which works the other way round and return the long url from short url.





