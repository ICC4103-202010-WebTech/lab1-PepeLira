
### Lab 1 Report

by: José Lira

#### 1. How is the list of news articles structured with HTML?



After initiate the HTML file with a tag <html>, in one large body that contains
a big borderless Table how contains the content of the page.

This content is divided in three main areas:    

* At the Head: A Table containing The Logo, an index of the main pages of the website and the login link.

* In the midlle: Another Table how contains an item list with the Articles ordered by votes.

* On the bottom: The last Table containing another index with the less common pages of the site and a search bar.

Comments: each table is borderless, and also contains some empty rows to use as spacers.





#### 2. How are these files different? What is their purpose?




The .js are java script files how contains functionality to the page.

For example it can control the hierarchy behind the votes order of the item list.

The .css are pages of style, that contains things like the typographic, the size or the stylish for one big area of the page o for a specific one.

Another difference is that both of them uses different programing languages.




#### 3. How many requests has it taken for the browser to download the Hacker News main page?
#### What are the HTTP request methods in each case?
*Check out the HTTP response headers and find out what kind of web server is used for this website.*




In my browser has taked 8 request each with a Get method.

Searching in the HTTP response headers shows that the server is called Nginx.
Affter googled it seens that is a web server / reverse proxy.

> A reverse proxy, by contrast, appears to the client just like an ordinary web server. No special configuration on the client is necessary. The client makes ordinary requests for content in > > the name-space of the reverse proxy. The reverse proxy then decides where to send those requests, and returns the content as if it was itself the origin.
