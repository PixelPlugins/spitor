# spitor
-----------------------------
Spitor is a github repository containing text files with web crawl data.
You are free to use this in your search engine or anything else you would like to do with it.
To figure out what file you want:

Decide whether you want a large index or a small one. (If you want a short list, use 'sample' files!)
The filenames are formatted like this:

webcrawl-month-day-year.txt (or for samples, webcrawl-month-day-year-sample.txt.)

If you want to get the latest crawl, just use webcrawl-latest.txt. (latest does not work for samples)

Crawls are lists of websites. Each website is on a new line. If you want the website, its content, and its title, then you should use
webcrawlcontent.txt.

It is always on the latest crawl. Each entry takes up three lines. The first line is the website url, the second is its title, and the third is its content. 
Here is a 3 entry example.

https://www.google.com

Google

<body>html content here...</body>

https://www.bing.com/

Bing

<body>html content here...</body>

http://www.msn.com/

MSN.com - Hotmail, Outlook, Skype, Bing, Latest News, Photos & Videos

<body>html content here...</body>
